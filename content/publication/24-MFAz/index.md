---
authors:
- Eyasu Getahun Chekole
- Howard Halim
- Jianying Zhou
title: "MFAz: Historical Access Based Multi-Factor Authorization"
date: "2025-07-05"
#doi: "https://doi.org/10.48550/arXiv.2407.20459"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-05"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Preprint"
publication_short:  "Preprint"

abstract: "Unauthorized access to private resources (such as data and services) remains one of the most critical security challenges in the realm of cybersecurity. With the increasing sophistication of attack techniques, the threat of unauthorized access is no longer confined to the conventional ones, such as exploiting weak access control policies. Instead, advanced exploitation strategies, such as session hijacking-based attacks, are becoming increasingly prevalent, posing serious security concerns. Session hijacking enables attackers to take over an already established session between legitimate peers, thereby gaining unauthorized access to private resources. These attacks are typically conducted in a stealthy manner, making their detection exceedingly difficult. Unfortunately, traditional access control mechanisms, such as static access control policies, are insufficient to prevent session hijacking or other advanced exploitation techniques. In this work, we propose a new multi-factor authorization (MFAz) scheme that proactively mitigates unauthorized access attempts both conventional and advanced unauthorized access attacks. The proposed scheme employs fine-grained access control rules (ARs) and verification points (VPs) that are systematically generated from historically granted accesses as the first and second authorization factors, respectively. As a proof-of-concept, we implement the scheme using different techniques. We leverage bloom filter to achieve runtime and storage efficiency (even for resource-constrained devices), and blockchain to make authorization decisions in a temper-proof and decentralized manner. To the best of our knowledge, this is the first formal introduction of a multi-factor authorization scheme, which is orthogonal to and distinct from the widely used multi-factor authentication (MFA) schemes. The effectiveness of our proposed scheme is experimentally evaluated using a smart city testbed involving different devices with varying computational capacities. The experimental results reveal high effectiveness of the scheme both in security and performance guarantees."
# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: false

links:
 - name: Preprint
   url: "https://arxiv.org/abs/2507.16060"
 #- name: Publication Site
   #url: "https://www.sciencedirect.com/science/article/abs/pii/S1874548221000238"
#url_pdf: https://www.sciencedirect.com/science/article/pii/S0167404820301061
url_pdf: pdf/MFA-Vulnerabilities.pdf
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
