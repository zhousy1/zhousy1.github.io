---
title: "Neural network-accelerated trajectory optimization for launch vehicle landing"
authors:
- Zhipeng Shen
- admin
- Jianglong Yu
- Hailong Huang

date: "2023-06-16T00:00:00Z"
doi: "https://ieeexplore.ieee.org/abstract/document/10245228"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-20"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "**The 9th International Conference on Control Science and Systems Engineering (ICCSSE)**"
publication_short: ""

abstract: This paper presents a novel trajectory optimization method for the 6-degrees-of-freedom powered landing problem in aerospace guidance and control. The method combines machine learning and convex optimization to achieve real-time performance. Specifically, we formulate the powered landing problem as an optimal control problem and transform it into a convex optimization problem. To enhance the state-of-the-art sequential convex programming algorithm, we use a deep neural network as an initial trajectory generator to provide a satisfactory initial guess for the sequential convex programming algorithm. Simulation results show that the proposed method achieves precise guidance of the vehicle to the landing site. Monte Carlo tests demonstrate that it can save an average of 40.8% of the computation time compared to the sequential convex programming method. Therefore, the proposed scheme is suitable for real-time applications in the aerospace industry.

# Summary. An optional shortened abstract.
summary: 

tags:
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'content/publication/2023_ICCSSE/2023_ICCSSE.pdf'
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
  caption: ''
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
