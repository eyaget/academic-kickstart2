---
authors:
- Eyasu Getahun Chekole
- Huaqun Guo
title: "DARUD: Detecting and Arresting Rogue USB Devices in the V2X Ecosystem"
date: "2021-12-11"
doi: "10.1109/SOLI54607.2021.9672338"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-27"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*15th IEEE International Conference on Service Operations and Logistics, and Informatics (SOLI'21), IEEE*"
publication_short: "*15th IEEE International Conference on Service Operations and Logistics, and Informatics (SOLI'21), IEEE*"

abstract: Vehicle-to-Everything (V2X) is a cutting-edge technology in intelligent transportation systems (ITS). In V2X, various entities communicate and cooperate each other to ensure road safety and efficiency. However, such communications and cooperation also pose various security risks to the transportation system. In particular, due to the involvement of several unattended roadside devices, such as roadside units (RSUs), industrial PCs, traffic light controllers, 3D laser scanners, video cameras, and pedestrian sensors, the V2X ecosystem is highly vulnerable to malware attacks. Attackers may use rogue USB devices to inject various types of malware (e.g., viruses, spyware, ransomware and worms) to the V2X system via the USB ports of the roadside devices. Such attacks may result in a debilitating impact on the safety and efficiency of road traffic. Although a wide-range of approaches have been proposed against USB-based attacks, most of them have several limitations, especially when applied in the V2X context. For example, the widely adopted approaches against USB-based attacks are scanning USB devices using anti-malware/antivirus tools (which is often not effective against zero-day malware), disabling USB ports (security-through-obscurity has already several drawbacks), whitelisting USB devices using certain attributes of the USB devices (which is often bypassed by brute-force attacks and not effective against dishonest USB users). Furthermore, most of the existing solutions are implemented only for general purpose computing devices (e.g., computers and servers), hence might not be suitable for sensors and tiny IoT devices involved in the V2X environment. Moreover, the configuration and update processes of most existing solutions requires physical access to the devices, which might not be feasible in V2X where devices and sensors are dispersed across various roadside locations. In this work, we propose and implement DARUD – a lightweight and automated toolkit that dynamically detects and prevents rogue USB devices in V2X. This is achieved by constructing a USB authorization policy based on kernel-level USB rules and fingerprints. The proposed solution can also be configured and updated to the roadside devices over-the-air via a secured VPN tunneling. This avoids the hassle of physically configuring or updating the USB-security solutions on each roadside device. The effectiveness of our proposed approach is also tested using a realistic V2X infrastructure.

# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: false

# links:
 - name: Publication Site
   url: "https://ieeexplore.ieee.org/document/9672338"
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
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

