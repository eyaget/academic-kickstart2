---
authors:
- Eyasu Getahun Chekole
- Jianying Zhou
title: "MFAA: Historical Hash Based Multi-Factor Authentication and Authorization in IIoT"
date: "2024-12-09"
doi: "https://doi.org/10.1109/ACSACW65225.2024.00021"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-10"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In ***Proceedings of the 10th Annual Industrial Control System Security Workshop (ICSS'24), co-located with ACSAC'24***, IEEE"
publication: "In ***Proceedings of the 10th Annual Industrial Control System Security Workshop (ICSS'24), co-located with ACSAC'24***, IEEE"

abstract: "Industrial Internet of Things (IIoT) has been widely adopted in various critical infrastructures. However, machine-to-machine (M2M) communication in IIoT is particularly vulnerable to a wide range of authentication and authorization attacks. Although a variety of end-to-end security protocols can be used to secure the communication channels, establishing such a secure channel (i.e., securely generating and exchanging the session key) is still challenging due to various reasons. The single-factor based Authenticated Key Exchange (AKE) schemes are no longer sufficient to provide adequate security in IIoT. Most password, smart card and biometric based multi-factor AKE (MAKE) schemes are not also applicable in M2M communication as they require human involvement. Recently, historical data based multi-factor AKE (HMAKE) schemes have appeared to be promising to achieve AKE in IIoT. However, the state-of-the-art HMAKE schemes do not still sufficiently address the various security and performance requirements in IIoT. Furthermore, advanced session hijacking attacks also pose additional security concerns as they hijack already established sessions and get unauthorized access to resources. In this work, we propose MFAA – a lightweight HMAKE scheme that effectively addresses most of the AKE-related authentication issues and session hijacking-based unauthorized accesses in IIoT. In MFAA, we systematically refine and intertwine historical hashes to produce a highly leakage-resilient second authentication factor for AKE and an authorization token (against session hijacking attacks) with a negligible performance overhead. In general, the proposed scheme has the following key features: 1) provides mutually authenticated two-factor security; 2) highly leakage-resistant even under the assumption of a strong adversary; 3) properly achieves perfect forward secrecy; 4) resilient against session hijacking attacks; 5) very lightweight and practical even for resource-constrained IIoT devices. Overall, the proposed scheme is highly effective both in terms of security guarantee and efficiency."

# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: false

links:
 #- name: Preprint
   #url: "https://www.techrxiv.org/articles/preprint/EARIC_Exploiting_ADC_Registers_in_IoT_and_Control_Systems/21215588"
 #- name: Publication Site
   #url: "https://www.sciencedirect.com/science/article/abs/pii/S1874548221000238"
#url_pdf: https://www.sciencedirect.com/science/article/pii/S0167404820301061
#url_pdf: pdf/VulnGen.pdf
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
