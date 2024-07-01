---
title: "[ICASSP'22]Genre-Conditioned Long-Term 3D Dance Generation Driven by Music"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Yuhang Huang
- Junjie Zhang
- Shuyan Liu
- Qian Bao
- Dan Zeng
- Zhineng Chen
- YWu Liu


# Author notes (optional)

author_notes:
  - 
  - 
  - 
  - 'Corresponding author'
  - 'Corresponding author'
  - 

date: '2022-05-23T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2022*
publication_short: In *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2022*

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

url_pdf: 'https://arxiv.org/abs/2205.00159'
url_code: 'https://github.com/PaddlePaddle/PaddleOCR'
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
Dancing to music is an artistic behavior of humans, however, letting machines generate dances from music is still challenging. Most existing works have been made progress in tackling the problem of motion prediction conditioned by music, yet they rarely consider the importance of the musical genre. In this paper, we focus on generating long-term 3D dance from music with a specific genre. Specifically, we construct a pure transformer-based architecture to correlate motion features and music features. To utilize the genre information, we propose to embed the genre categories into the transformer decoder so that it can guide every frame. Moreover, different from previous inference schemes, we introduce the motion queries to output the dance sequence in parallel that significantly improves the efficiency. Extensive experiments on AIST++[1] dataset show that our model outperforms state-of-the-art methods with a much faster inference speed.
