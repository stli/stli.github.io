---
title: Towards optimal nonlinearities for sparse recovery using higher-order statistics
authors:
- Steffen Limmer
- Slawomir Stanczak
date: '2016-09-05'
publishDate: '2025-08-02T10:57:54.749867Z'
publication_types:
- paper-conference
publication: '*2016 IEEE 26th International Workshop on Machine Learning for Signal
  Processing (MLSP)*'

# Summary. An optional shortened abstract.
abstract: This paper investigates machine learning techniques to achieve low-latency approximate solutions for inverse problems, specifically focusing on recovering sparse stochastic signals within lp​-balls using a probabilistic framework. The authors analyze the Bayesian mean-square-error (MSE) for two estimators. a linear one, and a structured nonlinear one comprising a linear operator followed by a Cartesian product of univariate nonlinear mappings. Crucially, the proposed nonlinear estimator maintains comparable complexity to its linear counterpart due to the efficient hardware implementation of the nonlinear mapping via look-up tables (LUTs). This structure is well-suited for neural networks and single-iterate shrinkage/thresholding algorithms, and an alternating minimization technique yields optimized operators and mappings that converge in MSE, making it highly appealing for real-time applications where traditional iterative optimization is infeasible.

summary: This paper investigates machine learning techniques to achieve low-latency approximate solutions for inverse problems, specifically focusing on recovering sparse stochastic signals within lp​-balls using a probabilistic framework. The authors analyze the Bayesian mean-square-error (MSE) for two estimators. a linear one, and a structured nonlinear one comprising a linear operator followed by a Cartesian product of univariate nonlinear mappings. Crucially, the proposed nonlinear estimator maintains comparable complexity to its linear counterpart due to the efficient hardware implementation of the nonlinear mapping via look-up tables (LUTs). This structure is well-suited for neural networks and single-iterate shrinkage/thresholding algorithms, and an alternating minimization technique yields optimized operators and mappings that converge in MSE, making it highly appealing for real-time applications where traditional iterative optimization is infeasible.

tags:
  - Sparse Signal Processing
  # - AI4Science

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/1605.08201'
url_code: 'https://github.com/stli/MLSP2016_OptNonlin'
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
