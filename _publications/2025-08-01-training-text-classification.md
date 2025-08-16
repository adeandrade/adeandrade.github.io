---
title: "A comparison of neural network training methods for text classification"
collection: publications
category: manuscripts
permalink: /publication/training-text-classification
excerpt: 'Benchmark of stochastic gradient descent and Nesterov''s accelerated gradient for text classification.'
date: 2013-12-15
venue: 'arXiv'
paperurl: "https://arxiv.org/pdf/1910.12674"
bibtexturl : 'https://dblp.uni-trier.de/rec/journals/corr/abs-1910-12674.bib'
citation: 'Anderson de Andrade. (2013). &quot;A comparison of neural network training methods for text classification.&quot; <i>arXiv:1910.12674</i>.'
---
We study the impact of neural networks in text classification. Our focus is on training deep neural networks with proper weight initialization and greedy layer-wise pretraining. Results are compared with 1-layer neural networks and Support Vector Machines. We work with a dataset of labeled messages from the Twitter microblogging service and aim to predict weather conditions. A feature extraction procedure specific for the task is proposed, which applies dimensionality reduction using Latent Semantic Analysis. Our results show that neural networks outperform Support Vector Machines with Gaussian kernels, noticing performance gains from introducing additional hidden layers with nonlinearities. The impact of using Nesterov's Accelerated Gradient in backpropagation is also studied. We conclude that deep neural networks are a reasonable approach for text classification and propose further ideas to improve performance.
