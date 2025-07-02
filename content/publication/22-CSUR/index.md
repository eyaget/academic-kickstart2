---
authors:
- Ang Kok Wee
- Eyasu Getahun Chekole
- Jianying Zhou
title: "Unveiling the Covert Vulnerabilities in Multi-Factor Authentication Protocols: A Systematic Review and Security Analysis"
date: "2025-05-07"
doi: "https://doi.org/10.1145/3734864"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-07"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "In ***ACM Computing Surveys*** journal, ACM"
publication_short:  "In ***ACM Computing Surveys*** journal, ACM"

abstract: "Nowadays, cyberattacks are growing at an alarming rate, causing widespread havoc to the digital community. In particular, authentication attacks have become a dominant attack vector, allowing intruders to impersonate legitimate users and maliciously access resources. Traditional single-factor authentication (SFA) protocols, which rely on such as a single authentication factor, such as passwords, PINs, pre-shared keys, and biometric identifiers, among others, are often insufficient to address the growing sophistication of modern cyberattacks. They are often bypassed by side-channel or other attack techniques, rendering them inadequate to meet current authentication requirements. To address these shortcomings, multi-factor authentication (MFA) protocols have been widely adopted in recent years, raising the security bar against impostors and restricting unauthorized accesses. MFA enhances security by incorporating multiple authentication factors, such as knowledge-based (e.g., passwords), possession-based (e.g., tokens), and inherent-based factors (e.g., biometrics), among others. However, while MFA is generally considered more secure than SFA, it is not foolproof. Because, critical vulnerabilities may still arise due to design or implementation flaws in MFA protocols. These vulnerabilities are often overlooked by designers or users and remain undetected until exploited by attackers, potentially resulting in catastrophic consequences. Unfortunately, existing works failed to adequately analyze and identify most of such critical security flaws in MFA protocols. In this work, we systematically analyze the intricate design and construction of MFA protocols to uncover potential design-level security flaws. To this end, we first define eight security evaluation criteria that are essential to critically evaluate and identify design-level security flaws of MFA protocols. These criteria are primarily derived from existing and newly introduced MFA security requirements. We then review a range of MFA protocols across various domains, including client-server systems, cloud computing, finance, healthcare, internet of things (IoT), wireless sensor networks (WSN), smart cities, and other industrial applications. Using our established evaluation criteria, we perform a systematic security analysis and evaluation of these protocols, particularly focusing on their design and construction. Ultimately, our investigation uncovers several security flaws in most of the MFA protocols evaluated. Due to space limitations, we select ten of the vulnerable MFA protocols for deeper security analysis and provide a detailed discussion of the respective flaws identified. Additionally, we devise relevant mitigation strategies to address each of the security flaws identified. Furthermore, we consolidate the runtime performance information of these MFA protocols, as it is directly related to their design, highlighting the trade-off between security and efficiency. our findings provide valuable insights to cybersecurity researchers and practitioners, helping them address a wide range of security flaws in the design of MFA protocols. Moreover, this investigation underscores the need for improved design and implementation practices to ensure that MFA protocols remain effective to enhance system security."
# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: false

links:
 - name: "[IF = 28]"
   url: "https://dl.acm.org/journal/csur"
 #- name: Publication Site
   #url: "https://www.sciencedirect.com/science/article/abs/pii/S1874548221000238"
#url_pdf: https://www.sciencedirect.com/science/article/pii/S0167404820301061
#url_pdf: pdf/MFA-Vulnerabilities.pdf
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
