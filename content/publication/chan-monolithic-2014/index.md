---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Monolithic Digital Ripple-Based Adaptive-Off-Time DC-DC Converter With a Digital Inductor Current Sensor"


authors:
  - Man Pun Chan
  - Philip K.T. Mok

abstract: A ripple-based digital controller requires inductor current ripple as feedback signals and analog RC inductor current sensors can be used for sensing the ripple. However, the passive RC components are bulky to integrate on-chip and the digital controller cannot use the analog ripple for the control purpose unless extra ADCs are available to quantize the signal. Therefore, a digital inductor current sensor is presented in this paper for obtaining the ripple in the digital domain. As compared to the existing designs, the digital inductor current sensor does not require extra ADCs or knowledge of the inductor DCR. A ripple-based digital controller is designed to demonstrate how the digital sensor can be utilized. A digital frequency-lock-loop is also incorporated into the digital controller to alleviate the problem of variable switching-frequency that is commonly found in the ripple-based control scheme. Both the digital sensor and controller are fabricated in UMC 0.13 $\mu m$ digital CMOS process with a small chip area of $220 \mu m\times 220 \mu m$. Measurements results show that a 2 MHz (max. $\pm$6.5% in variation) buck converter achieves load-transient responses of about 5 $\mu s$ by using the digital controller. The peak efficiency is 91% at a nominal load current of 100 mA. 

date: "2014-08-01"
doi: "10.1109/JSSC.2014.2313567"

publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Journal of Solid-State Circuits
publication_short: JSSCC

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
