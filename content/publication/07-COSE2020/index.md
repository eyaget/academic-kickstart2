---
authors:
- E. G. Chekole
- S. Chattopadhyay
- M. Ochoa
- H. Guo
- U. Cheramangalath
title: "CIMA: Compiler-Enforced Resilience Against Memory Safety Attacks in Cyber-Physical Systems"
date: "2020-04-13"
doi: "https://doi.org/10.1016/j.cose.2020.101832"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-13"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computers & Security journal, Elsevier*"
publication_short: "*Computers & Security journal, Elsevier*"

abstract: Memory-safety attacks have been one of the most critical threats against computing systems. Although a wide-range of defense techniques have been developed against these attacks, the existing mitigation strategies have several limitations. In particular, most of the existing mitigation approaches are based on aborting or restarting the victim program when a memory-safety attack is detected, thus making the system unavailable. This might not be acceptable in systems with stringent timing constraints, such as cyber-physical systems (CPS), since the system unavailability leaves the control system in an unsafe state. To address this problem, we propose CIMA -- a resilient mitigation technique that prevents invalid memory accesses at runtime. CIMA manipulates the compiler-generated control-flow graph to automatically detect and bypass unsafe memory accesses at runtime, thereby mitigating memory-safety attacks along the process. An appealing feature of CIMA is that it significantly improves system availability and resilience of the CPS even under the presence of memory-safety attacks. To this end, we design our experimental setup based on a realistic Secure Water Treatment (SWaT) and Secure Urban Transportation System (SecUTS) testbeds and evaluate the effectiveness and the efficiency of our approach. The experimental results reveal that CIMA handles memory-safety attacks effectively while meeting the real-time constraints and physical-state resiliency of the CPS under test. Using CIMA, we have also discovered a memory-safety vulnerability in the firmware of programmable logic controllers and a CVE ID has already been assigned for it. 

# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: false

links:
 - name: Publication Site
   url: https://www.sciencedirect.com/science/article/pii/S0167404820301061
 - name: CVE-2018-20818
   url: https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-20818
#url_pdf: https://www.sciencedirect.com/science/article/pii/S0167404820301061
url_pdf: pdf/COSE2020-PostPrint.pdf
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
