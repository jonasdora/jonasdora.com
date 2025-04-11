---
title: Multiple Imputation in EMA research - A practical introduction for applied researchers

event: Annual meeting of the Society for Ambulatory Assessment
event_url: https://saa2025.com/

#location: Hugo Blox Builder HQ
#address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: My talk for the 2025 SAA conference.
abstract: 'Ecological Momentary Assessment (EMA) studies frequently encounter missing data due to participant non-response, technical issues, or study design. Ignoring missing data or using simple deletion methods can introduce substantial bias, distort parameter estimates, and lead to incorrect statistical inferences - particularly in intensive longitudinal data where missingness patterns may be systematic. While modern missing data techniques offer solutions, many applied researchers lack practical guidance on implementing multiple imputation (MI). Drawing from both successful and failed MI implementations in our labs EMA datasets, I demonstrate the implementation of MI using the R package mice. I provide step-by-step guidance on (1) evaluating missing data patterns in intensive longitudinal data, (2) setting up appropriate imputation models that account for the nested structure of EMA data, (3) checking model convergence and imputation quality through diagnostic procedures, and (4) conducting both Bayesian and frequentist analyses using multiply imputed datasets. Using concrete examples, I illustrate how different analytical choices in the MI process affect research outcomes. I demonstrate common pitfalls, practical solutions, and decision points researchers face when implementing MI in EMA studies. Special attention is given to handling within-person dependencies and between-person differences in missing data patterns.This presentation provides applied researchers with accessible strategies for implementing MI in EMA research, informed by both successes and failures. Focussing on practical application, it should enable researchers to make informed decisions about handling missing data in their own studies. Our approach emphasizes both statistical rigor and real-world applicability in psychological research contexts.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-06-25'
date_end: '2025-06-25'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2025-06-25'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://osf.io/xjg24/files/osfstorage'
url_pdf: ''
url_slides: 'https://osf.io/xjg24/files/osfstorage'
url_video: 'https://osf.io/xjg24/files/osfstorage'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example

---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
