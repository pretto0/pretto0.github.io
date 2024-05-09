---
title: 'Dual Contrastive Learning Guided Pathological Image Re-Staining'

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Yuexiao Liang
- Zhineng Chen
- Xin Chen
- Xin Chen
- Caiyan Jia
- Xiongjun Ye
- Xieping Gao

# Author notes (optional)

author_notes:
  - 
  - 'Corresponding author'

date: '2024-03-24T00:00:00Z'
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

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10446668'
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

Pathological virtual re-staining is a valuable research topic in AI-aided diagnosis, as it reduces the need for costly and time-consuming physical staining. However, existing methods still suffer from the insufficient ability to preserve tissue microstructure and cellular details, making the generated images less convincing. In this paper, we propose a CycleGAN-based dual contrastive learning re-staining method called DCLRStain. DCLRStain establishes dual contrastive learning between the source and re-stained image domains, conducting negative sampling within each image pair from both domains. It guides the model’s attention to finer content such as cellular details. Meanwhile, DCLRStain introduces a structural similarity-based loss term that further forces the tissue microstructure to be consistent between the source and re-stained images. Experimental results demonstrate that DCLRStain yields competitive quantitative scores compared to state-of-the-art models and maintains superior qualitative performance. Moreover, DCLRStain achieves higher accuracy in the downstream classification task.