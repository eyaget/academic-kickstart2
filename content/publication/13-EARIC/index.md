---
authors:
- Eyasu Getahun Chekole
- Rajaram Thulasiraman
- Jianying Zhou
title: "EARIC: Exploiting ADC Registers in IoT and Control Systems"
date: "2022-10-06"
#doi: "10.1016/j.ijcip.2021.100431"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-06"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "In ***TechRxiv***"
publication_short: "In ***TechRxiv***"
#publication: "*International Journal of Critical Infrastructure Protection (IJCIP)*, Elsevier, In Press"
#publication_short: "IJCIP"

abstract: "An analog-to-digital converter (ADC) is a critical part of most computing systems that converts analog signals into quantifiable digital values. Since most digital devices operate only on digital values, the ADC acts as an interface between the digital and analog worlds. As such, ADCs are commonly used in a wide-range of applications, including internet of things (IoT), industrial control systems (ICS), cyber-physical systems (CPS), audio/video devices, medical imaging, digital oscilloscopes, and cell phones, among others. For example, programmable logic controllers (PLCs) in ICS/CPS often make control decisions based on digital values converted from analog signals by ADCs Due to its crucial role in various applications, ADCs are often targeted by a wide-range of physical and cyber attacks. Attackers often exploit vulnerabilities that could be found in the software/hardware of ADCs. In this work, we first conduct a deeper study in the ADC conversion logic to investigate relevant vulnerabilities that were not well explored by prior works. As a result, we manage to identify exploitable vulnerabilities on certain ADC registers that are involved in the analog-to-digital conversion logic. As a proof of concept, we construct and develop three attack techniques by exploiting the vulnerabilities identified. Finally, we test the attacks on a mini-CPS testbed we designed using IoT devices, analog sensors and actuators. Our experimental results reveal high effectiveness of the proposed attack techniques in misleading PLCs to make incorrect control decisions in CPS. We also analyze the impact of such attacks when launched in real-word CPS testbeds."

# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: false

links:
 - name: Preprint
   url: "https://www.techrxiv.org/articles/preprint/EARIC_Exploiting_ADC_Registers_in_IoT_and_Control_Systems/21215588"
 #- name: Publication Site
   #url: "https://www.sciencedirect.com/science/article/abs/pii/S1874548221000238"
#url_pdf: https://www.sciencedirect.com/science/article/pii/S0167404820301061
url_pdf: pdf/EARIC.pdf
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
