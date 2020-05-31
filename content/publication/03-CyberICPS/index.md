---
authors:
- E. G. Chekole
- J. H. Castellanos
- M. Ochoa 
- D. K. Y. Yau
title: "Enforcing Memory Safety in Cyber-Physical Systems"
date: "2017-09-11"
doi: "https://doi.org/10.1007/978-3-319-72817-9_9"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-09-11"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the ESORICS workshop on Security of Industrial Control Systems and Cyber-Physical Systems (CyberICPS), Springer*"
publication_short: "*Proceedings of the ESORICS workshop on Security of Industrial Control Systems and Cyber-Physical Systems (CyberICPS), Springer*"

abstract: Cyber-Physical Systems (CPS) integrate computations and communications with physical processes and are being widely adopted in various application areas. However, the increasing prevalence of cyber attacks targeting them poses a growing security concern. In particular, attacks exploiting memory-safety vulnerabilities constitute a major attack vector against CPS, because embedded systems often rely on unsafe but fast programming languages to meet their hard time constraints. A wide range of countermeasures has been developed to provide protection against these attacks. However, the most reliable countermeasures incur in high runtime overheads. In this work, we explore the applicability of strong countermeasures against memory-safety attacks in the context of realistic Industrial Control Systems (ICS). To this end, we design an experimental setup, based on a secure water treatment plant (SWaT) to empirically measure the memory safety overhead (MSO) caused by memory-safe compilation of the Programmable Logic Controller (PLC). We then quantify the tolerability of this overhead in terms of the expected real-time constraints of SWaT. Our results show high effectiveness of the security measure in detecting memory-safety violations and a MSO (197.86µs per scan-cycle) that is also tolerable for the SWaT simulation. We also discuss how different parameters impact the execution time of PLCs and the resulting absolute MSO.

# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: false

# links:
# - name: Custom Link
#  url: http://example.org
url_pdf: https://link.springer.com/chapter/10.1007/978-3-319-72817-9_9
#url_pdf: pdf/icss-final.pdf
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
projects:
- internal-project

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

