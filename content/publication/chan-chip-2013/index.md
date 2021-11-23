---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "On-Chip Digital Inductor Current Sensor for Monolithic Digitally Controlled DC-DC Converter"


authors:
  - Man Pun Chan
  - Philip K.T. Mok

abstract: Conventionally, inductor current is sensed and quantized before it can be used by digitally controlled DC-DC converters. These are intuitively done by using two separated functional blocks—an analog current sensor and an ADC. A few research works have investigated other ways of obtaining the inductor current information in the digital domain. This paper proposes an on-chip digital inductor current sensor that combines both the inductor current-sensing and quantization into a single functional block. In this way, the redundancies found in the conventional approach can be reduced and optimizations can be made to save chip area and power consumption. An 8-bit digital inductor current sensor has been designed and fabricated with a UMC 0.13 $\mu m$ CMOS process. The measurement results show that the digital sensor can provide digital inductor current information with a conversion time of 225 ns. This can be used by a buck converter with a switching frequency up to 4 MHz. The digital sensor has linear and monotonic input-output transfer curve properties with an LSB of 6.79 mA. It consumes current of 700$\mu A$ at 1.2 V supply voltage.

date: "2013-05-01"
doi: "10.1109/TCSI.2013.2239165"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication:  IEEE Transactions on Circuits and Systems I
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
