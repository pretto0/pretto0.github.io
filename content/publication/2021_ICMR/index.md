---
title: "[ICMR'21]Bag of Tricks for Building an Accurate and Slim Object Detector for Embedded Applications"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Yongkun Du
- Zhineng Chen
- Caiyan Jia
- Xuanya Li
- Yu-Gang Jiang


# Author notes (optional)

author_notes:
  - 
  - 

date: '2021-04-01T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *International Conference on Multimedia Retrieval (ICMR) 2021*
publication_short: In *International Conference on Multimedia Retrieval (ICMR) 2021*

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

url_pdf: 'https://dl.acm.org/doi/10.1145/3460426.3463659'
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
Object detection is an essential computer vision task that possesses extensive application prospects in on-road applications. Copious novel methods have been proposed in this branch recently. However, the majority of them have high computational cost, making them intractable to be deployed on embedded devices. In this paper, taking YOLOv5s, the smallest model in the YOLOv5 family, as the baseline, we explore a bag of tricks that improve the detection performance for a specified on-road application, under the premise of ensuring that it does not increase the computational cost of YOLOv5s. Specifically, we introduce relevantly external data to deal with the problems of sample imbalance. Meanwhile, knowledge distillation is employed to transfer knowledge from a cumbersome model to a compact model, where a united distillation scheme is developed to enhance the effectiveness. In addition, a pseudo-label based training strategy is utilized to further learn from the biggest YOLOv5 model. We have applied the above tricks to the Embedded Deep Learning Object Detection Model Compression Competition for Traffic in Asian Countries held in conjunction with ICMR 2021. The experiments have shown that all the tricks are useful. Their combination have built an accurate and slim detection model. It is highly competitive and has been ranked 2nd place in the competition. We believe the tricks are also meaningful for building other application-oriented object detectors.
