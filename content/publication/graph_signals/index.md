---
title: "Scalable M-Channel Critically Sampled Filter Banks for Graph Signals"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Shuni Li
- Yan Jin
- David Shuman


# Author notes (optional)
#author_notes:


date: "2019-06-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Signal Processing*
publication_short: ""

abstract: We investigate a scalable M-channel critically sampled filter bank for graph signals, where each of the M filters is supported on a different subband of the graph Laplacian spectrum. For analysis, the graph signal is filtered on each subband and downsampled on a corresponding set of vertices. However, the classical synthesis filters are replaced with interpolation operators. For small graphs, we use a full eigendecomposition of the graph Laplacian to partition the graph vertices such that the m th set comprises a uniqueness set for signals supported on the m th subband. The resulting transform is critically sampled, the dictionary atoms are orthogonal to those supported on different bands, and graph signals are perfectly reconstructable from their analysis coefficients. We also investigate fast versions of the proposed transform that scale efficiently for large, sparse graphs. Issues that arise in this context include designing the filter bank to be more amenable to polynomial approximation, estimating the number of samples required for each band, performing nonuniform random sampling for the filtered signals on each band, and using efficient reconstruction methods. We empirically explore the joint vertex-frequency localization of the dictionary atoms, the sparsity of the analysis coefficients for different classes of signals, the reconstruction error resulting from the numerical approximations, and the ability of the proposed transform to compress piecewise-smooth graph signals. The proposed filter bank also yields a fast, approximate graph Fourier transform with a coarse resolution in the spectral domain.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/8736850'
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
