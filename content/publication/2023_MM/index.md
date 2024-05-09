---
title: '3DStyle-Diffusion: Pursuing Fine-grained Text-driven 3D Stylization with 2D Diffusion Models'

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Haibo Yang
- Yang Chen
- Yingwei Pan
- Ting Yao
- Zhineng Chen
- Tao Mei


# Author notes (optional)

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  -
  -
  - 'Corresponding author'

date: '2023-10-27T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *ACM International Conference on Multimedia (MM) 2023*
publication_short: In *ACM International Conference on Multimedia (MM) 2023*

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

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3581783.3612363'
url_code: 'https://github.com/yanghb22-fdu/3DStyle-Diffusion-Official'
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
3D content creation via text-driven stylization has played a fundamental challenge to multimedia and graphics community. Recent advances of cross-modal foundation models (e.g., CLIP) have made this problem feasible. Those approaches commonly leverage CLIP to align the holistic semantics of stylized mesh with the given text prompt. Nevertheless, it is not trivial to enable more controllable stylization of fine-grained details in 3D meshes solely based on such semantic-level cross-modal supervision. In this work, we propose a new 3DStyle-Diffusion model that triggers fine-grained stylization of 3D meshes with additional controllable appearance and geometric guidance from 2D Diffusion models. Technically, 3DStyle-Diffusion first parameterizes the texture of 3D mesh into reflectance properties and scene lighting using implicit MLP networks. Meanwhile, an accurate depth map of each sampled view is achieved conditioned on 3D mesh. Then, 3DStyle-Diffusion leverages a pre-trained controllable 2D Diffusion model to guide the learning of rendered images, encouraging the synthesized image of each view semantically aligned with text prompt and geometrically consistent with depth map. This way elegantly integrates both image rendering via implicit MLP networks and diffusion process of image synthesis in an end-to-end fashion, enabling a high-quality fine-grained stylization of 3D meshes. We also build a new dataset derived from Objaverse and the evaluation protocol for this task. Through both qualitative and quantitative experiments, we validate the capability of our 3DStyle-Diffusion. Source code and data are available at https://github.com/yanghb22-fdu/3DStyle-Diffusion-Official.