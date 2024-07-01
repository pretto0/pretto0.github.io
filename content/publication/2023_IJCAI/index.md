---
title: "[IJCAI'23]TPS++: Attention-Enhanced Thin-Plate Spline for Scene Text Recognition"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Tianlun Zheng
- Zhineng Chen
- Jinfeng Bai
- Hongtao Xie
- Yu-Gang Jiang

# Author notes (optional)

author_notes:
  - 
  - 'Corresponding author'

date: '2023-05-09T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *International Joint Conference on Artificial Intelligence (IJCAI) 2023*
publication_short: In *International Joint Conference on Artificial Intelligence (IJCAI) 2023*

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

url_pdf: 'https://arxiv.org/abs/2305.05322'
url_code: 'https://github.com/simplify23/TPS_PP'
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

Text irregularities pose significant challenges to scene text recognizers. Thin-Plate Spline (TPS)-based rectification is widely regarded as an effective means to deal with them. Currently, the calculation of TPS transformation parameters purely depends on the quality of regressed text borders. It ignores the text content and often leads to unsatisfactory rectified results for severely distorted text. In this work, we introduce TPS++, an attention-enhanced TPS transformation that incorporates the attention mechanism to text rectification for the first time. TPS++ formulates the parameter calculation as a joint process of foreground control point regression and content-based attention score estimation, which is computed by a dedicated designed gated-attention block. TPS++ builds a more flexible content-aware rectifier, generating a natural text correction that is easier to read by the subsequent recognizer. Moreover, TPS++ shares the feature backbone with the recognizer in part and implements the rectification at feature-level rather than image-level, incurring only a small overhead in terms of parameters and inference time. Experiments on public benchmarks show that TPS++ consistently improves the recognition and achieves state-of-the-art accuracy. Meanwhile, it generalizes well on different backbones and recognizers. Code is at https://github.com/simplify23/TPS_PP.
