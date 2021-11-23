---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Design and Implementation of Fully Integrated Digitally Controlled Current-Mode Buck Converter"


authors:
  - Man Pun Chan
  - Philip K.T. Mok

abstract: Digital current-mode control is a dual-loop control which potentially results in a better transient response and thus is more favorable than voltage-mode control. There are only a few publications on how to design and implement a fully integrated digital controller as the on-chip implementation is very challenging, especially for current-mode control. This paper addresses those design challenges and considerations. One of the main challenges is to efficiently sample and quantize both the output voltage and inductor current of the buck converter for control purposes. A time-multiplex scheme is used for the control-loop which enables the converter to work with a single ADC. A modified delay-lock-loop DPWM has been developed for minimizing the mismatch of the delay-cells. This enhances the accuracy at high frequency to prevent limit-cycle. A new algorithm has also been proposed for implementing look-up-table digital compensators with 20% less chip area. A converter with the fully integrated digitally controlled loop, including the single ADC, digital compensators and DPWM, has been fabricated in a CMOS 0.35 &#x03BC;m process with a chip area of 1049 &#x03BC;m &#x00D7; 1533 &#x03BC;m. Measurement results show that the buck converter has a load transient response of 20 &#x03BC;s, which is one of the fastest compared to other state-of-the-art digitally controlled buck converter.

date: "2011-08-01"
doi: "10.1109/TCSI.2011.2112531"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Circuits and Systems I
publication_short: IEEE Trans. Circuits Syst. I, Reg. Papers

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
