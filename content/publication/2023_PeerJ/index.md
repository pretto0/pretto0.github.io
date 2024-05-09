---
title: 'A super-resolution network using channel attention retention for pathology images'

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Feiyang Jia
- Li Tan
- Ge Wang
- Caiyan Jia
- Zhineng Chen



# Author notes (optional)

author_notes:
  - 
  - 'Corresponding author'
  -
  -
  - 

date: '2023-01-17T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *Peer-reviewed Open Access journal (Peerj) 2023*
publication_short: In *Peer-reviewed Open Access journal (Peerj) 2023*

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

url_pdf: 'https://peerj.com/articles/cs-1196/'
url_code: 'https://github.com/MoyangSensei/CARN-Pytorch'
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

Image super-resolution (SR) significantly improves the quality of low-resolution images, and is widely used for image reconstruction in various fields. Although the existing SR methods have achieved distinguished results in objective metrics, most methods focus on real-world images and employ large and complex network structures, which are inefficient for medical diagnosis scenarios. To address the aforementioned issues, the distinction between pathology images and real-world images was investigated, and an SR Network with a wider and deeper attention module called Channel Attention Retention is proposed to obtain SR images with enhanced high-frequency features. This network captures contextual information within and across blocks via residual skips and balances the performance and efficiency by controlling the number of blocks. Meanwhile, a new linear loss was introduced to optimize the network. To evaluate the work and compare multiple SR works, a benchmark dataset bcSR was created, which forces a model training on wider and more critical regions. The results show that the proposed model outperforms state-of-the-art methods in both performance and efficiency, and the newly created dataset significantly improves the reconstruction quality of all compared models. Moreover, image classification experiments demonstrate that the suggested network improves the performance of downstream tasks in medical diagnosis scenarios. The proposed network and dataset provide effective priors for the SR task of pathology images, which significantly improves the diagnosis of relevant medical staff. The source code and the dataset are available on https://github.com/MoyangSensei/CARN-Pytorch.