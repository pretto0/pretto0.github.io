---
title: 'Bi-Directional Feature Fusion Generative Adversarial Network for Ultra-High Resolution Pathological Image Virtual Re-Staining'

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Kexin Sun
- Zhineng Chen
- Gongwei Wang
- Jun Liu
- Xiongjun Ye
- Yu-Gang Jiang

# Author notes (optional)

author_notes:
  - 
  - 'Corresponding author'
  - 
  - 

date: '2023-02-28T00:00:00Z'
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

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2023/html/Sun_Bi-Directional_Feature_Fusion_Generative_Adversarial_Network_for_Ultra-High_Resolution_Pathological_CVPR_2023_paper.html'
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

The cost of pathological examination makes virtual re-staining of pathological images meaningful. However, due to the ultra-high resolution of pathological images, traditional virtual re-staining methods have to divide a WSI image into patches for model training and inference. Such a limitation leads to the lack of global information, resulting in observable differences in color, brightness and contrast when the re-stained patches are merged to generate an image of larger size. We summarize this issue as the square effect. Some existing methods try to solve this issue through overlapping between patches or simple post-processing. But the former one is not that effective, while the latter one requires carefully tuning. In order to eliminate the square effect, we design a bi-directional feature fusion generative adversarial network (BFF-GAN) with a global branch and a local branch. It learns the inter-patch connections through the fusion of global and local features plus patch-wise attention. We perform experiments on both the private dataset RCC and the public dataset ANHIR. The results show that our model achieves competitive performance and is able to generate extremely real images that are deceptive even for experienced pathologists, which means it is of great clinical significance.