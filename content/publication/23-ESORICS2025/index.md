---
authors:
- Howard Halim
- Eyasu Getahun Chekole
- Daniel Reijsbergen 
- Jianying Zhou
title: "BlowPrint: Blow-Based Multi-Factor Biometrics for Smartphone User Authentication"
date: "2025-06-22"
#doi: "https://doi.org/10.1145/3734864"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-22"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Accepted at ***The 30th European Symposium on Research in Computer Security (ESORICS'25)***, Springer"
publication_short:  "Accepted at ***The 30th European Symposium on Research in Computer Security (ESORICS'25)***, Springer"

abstract: "Biometric authentication is a widely used security mechanism that leverages unique physiological or behavioral characteristics to authenticate users. In multi-factor biometrics (MFB), multiple biometric modalities, e.g.,  physiological and behavioral biometrics, are integrated to mitigate the limitations inherent in single-factor biometric systems. The primary research challenge within MFB lies in identifying novel behavioral techniques capable of meeting critical criteria, including high accuracy, high usability,  non-invasiveness, resilience against spoofing and other known attacks, and low use of computational resources. Despite ongoing advancements, current behavioral biometric techniques often fall short of fulfilling one or more of these requirements. <br/><br/> 

In this work, we propose *BlowPrint*, a novel behavioral biometric technique that allows us to authenticate users based on their phone blowing behaviors. In brief, we assume that the way users blow on a phone screen can produce distinctive acoustic patterns, which can serve as a unique behavioral biometric identifier for effective user identification or authentication. The acoustic features of blowing, such as differences in pattern, intensity, frequency, and timing, are unique to each person, making this technique highly accurate, non-invasive, and exceedingly robust against spoofing and other attacks. Moreover, it can be concurrently performed and seamlessly integrated with other physiological techniques, such as facial recognition, thereby enhancing usability. <br/><br/>

To assess BlowPrint's effectiveness, we conduct an empirical study involving 50 participants from whom we collect blow-acoustic and facial feature data in both sitting and standing modes. Subsequently, we compute the similarity scores of the blow-acoustic data using various time-series similarity algorithms, while we use a pretrained FaceNet-512 model for the facial recognition features. Finally, we combine the similarity scores of the two modalities through score-level fusion and compute the accuracy using a machine learning-based classifier. As a result, the proposed method demonstrates an accuracy of 99.35% for blow acoustics, 99.96% for facial recognition, and 99.82% for the combined approach. The experimental results demonstrate BlowPrint's high effectiveness in terms of authentication accuracy, spoofing attack resilience, usability, non-invasiveness, and other aspects."
# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: false

links:
 - name: "Preprint"
   url: "https://arxiv.org/abs/2507.04126"
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
