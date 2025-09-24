---
title: "[MM'24]Decoder Pre-Training with only Text for Scene Text Recognition"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Shuai Zhao
- Yongkun Du
- Zhineng Chen
- Yu-Gang Jiang



# Author notes (optional)

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Corresponding author'

date: '2024-7-16T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *ACM International Conference on Multimedia (MM) 2024*
publication_short: In *ACM International Conference on Multimedia (MM) 2024*

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

url_pdf: 'https://arxiv.org/abs/2408.05706'
url_code: 'https://github.com/Topdu/OpenOCR'
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
Scene text recognition (STR) pre-training methods have achieved remarkable progress, primarily relying on synthetic datasets. However, the domain gap between synthetic and real images poses a challenge in acquiring feature representations that align well with images on real scenes, thereby limiting the performance of these methods. We note that vision-language models like CLIP, pre-trained on extensive real image-text pairs, effectively align images and text in a unified embedding space, suggesting the potential to derive the representations of real images from text alone. Building upon this premise, we introduce a novel method named Decoder Pre-training with only text for STR (DPTR). DPTR treats text embeddings produced by the CLIP text encoder as pseudo visual embeddings and uses them to pre-train the decoder. An Offline Randomized Perturbation (ORP) strategy is introduced. It enriches the diversity of text embeddings by incorporating natural image embeddings extracted from the CLIP image encoder, effectively directing the decoder to acquire the potential representations of real images. In addition, we introduce a Feature Merge Unit (FMU) that guides the extracted visual embeddings focusing on the character foreground within the text image, thereby enabling the pre-trained decoder to work more efficiently and accurately. Extensive experiments across various STR decoders and language recognition tasks underscore the broad applicability and remarkable performance of DPTR, providing a novel insight for STR pre-training. Code is available at https://github.com/Topdu/OpenOCR
