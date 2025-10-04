---
title: "Distributed adaptive fixed-time formation tracking for heterogeneous multi-agent systems"
authors:
- admin
- Dong Sun
- Gang Feng
date: "2025-08-26T00:00:00Z"
doi: "https://doi.org/10.1016/j.automatica.2025.112632"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-8-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "**Automatica**"
publication_short: ""

abstract: This article investigates the problem of fixed-time time-varying formation tracking control for heterogeneous linear multiagent systems under the directed communication graph. It is assumed that the Laplacian matrix associated with the communication graph is unavailable and that the system matrices of the leader are only available to its neighboring followers. This differs from many existing works on fixed-time formation tracking control problems where the communication graphs are typically undirected and protocol designs often rely on certain global information. A novel distributed observer is first put forward to estimate both the state and system matrices of the leader in fixed time. Then, an adaptive scheme is developed to solve the time-varying regulator equations resulting from the estimated leader system matrices in fixed time. Based on the proposed observer and the adaptive solutions to the regulator equations, a distributed adaptive fixed-time formation tracking control protocol is further proposed via coordinate transformation techniques. It is shown that our proposed controllers do not require the input matrices of the followers to be of full row rank. It is also shown that the concerned fixed-time formation tracking control problem can be solved with the proposed fixed-time formation tracking control strategy in a distributed manner. Our results can be directly applied to solve both the adaptive fixed-time cooperative output regulation problem and the leader-following consensus problems of multiagent systems under the directed graph. Finally, the effectiveness of the proposed fixed-time formation tracking control strategy is demonstrated through a numerical example.

# Summary. An optional shortened abstract.
summary: This article was published as a brief paper in ***Automatica***. In this article, the fixed-time time-varying formation tracking control problem is addressed for heterogeneous linear multiagent systems under the directed communication graph. It is assumed that the Laplacian matrix associated with the communication graph is unavailable and that the system matrices of the leader are only available to its neighboring followers.

tags:
- Fixed-time control
featured: true 

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'content/publication/2025_Auto/2025_Auto.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Output trajectories of the multiagent systems'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
