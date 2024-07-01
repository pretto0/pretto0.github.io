---
title: "[ICASSP'23]Multi-Object Localization and Irrelevant-Semantic Separation for Nuclei Segmentation in Histopathology Images"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Ya Tang
- Xiongjun Ye
- Xuanya Li
- Zhineng Chen

# Author notes (optional)

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 
  - 'Corresponding author'

date: '2023-06-04T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2023*
publication_short: In *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2023*

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

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10096902'
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

Automated segmentation of nuclei in histopathology images is critical for cancer diagnosis and prognosis. Due to the high variability of nuclei morphology, numerous nuclei overlapping, and the wide existence of nuclei clusters, this task still remains challenging. In this paper, we propose an effective nuclei segmentation method for histopathology images based on a novel neural network for multi-object localization and irrelevant-semantic separation (MI-Net), which includes a multi-object localization module (MOLM), a deep boundary awareness module (DBAM), and an irrelevant semantic separation module (ISSM). Specifically, the MOLM is used to calibrate features to capture more comprehensive information about the location of nuclei. It alleviates the problem of cell adhesion in histopathology images. The DBAM is intended to extract boundary information and solve the blurred boundary problem effectively. The ISSM is used to separate foreground features from background features and effectively address the problem of complex backgrounds in histopathology images. It also solves the low contrast problem between the target objects and the background. We evaluate MI-Net on the famous MoNuSeg dataset and compare it with ten state-of-the-art methods. MI-Net surpasses the best-performed method by margins from 1.12% to 2.29% over standard evaluation metrics, showing its effectiveness on nuclei segmentation.
