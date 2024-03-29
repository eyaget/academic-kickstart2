---
authors:
- Eyasu Getahun Chekole
- Martin Ochoa
- Sudipta Chattopadhyay
title: "SCOPE: Secure Compiling of PLCs in Cyber-Physical Systems"
date: "2021-03-08"
doi: "10.1016/j.ijcip.2021.100431"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-08"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
# publication: "In *CoRR abs, arXiv*"
# publication_short: "In *CoRR abs, arXiv*"
publication: "In ***International Journal of Critical Infrastructure Protection (IJCIP)***, Elsevier"
#publication_short: "IJCIP"

abstract: "Cyber-Physical Systems (CPS) are being widely adopted in critical infrastructures, such as smart grids, nuclear plants, water systems, transportation systems, manufacturing and healthcare services, among others. However, the increasing prevalence of cyberattacks targeting them raises a growing security concern in the domain. In particular, memory-safety attacks, that exploit memory-safety vulnerabilities, constitute a major attack vector against real-time control devices in CPS. Traditional IT countermeasures against such attacks have limitations when applied to the CPS context: they typically incur in high runtime overheads; which conflicts with real-time constraints in CPS and they often abort the program when an attack is detected, thus harming availability of the system, which in turn can potentially result in damage to the physical world. In this work, we propose to enforce a full-stack memory-safety (covering user-space and kernel-space attack surfaces) based on secure compiling of PLCs to detect memory-safety attacks in CPS. Furthermore, to ensure availability, we enforce a resilient mitigation technique that bypasses illegal memory access instructions at runtime by dynamically instrumenting low-level code. We empirically measure the computational overhead caused by our approach on two experimental settings based on real CPS. The experimental results show that our approach effectively and efficiently detects and mitigates memory-safety attacks in realistic CPS."

# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: false

links:
 #- name: Preprint
 #  url: "https://arxiv.org/abs/2012.12529"
 #- name: Publication Site
 #  url: "https://www.sciencedirect.com/science/article/abs/pii/S1874548221000238"
#url_pdf: https://www.sciencedirect.com/science/article/pii/S0167404820301061
url_pdf: pdf/IJCIP2021-Postprint.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}
