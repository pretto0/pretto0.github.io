---
title: 'AS-Net: Attention Synergy Network for skin lesion segmentation'

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Kai Hu
- Jing Lu
- Dongjin Lee
- Dapeng Xiong
- Zhineng Chen


# Author notes (optional)

author_notes:
  - 
  - 

date: '2022-09-01T00:00:00Z'
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

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0957417422005139'
url_code: ''
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
Accurate skin lesion segmentation in dermoscopic images is crucial to the early diagnosis of skin cancers. However, it remains a challenging task due to fuzzy lesion boundaries, irregular lesion shapes, and the existence of various interference factors. In this paper, a novel Attention Synergy Network (AS-Net) is developed to enhance the discriminative ability for skin lesion segmentation by combining both spatial and channel attention mechanisms. The spatial attention path captures lesion-related features in the spatial dimension while the channel attention path selectively emphasizes discriminative features in the channel dimension. The synergy module is designed to optimally integrate both spatial and channel information, and a weighted binary cross-entropy loss function is introduced to emphasize the foreground lesion region. Comprehensive experiments indicate that our proposed model achieves the state-of-the-art performance with the highest overall score in the ISIC2017 challenge, and outperforms several popular deep neural networks on both ISIC2018 and PH2 datasets.