---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech in Computer Science Engineering, Indian Institute of Technology Bhilai, 2019-2023 (GPA-9.66/10.00)


Work experience
======
* Apr 2026 - Present: Research SDE at Microsoft M365 Research
  * Working on efficient LLM inference

* Jul 2024 - Apr 2026: Research Fellow at Microsoft Research India
  * Designed an efficient & practical sparse attention technique Kascade.
  * Impact: Kascade achieves up to 4.1x speedup for decode attention and 2.2x for
  prefill attention over FlashAttention-3 on H100 GPUs using custom kernels.
  * Impact: Verified using large models like Qwen-3-32B, maintaining dense-model
  accuracy on reasoning benchmarks (AIME-24).
  * Architected a modular evaluation framework using the Strategy Pattern to de
  couple attention implementations from models, enabling rapid benchmarking of
  sparse attention schemes via Transformers on a range of downstream tasks.
  * Supervised finetuning using FSDP on MultiHop Question-Answering datasets to learn
  document-local sparse attention.


* Oct 2023 - Jun 2024: Associate Software Development Engineer at Publicis Sapient
  * Modernized the Deposits journey on web and mobile for Lloyds Banking Group
  * Spearheaded WCAG 2.1 accessibility for the application


* Feb 2023 - May 2023: UG Research Fellow at TIH IIT Bhilai
  * Created the prototype for a Bike Renting System using LoRa technology
  * LoRa Protocol for communication between Gateway and bike-locks
  * Coding the App-Server system for renting the bike


* May 2022 - July 2022: Sofware Development Engineering Intern at Publicis Sapient
  * Integrated Google PubSub communication in Point of Sale ordering and management system making it data flow more reliable
  * Designed and Deployed end-to-end face recognition microservice 25% more efficient and 99% smaller network data packet size than earlier design

Achievements
======
* Award for Learning Mindset at client townhall while working at Publicis Sapient
* Smart India Hackathon'22 Finalist & Runner Up in Software Monitoring category
* Member of a team of 4 that stood 1892/9000+ teams in Google Hashcode'21 
* Led a team that stood 279/3500+ teams in the ICPC'21 Amritapuri preliminary round and qualified for the regional round

  
Skills
======
* Languages: Python, C++, C, Javascript, CUDA,  Go
* ML Technologies: Deep Graph Library(DGL), PyTorch, OpenCV, HuggingFace
* Tools: Git, Github, Docker(basic), Python Notebooks, AWS, GPGPUSim, Kubernetes, Microk8s, GCP
* Coursework: Data Structures, Algorithms, Machine Learning, Parallel Programming, Artificial Intelligence, Information Retrieval, Computer System Design, Natural Language Processing, Approximation Algorithms, Digital Image Processing, Distributed Systems


Projects
======
  <ul>{% for post in site.research-projects %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* May 2022-Mar 2023IIT Bhilai - DSAI Club Department Head computer Vision
  * Spearheaded in projects related to computer vision
  * Conducted workshops to introduce students to computer vision
* May 2021-Apr 2022 IIT, Bhilai - Centre for Career Planning Services Computer Science Representative
  * Led a team of 4 to create and conduct 6 programming/technical tests to make final year students interview ready
* May 2021-Apr 2022 IIT, Bhilai - UG EECS Representative
  * Guided students regarding academic decisions
  * Faciliated smooth function of academic activites at insitute 

