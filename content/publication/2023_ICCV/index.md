---
title: 'MRN: Multiplexed Routing Network for Incremental Multilingual Text Recognition'

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Tianlun Zheng
- Zhineng Chen
- Bingchen Huang
- Wei Zhang
- Yu-Gang Jiang

# Author notes (optional)

author_notes:
  - 
  - 'Corresponding author'

date: '2023-07-14T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: 

# Summary. An optional shortened abstract.

summary: 

tags: []

# Display this page in the Featured widget?

featured: true

# Custom links (uncomment lines below)

# links:

# - name: Custom Link

# url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/ICCV2023/html/Zheng_MRN_Multiplexed_Routing_Network_for_Incremental_Multilingual_Text_Recognition_ICCV_2023_paper.html'
url_code: 'https://github.com/simplify23/MRN'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image

# To use, add an image named `featured.jpg/png` to your page's folder.

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).

# Associate this publication with one or more of your projects.

# Simply enter your project's folder or file name without extension.

# E.g. `internal-project` references `content/project/internal-project/index.md`.

# Otherwise, set `projects: []`.

# projects:

# - example

# Slides (optional).

# Associate this publication with Markdown slides.

# Simply enter your slide deck's filename without extension.

# E.g. `slides: "example"` references `content/slides/example/index.md`.

# Otherwise, set `slides: ""`.

# slides: example
---

Multilingual text recognition (MLTR) systems typically focus on a fixed set of languages, which makes it difficult to handle newly added languages or adapt to ever-changing data distribution. In this paper, we propose the Incremental MLTR (IMLTR) task in the context of incremental learning (IL), where different languages are introduced in batches. IMLTR is particularly challenging due to rehearsal-imbalance, which refers to the uneven distribution of sample characters in the rehearsal set, used to retain a small amount of old data as past memories. To address this issue, we propose a Multiplexed Routing Network (MRN). MRN trains a recognizer for each language that is currently seen. Subsequently, a language domain predictor is learned based on the rehearsal set to weigh the recognizers. Since the recognizers are derived from the original data, MRN effectively reduces the reliance on older data and better fights against catastrophic forgetting, the core issue in IL. We extensively evaluate MRN on MLT17 and MLT19 datasets. It outperforms existing general-purpose IL methods by large margins, with average accuracy improvements ranging from 10.3% to 35.8% under different settings. Code is available at https://github.com/simplify23/MRN.