---
title: Neural networks for integral equations and engineering applications @ The Alan Turing Institute

event: Physics-informed machine learning meets engineering seminar series
event_url: https://www.turing.ac.uk/events/phi-ml-meets-engineering-neural-networks-integral-equations-and-engineering-applications

# location: Hugo Blox Builder HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

abstract: In this talk, we will explore different approaches that leverage neural networks for solving integral equations that appear in engineering applications. First, we introduce a physics-informed neural network for the problem of calculating line integrals in pathloss prediction. The method provides physically consistent pathloss estimates, while offering fast inference times and automatic differentiation useful for downstream tasks such as localization and network planning. Second, we introduce an approach to decompose neural networks into lower-dimensional models using the ANOVA decomposition. This Neural-ANOVA decomposition builds on closed-form integration over subspaces and enables an analysis of all learned interaction effects. Lastly, we discuss the application of Laplace techniques for designing neural networks to solve integrals over a particular class of polytopes that are given as the intersection of the simplex and an affine subspace. We show that classical deep neural networks with specialized activation functions can be designed to solve this problem in closed-form without training. These approaches collectively demonstrate the potential of neural networks for integral equations and advancing engineering applications through tailored network architectures and training methods.

summary: In this talk, we will explore different approaches that leverage neural networks for solving integral equations that appear in engineering applications. First, we introduce a physics-informed neural network for the problem of calculating line integrals in pathloss prediction. The method provides physically consistent pathloss estimates, while offering fast inference times and automatic differentiation useful for downstream tasks such as localization and network planning. Second, we introduce an approach to decompose neural networks into lower-dimensional models using the ANOVA decomposition. This Neural-ANOVA decomposition builds on closed-form integration over subspaces and enables an analysis of all learned interaction effects. Lastly, we discuss the application of Laplace techniques for designing neural networks to solve integrals over a particular class of polytopes that are given as the intersection of the simplex and an affine subspace. We show that classical deep neural networks with specialized activation functions can be designed to solve this problem in closed-form without training. These approaches collectively demonstrate the potential of neural networks for integral equations and advancing engineering applications through tailored network architectures and training methods.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-09-05'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: ''
  preview_only: false

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: ''
# url_slides: 'https://slideshare.net'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - Physical AI
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
