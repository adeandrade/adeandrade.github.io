---
title: "Lossy Common Information in a Learnable Gray-Wyner Network"
collection: publications
category: conferences
permalink: /publication/common-information
excerpt: 'Isolate the common information between two dependent computer vision tasks.'
date: 2026-02-01
venue: 'ICLR'
paperurl: 'https://arxiv.org/pdf/2601.21424'
citation: 'Anderson de Andrade, Alon Harell, & Ivan Bajić. (2026). &quot;Lossy Common Information in a Learnable Gray-Wyner Network.&quot; <i>ICLR</i>.'
---
Many computer vision tasks share substantial overlapping information, yet conventional codecs tend to ignore this, leading to redundant and inefficient representations. The Gray-Wyner network, a classical concept from information theory, offers a principled framework for separating common and task-specific information. Inspired by this idea, we develop a learnable three-channel codec that disentangles shared information from task-specific details across multiple vision tasks. We characterize the limits of this approach through the notion of lossy common information, and propose an optimization objective that balances inherent tradeoffs in learning such representations. Through comparisons of three codec architectures on two-task scenarios spanning six vision benchmarks, we demonstrate that our approach substantially reduces redundancy and consistently outperforms independent coding. These results highlight the practical value of revisiting Gray-Wyner theory in modern machine learning contexts, bridging classic information theory with task-driven representation learning.
