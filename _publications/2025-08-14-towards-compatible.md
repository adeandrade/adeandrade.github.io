---
title: "Towards task-compatible compressible representations"
collection: publications
category: conferences
permalink: /publication/towards-compatible
excerpt: 'Task reconstruction loss acts as a regularizer, increasing rate-distortion performance in coding for humans and machines.'
date: 2025-08-14
venue: 'ICME Workshop on Coding for Machines'
slidesurl: 'http://adeandrade.github.io/files/towards-compatible-slides.pdf'
paperurl: 'https://arxiv.org/pdf/2405.10244'
bibtexurl: 'https://dblp.org/rec/conf/icmcs/AndradeB24.bib'
citation: 'de Andrade, Anderson, & Bajić, I. (2024). &quot;Towards task-compatible compressible representations. ICME Workshop on Coding for Machines.&quot; <i>ICME Workshop on Coding for Machines</i>.'
---
We identify an issue in multi-task learnable compression, in which a representation learned for one task does not positively contribute to the rate-distortion performance of a different task as much as expected, given the estimated amount of information available in it. We interpret this issue using the predictive -information framework. In learnable scalable coding, previous work increased the utilization of side-information for input reconstruction by also rewarding input reconstruction when learning this shared representation. We evaluate the impact of this idea in the context of input reconstruction more rigorously and extended it to other computer vision tasks. We perform experiments using representations trained for object detection on COCO 2017 and depth estimation on the Cityscapes dataset, and use them to assist in image reconstruction and semantic segmentation tasks. The results show considerable improvements in the rate-distortion performance of the assisted tasks. Moreover, using the proposed representations, the performance of the base tasks are also improved. Results suggest that the proposed method induces simpler representations that are more compatible with downstream processes.
