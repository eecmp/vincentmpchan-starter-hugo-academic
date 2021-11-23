---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Monolithic Digitally Controlled Ripple-Based DC-DC Converter with Digital Inductor Current Sensor"


authors:
  - Man Pun Chan
  - Philip K.T. Mok

abstract: A ripple-based control scheme for DC-DC converters is presented which can fast load-transient responses by sensing inductor current and using it as feedback ripples. Conventionally, analog RC inductor current sensors can be used for that purpose. However, the RC passive components are too bulky to integrate on-chip, and digital controllers cannot use the analog ripples for the control purpose unless extra ADCs are available to quantize them. Therefore, this paper proposes a digital inductor current sensor that does not require the extra ADCs and occupies a small chip area. A ripple-based digital controller has been implemented to demonstrate how the digital sensor can be utilized. Both the digital sensor and controller are fully synthesizable with a UMC 0.13-μm digital CMOS process. Their total chip areas are 220μm×220μm. Measurements results show that a 2MHz buck converter achieves load-transient responses of 10μs by using the digital controller. The peak efficiency is 91% at 100mA of the loading current.

date: "2013-09-01"
doi: "10.1109/CICC.2013.6658484"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2013 IEEE Custom Integrated Circuits Conference (CICC)
publication_short: Proc. IEEE Custom Integrated Circuits Conf.

tags: []
categories: []
#date: 2021-11-22T00:09:20-05:00
#lastmod: 2021-11-22T00:09:20-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
