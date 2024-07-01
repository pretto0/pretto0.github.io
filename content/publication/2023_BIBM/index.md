---
title: "[BIBM'23]Self-distillation Augmented Masked Autoencoders for Histopathological Image Understanding"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Yang Luo
- Zhineng Chen
- Shengtian Zhou
- Kai Hu
- Xieping Gao


# Author notes (optional)

author_notes:
  - 
  - 'Corresponding author'

date: '2023-12-05T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *IEEE International Conference on Bioinformatics and Biomedicine (BIBM) 2023*
publication_short: In *IEEE International Conference on Bioinformatics and Biomedicine (BIBM) 2023*

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

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10385986'
url_code: 'https://github.com/irsLu/SD-MAE/'
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
Recently, regression-based methods, which predict parameterized text shapes for text localization, have gained popularity in scene text detection. However, the existing parameterized text shape methods still have limitations in modeling arbitrary-shaped texts due to ignoring the utilization of text-specific shape information. Moreover, the time consumption of the entire pipeline has been largely overlooked, leading to a suboptimal overall inference speed. To address these issues, we first propose a novel parameterized text shape method based on low-rank approximation. Unlike other shape representation methods that employ data-irrelevant parameterization, our approach utilizes singular value decomposition and reconstructs the text shape using a few eigenvectors learned from labeled text contours. By exploring the shape correlation among different text contours, our method achieves consistency, compactness, simplicity, and robustness in shape representation. Next, we propose a dual assignment scheme for speed acceleration. It adopts a sparse assignment branch to accelerate the inference speed, and meanwhile, provides ample supervised signals for training through a dense assignment branch. Building upon these designs, we implement an accurate and efficient arbitrary-shaped text detector named LRANet. Extensive experiments are conducted on several challenging benchmarks, demonstrating the superior accuracy and efficiency of LRANet compared to state-of-the-art methods. Code is available at: https://github.com/ychensu/LRANet.git
