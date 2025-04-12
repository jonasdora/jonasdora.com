---
title: Multiple Imputation in EMA research - A practical introduction for applied researchers

event: Annual meeting of the Society for Ambulatory Assessment
event_url: https://saa2025.com/

location: University of Leuven
address:
  street: Sint-Michielsstraat 6
  city: Leuven
  region: Flemish Region
  postcode: '3000'
  country: Belgium

summary: My talk for the 2025 SAA conference.
abstract: 'Ecological Momentary Assessment (EMA) studies frequently encounter missing data due to participant non-response, technical issues, or study design. Ignoring missing data or using simple deletion methods can introduce substantial bias, distort parameter estimates, and lead to incorrect statistical inferences - particularly in intensive longitudinal data where missingness patterns may be systematic. While modern missing data techniques offer solutions, many applied researchers lack practical guidance on implementing multiple imputation (MI). Drawing from both successful and failed MI implementations in our labs EMA datasets, I demonstrate the implementation of MI using the R package mice. I provide step-by-step guidance on (1) evaluating missing data patterns in intensive longitudinal data, (2) setting up appropriate imputation models that account for the nested structure of EMA data, (3) checking model convergence and imputation quality through diagnostic procedures, and (4) conducting both Bayesian and frequentist analyses using multiply imputed datasets. Using concrete examples, I illustrate how different analytical choices in the MI process affect research outcomes. I demonstrate common pitfalls, practical solutions, and decision points researchers face when implementing MI in EMA studies. Special attention is given to handling within-person dependencies and between-person differences in missing data patterns.This presentation provides applied researchers with accessible strategies for implementing MI in EMA research, informed by both successes and failures. Focussing on practical application, it should enable researchers to make informed decisions about handling missing data in their own studies. Our approach emphasizes both statistical rigor and real-world applicability in psychological research contexts.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-05-25'
#date_end: '2025-06-25'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2025-04-10'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: SAA'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://osf.io/xjg24/files/osfstorage'
url_pdf: ''
url_slides: 'uploads/SAA_Dora_imputation.html'
url_video: 'https://youtu.be/_IhcJP7Zrb4'

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
