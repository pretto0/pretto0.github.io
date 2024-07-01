---
title: "[IJMLC'23]Pathological image super‑resolution using mix‑attention generative 
adversarial network"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Zhineng Chen
- Jing Wang
- Caiyan Jia
- Xiongjun Ye

# Author notes (optional)

author_notes:
  - 
  - 
  - 'Corresponding author'

date: '2023-05-08T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.

publication: In *International Journal of Machine Learning and Cybernetics (IJMLC) 2023*
publication_short: In *International Journal of Machine Learning and Cybernetics (IJMLC) 2023*

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

url_pdf: 'https://link.springer.com/article/10.1007/s13042-023-01806-9#Abs1'
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
Image super-resolution (SR) is a fundamental research task in low-level vision. Recently it has been applied to digital pathology to build transformations from low-resolution (LR) to super-resolved high-resolution (HR) images, which benefits pathological image sharing, storage, management, etc. However, existing studies on pathological image SR are mostly carried out on simulated dataset. It cannot fully reveal the challenge of real-world SR. Meanwhile, these studies rarely investigate SR models from a pathological-tailored perspective. This paper aims to promote studies on pathological image SR from the two aspects. Firstly, we construct PathImgSR, a dataset containing real-captured paired LR-HR pathological images by leveraging the progressively imaging property of pathological images. Second, we develop MASRGAN, a GAN-based mix-attention network to implement the SR. It devises a mix-attention block that is featured by modeling the channel and spatial attentions in parallel. Therefore it better captures the discriminative feature from pathological images spatially and channel-wisely. Furthermore, by formulating the learning processing in an adversarial learning manner, it also improves the subjective perception quality of the reconstructed HR image. Experiments on PathImgSR demonstrate that MASRGAN outperforms popular CNN-based and GAN-based SR methods in both quantitative metrics and visual subjective perception.
