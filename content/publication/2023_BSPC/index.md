---
title: 'MMSRNet: Pathological image super-resolution by multi-task and
multi-scale learning'

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Xinyue Wu
- Zhineng Chen
- Changgen Peng
- Xiongjun Ye

# Author notes (optional)

author_notes:
  - 
  - 
  - 'Corresponding author'
  - 

date: '2023-03-01T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *Biomedical Signal Processing and Control (BSPC) 2023*
publication_short: In *Biomedical Signal Processing and Control (BSPC) 2023*

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

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S1746809422008825'
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

Pathological diagnosis is the gold standard for disease assessment in clinical practice. It is conducted by inspecting the specimen at the microscopical level. Therefore, a very high-resolution pathological image that precisely describes the submicron-scale appearance is essential in the era of digital pathology, which is not easily obtained. Recently, pathological image super-resolution (SR) has shown promising prospects in bridging this gap. However, existing studies have not fully explored the peculiarity of pathological data, which contains several gradually enlarged images describing the specimen at different magnifications. In this paper, we propose a novel MMSRNet that formulates the pathological image SR in a multi-task learning way. It adds an image magnification classification branch on top of the CNN-based SR network, e.g., RCAN. Therefore, the learning objective is transformed into performing the SR while classifying the magnification as accurately as possible. The incorporated classification label guides the network to learn a more powerful feature representation. Meanwhile, the multi-task learning paradigm also encourages the joint learning of multi-scale mapping functions corresponding to multiple magnifications. It thus enables the learned model to adaptively accommodate the magnification variants, overcoming the problem that performing SR from different magnifications is treated as independent tasks in existing studies. Extensive experiments are conducted to validate the effectiveness of MMSRNet. It not only gains better performance in performing SR across magnifications and scaling factors, but also exhibits attractive plug-and-play nature when RCAN is substituted by other SR networks. The generated images are also supposed to be helpful in clinical diagnosis.