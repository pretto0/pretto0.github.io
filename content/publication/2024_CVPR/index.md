---
title: "[CVPR'24]Learning to Rank Patches for Unbiased Image Redundancy Reduction"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Yang Luo
- Zhineng Chen
- Peng Zhou
- Zuxuan Wu
- Xieping Gao
- Yu-Gang Jiang

# Author notes (optional)

author_notes:
  - 
  - 'Corresponding author'

date: '2024-03-31T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2024*
publication_short: In *IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2024*

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

url_pdf: 'https://arxiv.org/abs/2404.00680'
url_code: 'https://github.com/irsLu/ltrp'
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

Images suffer from heavy spatial redundancy because pixels in neighboring regions are spatially correlated. Existing approaches strive to overcome this limitation by reducing less meaningful image regions. However, current leading methods rely on supervisory signals. They may compel models to preserve content that aligns with labeled categories and discard content belonging to unlabeled categories. This categorical inductive bias makes these methods less effective in real-world scenarios. To address this issue, we propose a self-supervised framework for image redundancy reduction called Learning to Rank Patches (LTRP). We observe that image reconstruction of masked image modeling models is sensitive to the removal of visible patches when the masking ratio is high (e.g., 90\%). Building upon it, we implement LTRP via two steps: inferring the semantic density score of each patch by quantifying variation between reconstructions with and without this patch, and learning to rank the patches with the pseudo score. The entire process is self-supervised, thus getting out of the dilemma of categorical inductive bias. We design extensive experiments on different datasets and tasks. The results demonstrate that LTRP outperforms both supervised and other self-supervised methods due to the fair assessment of image content.

