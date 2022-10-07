---
title: 'Doubly Stochastic Variational Inference for Neural Processes with Hierarchical Latent Variables'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Herke van Hoof

# Author notes (optional)
author_notes:
  - 'Correspondence Author'
  # - 'Equal contribution'

date: '2020-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-10-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning*
publication_short: In *ICML2020*

abstract: Neural processes (NPs) constitute a family of variational approximate models for stochastic processes with promising properties in computational
efficiency and uncertainty quantification. These processes use neural networks with latent variable inputs to induce predictive distributions. However, the expressiveness of vanilla NPs is limited as they only use a global latent variable, while targetspecific local variation may be crucial sometimes. To address this challenge, we investigate NPs systematically and present a new variant of NP model that we call Doubly Stochastic Variational Neural Process (DSVNP). This model combines the global latent variable and local latent variables for prediction. We evaluate this model in several experiments, and our results demonstrate competitive prediction performance in multi-output regression and uncertainty estimation in classification.


# Summary. An optional shortened abstract.
summary: 'A hierarchical neural process was developed in this paper.'

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2008.09469.pdf' 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://icml.cc/media/Slides/icml/2020/virtual(no-parent)-15-19-00UTC-6122-doubly_stochast.pdf'
url_source: ''
url_video: 'https://crossminds.ai/video/doubly-stochastic-variational-inference-for-neural-processes-with-hierarchical-latent-variables-606f43bd072e523d7b780820/'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
