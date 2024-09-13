---
title: Finding Molecular Minima and Transition States with Reverse Diffusion

event: STC 2024
event_url: https://stc2024.de/

location: Braunschweig
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

# summary: An example talk using Hugo Blox Builder's Markdown slides feature.
abstract: 'Molecular relaxation and transition state finding are essential components of
computational chemistry to understand reactivity. Focussing on the former, neural
network force field models require large labeled datasets encompassing both
equilibrium and non-equilibrium structures. As a remedy, we propose MoreRed [1],
molecular relaxation by reverse diffusion where non-equilibrium structures are treated
as “noisy” instances of their corresponding equilibrium states. We extend this framework
to also denoise structures to generate transition states. Notably, MoreRed learns a
simpler pseudo potential energy surface instead of the complex physical potential
energy surface, thereby requiring much less and unlabelled data. We compare
MoreRed to classical force fields, equivariant neural network force fields trained on a
large dataset of equilibrium and non-equilibrium data, as well as a semi-empirical
tight-binding model. Lastly we show the potential for elucidating chemical reaction
networks by chaining a relaxation and a transition state model.'

# # Talk start and end times.
# #   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-09-03'
# date_end: '2030-06-01T15:00:00Z'
all_day: true

# # Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: Stefan Gugler'
  focal_point: Right

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
# projects:
#   - example
---
<!-- 
{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
