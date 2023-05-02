---
title: "DeepRHP: A Hybrid Variational Autoencoder for Designing Random Heteropolymers as Protein Mimics"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Shuni Li
- Zhiyuan Ruan
- Andy Shen
- Ivan Jayapurna
- Ting Xu
- Haiyan Huang


# Author notes (optional)
#author_notes:


date: "2023-02-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *AAAI Workshop on AI to Accelerate Science and Engineering (AI2ASE)*
publication_short: ""

abstract: Synthetic random heteropolymers (RHPs), consisting of a predefined set of monomers, offer an approach toward the design of protein-like materials. These RHPs, if designed appropriately, can mimic protein behavior and function. As such, there is a need for computational tools to efficiently guide RHP design. We bridge this gap by developing DeepRHP, a modified variational autoencoder (VAE) model under a semi-supervised framework. By equipping a classical VAE with an additional feature-based VAE, DeepRHP forces the latent space to capture structures of critical chemical features as well as individual RHP sequence patterns. In this sense, our method is versatile by allowing any relevant features to be incorporated in a hybrid manner. We demonstrate the effectiveness of DeepRHP by suggesting potential monomer compositions that stabilize membrane proteins (e.g. Aquaporin Z) in non-native environments and cross-validating our prediction with published results. The concordance between our model and true RHP function suggests strong potential in utilizing hybrid autoencoder architectures to guide RHP design for proteins and other biological compounds.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ai-2-ase.github.io/papers/'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
