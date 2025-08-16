---
title: "An architecture for accelerated large-scale inference of transformer-based language models"
collection: publications
category: conferences
permalink: /publication/transformer-inference
excerpt: 'Unified batch and online transformer inference.'
date: 2021-02-14
venue: 'NAACL Conference on Human Language Technologies: Industry Papers'
paperurl: 'https://aclanthology.org/2021.naacl-industry.21.pdf'
bibtexurl: 'https://dblp.org/rec/conf/naacl/GanievCAL21.bib'
citation: 'Amir Ganiev, Colt Chapin, Anderson de Andrade, & Chen Liu. (2021). &quot;An architecture for accelerated large-scale inference of transformer-based language models.&quot; <i>NAACL Conference on Human Language Technologies: Industry Papers</i>.'
---
This work demonstrates the development process of a machine learning architecture for inference that can scale to a large volume of requests. In our experiments, we used a BERT model that was fine-tuned for emotion analysis, returning a probability distribution of emotions given a paragraph. The model was deployed as a gRPC service on Kubernetes. Apache Spark was used to perform inference in batches by calling the service. We encountered some performance and concurrency challenges and created solutions to achieve faster running time. Starting with 3.3 successful inference requests per second, we were able to achieve as high as 300 successful requests per second with the same batch job resource allocation. As a result, we successfully stored emotion probabilities for 95 million paragraphs within 96 hours.
