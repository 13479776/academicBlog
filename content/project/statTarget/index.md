---
title: statTarget
summary: 一种流线型的工具，具有简单易用的界面，提供组学数据的数据校正（QC-RFSC）和广泛的精确地统计分析。
tags:
- Metabolomics software 
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: 
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

质量控制是生物分析的基本概念之一，用在保证组学测定的数据的重复性和精确性。由于色谱系统与质谱直接与样品接触， 随着分析样品的增多，色谱柱和质谱会逐步的污染，导致信号的漂移。通过重复使用同一个质控样本来跟踪整个数据采集过程的行为， 已经被大多数的分析化学领域专家推荐和使用。质控样本被用于评估整个质谱数据在采集过程中的信号漂移， 这些漂移进一步能够被精确的算法所识别，校正，提高数据的质量。如图1所示，蓝色质控样本点的特征峰信号强度在整个分析过程中能够具有将近6倍差异（最高点-最低点）， 通过QC-RFSC算法校正后，信号强度差异被降到了1.5倍以内。完全符合FDA对于生物样本分析的质控要求。

statTarget是一种流线型的工具，具有简单易用的界面，提供组学数据的数据校正（QC-RFSC）和广泛的精确地统计分析。

引用文章看这里

您的大作如果使用了statTarget或者QC-RFSC算法，请引用这里

Luan H., Ji F., Chen Y., Cai Z. (2018) statTarget: A streamlined tool for signal drift correction and interpretations of quantitative mass spectrometry-based omics data. Analytica Chimica Acta. dio: https://doi.org/10.1016/j.aca.2018.08.002

Luan H., Ji F., Chen Y., Cai Z. (2018) Quality control-based signal drift correction and interpretations of metabolomics/proteomics data using random forest regression. bioRxiv 253583; doi: https://doi.org/10.1101/253583

statTarget的基本功能

statTarget提供了两个基本模块功能。

1，shiftCor() ….. 该功能包含了发表在国际主流期刊发表的算法QC-RFSC和QC-RLSC，用于数据的质量控制，评估与校正。

2，statAnalysis() ….. 该功能包含了非常广泛的统计学内容，一键式设计自动化，可以输出任意两组的主成分分析，偏最小二乘法-判别分析，随机森林，P值，BH方法假阳性校正后P值（Q值），Odd ratio， 火山图，倍数值。在组学统计分析与生物标记物分析非常实用。即刻拿到所有的可靠地数据结果。
