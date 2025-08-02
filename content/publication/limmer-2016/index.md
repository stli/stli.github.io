---
title: Towards optimal nonlinearities for sparse recovery using higher-order statistics
authors:
- Steffen Limmer
- Slawomir Stanczak
date: '2016-01-01'
publishDate: '2025-08-02T10:57:54.749867Z'
publication_types:
- paper-conference
publication: '*2016 IEEE 26th International Workshop on Machine Learning for Signal
  Processing (MLSP)*'

publication_short: In *MLSP 2016*

# Summary. An optional shortened abstract.
summary: This paper explores machine learning techniques to develop low-latency approximate solutions for inverse problems, specifically focusing on recovering sparse stochastic signals within lp​-balls using a probabilistic approach. It analyzes the Bayesian mean-square-error (MSE) for two estimators: a linear one, and a structured nonlinear one comprising a linear operator followed by a Cartesian product of univariate nonlinear mappings. The proposed nonlinear estimator maintains comparable complexity to its linear counterpart, as the nonlinear mapping can be efficiently implemented via look-up tables (LUTs), making it suitable for hardware implementation and directly applicable to neural networks or single-iterate shrinkage/thresholding algorithms under latency constraints. An alternating minimization technique is employed to optimize these operators and mappings, achieving MSE convergence, which is particularly beneficial for real-time applications where traditional iterative and convex optimization methods are impractical.

tags:
  - Sparse Signal Processing
  - AI4Science

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
