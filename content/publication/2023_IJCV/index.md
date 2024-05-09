---
title: 'CDistNet: Perceiving Multi-domain Character Distance for Robust Text Recognition'

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Tianlun Zheng
- Zhineng Chen
- Shancheng Fang
- Hongtao Xie
- Yu-Gang Jiang

# Author notes (optional)

author_notes:
  - 
  - 'Corresponding author'

date: '2023-09-04T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-09-24T00:00:00Z'
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

url_pdf: 'https://link.springer.com/article/10.1007/s11263-023-01880-0'
url_code: 'https://github.com/simplify23/CDistNet'
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
The transformer-based encoder-decoder framework is becoming popular in scene text recognition, largely because it naturally integrates recognition clues from both visual and semantic domains. However, recent studies show that the two kinds of clues are not always well registered and therefore, feature and character might be misaligned in difficult text (e.g., with a rare shape). As a result, constraints such as character position are introduced to alleviate this problem. Despite certain success, visual and semantic are still separately modeled and they are merely loosely associated. In this paper, we propose a novel module called multi-domain character distance perception (MDCDP) to establish a visually and semantically related position embedding. MDCDP uses the position embedding to query both visual and semantic features following the cross-attention mechanism. The two kinds of clues are fused into the position branch, generating a content-aware embedding that well perceives character spacing and orientation variants, character semantic affinities, and clues tying the two kinds of information. They are summarized as the multi-domain character distance. We develop CDistNet that stacks multiple MDCDPs to guide a gradually precise distance modeling. Thus, the feature-character alignment is well build even though various recognition difficulties are presented. We verify CDistNet on ten challenging public datasets and two series of augmented datasets created by ourselves. The experiments demonstrate that CDistNet performs highly competitively. It not only ranks top-tier in standard benchmarks, but also outperforms recent popular methods by obvious margins on real and augmented datasets presenting severe text deformation, poor linguistic support, and rare character layouts. In addition, the visualization shows that CDistNet achieves proper information utilization in both visual and semantic domains. Our code is available at https://github.com/simplify23/CDistNet.