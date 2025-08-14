---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* Ph.D in Engineering Science, Simon Fraser University, 2027 (expected)
* M.S. in Applied Computing, University of Toronto, 2015
* B.E. in Networks and Communications, Universidad Tecnológica del Centro (Venezuela), 2007

Work experience
======

* Fall 2015: Research Assistant, Simon Fraser University
  * Research in information theory, learning theory, and machine learning
  * Supervisor: Professor Ivan Bajic

* 2017-2021: Senior Data Scientist, Wattpad
  * Researched deep learning models to learn disentangled latent representations from unsupervised long-form text
  * Developed language models for affect analysis that incorporate knowledge graph information using attention mechanisms
  * Researched multilingual models to encode sentences into syntactic representations
  * Researched reinforcement learning models to elicit user preferences
  * Developed a Bayesian optimization engine to improve content discovery

* 2015-2017: Research Engineer, VerticalScope
  * Researched and developed algorithms to quantify and predict the performance of hundreds of social networks
  * Researched neural networks and probabilistic graphical models in semi-supervised scenarios for language processing tasks

* 2015: Data Scientist, Terapeak
  * Developed information theory algorithms to learn ontology representations from structured descriptions of products
  * Created a probabilistic model to learn synonym relationships between product terms
  
* 2014: Research Intern, BlackBerry
  * Researched predictive models for intrusion detection and multi-factor authentication
  * Developed temporal generative models and for outlier detection

* 2009-2010: Software Engineer, TDA
  * Developed data collection and statistical analysis platforms to derive insights

* 2004–2013: Software Engineer – Co-Founder, Web Lab
  * Solved problems in content management, real estate, e-learning, human resources, messaging and e-commerce

Skills
======

* High-performance scientific computing: Python, PyTorch, Numba, JAX
* Data engineering: Scala, Apache Spark, Apache Cassandra, Apache Kafka, Elasticsearch, SQL
* Backend development: Go, ZeroMQ, gRPC, Kubernetes

Awards
=====

* Mitacs Accelerate Fellowship
* Simon Fraser University Graduate Dean's Entrance Scholarship
* NSERC Canada Graduate Scholarship – Doctoral

Publications
======

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
