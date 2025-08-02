---
title: A neural architecture for Bayesian compressive sensing over the simplex via
  Laplace techniques
authors:
- Steffen Limmer
- Slawomir Stanczak
date: '2018-10-02'
publishDate: '2025-08-02T10:57:54.733866Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Signal Processing*'

# Summary. An optional shortened abstract.
abstract: This paper introduces a novel theoretical and conceptual framework for designing neural architectures specifically for Bayesian compressive sensing of simplex-constrained sparse stochastic vectors. The core idea involves reframing the MMSE estimation problem as computing the centroid of a polytope, which is the intersection of a simplex and an affine subspace defined by compressive measurements. Leveraging multidimensional Laplace techniques, the authors derive a closed-form solution for this centroid computation and demonstrate how to directly map this solution to a neural network architecture composed of threshold, ReLU, and rectified polynomial activation functions. This unique construction results in an architecture where the number of layers equals the number of measurements, offering faster solutions in low-measurement scenarios and exhibiting robustness to small model mismatches. Simulations further indicate that this proposed architecture achieves superior approximations with fewer parameters compared to standard ReLU networks in supervised learning contexts.

summary: This paper introduces a novel theoretical and conceptual framework for designing neural architectures specifically for Bayesian compressive sensing of simplex-constrained sparse stochastic vectors. The core idea involves reframing the MMSE estimation problem as computing the centroid of a polytope, which is the intersection of a simplex and an affine subspace defined by compressive measurements. Leveraging multidimensional Laplace techniques, the authors derive a closed-form solution for this centroid computation and demonstrate how to directly map this solution to a neural network architecture composed of threshold, ReLU, and rectified polynomial activation functions. This unique construction results in an architecture where the number of layers equals the number of measurements, offering faster solutions in low-measurement scenarios and exhibiting robustness to small model mismatches. Simulations further indicate that this proposed architecture achieves superior approximations with fewer parameters compared to standard ReLU networks in supervised learning contexts.

tags:
  - Sparse Signal Processing
  # - AI4Science

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/1709.01112'
url_code: 'https://github.com/stli/CentNet'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/stli/2023_pinn'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Sparse Signal Processing
  - AI4Science

---
