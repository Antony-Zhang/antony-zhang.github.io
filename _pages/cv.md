---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


## Education
<!-- * Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014 -->
* B.E. in Software Engineering, Wuhan University, 2025 (expected)

## Research experience

- **Data Analysis on Forward Flow Task** (Spring 2024)
  - Research assistant (Remote) in NKLCNL, Beijing Normal University, China
  - Duties included: Pre-processing words data on forward flow tasks, generating embeddings, computing statistical indicators, and analyzing correlation between indicators and participants’ scale scores;
  - Supervisor: Professor Yunzhe Liu

<!-- * Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git -->
  
## Projects experience

- **The Working Memory Capacity of RNN models**  (Summer 2024)
  - Computational Neuroscience Program, Neuromatch Academy
  - Developed a RNN-based model with parameters simulating biological factors contributing to working memory, and investigate the effects of each parameter as well as their interactions on the WM capacity.

- **LLM-based Interactive Chinese Poetry Learning Assistant** (Fall 2023)
  - 2023 Large Models Scene Innovation Competition - Innovation Award (Top 8%) 
  - Developed a LLM-based interactive Chinese poetry learning assistant by Gradio with ability of online searching, file analysis, and image production, which can chat with users from different age groups.

  <!-- - Designed prompts for image production as well as text interaction for different users, integrated them into program with Langchain based on API of SparkDesk;
  - Developed modules for online searching and file uploading based on RAG, including data indexing, query formulation, retrieval, data integration and response generation;
  - Developed web interface based on Gradio, including history records, theme selection, mode switching and file uploading. -->

  <!-- - Built a network to decode firing rates into previous input, use the correlation between real and decoded input to denote the WM capacity of RNN-model; -->

## Publications
  <!-- <i>* Equal authorship</i> -->
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

## Skills
- Data Analysis: Machine Learning, Deep Learning, EEG processing, Digital signal processing
- Programming: Python, C/C++
- Tools: Unix Shell, VS Code, Git/GitHub, Zotero
- Language: English(IELTS 7.0), Mandarin(native)


> You can download a PDF copy of my CV [here]({{base_path}}/files/CV_ZhidongZhang.pdf).


<embed src="{{base_path}}/files/CV_ZhidongZhang.pdf" type="application/pdf" width="70%" height="500px">


<!-- ![CV_ZhidongZhang]({{base_path}}/files/CV_ZhidongZhang.pdf) -->


<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
