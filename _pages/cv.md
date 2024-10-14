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
* B.Eng. in Software Engineering, Wuhan University, 2025 (expected)

## Research Experience

- Jul. 2024 - Oct. 2024: Research Intern 
  - Advisor: [Dr. Weiping Zhu](https://cs.whu.edu.cn/info/1019/2920.htm), Wuhan University
  - Paper: "Large Model Based Crossmodal Chinese Poetry Creation" (accepted)
  - Developed a large model based system that supports cross-modal input of text and image, provides interpretable annotations for generated Chinese poems, and supports multiple rounds of iterative optimization.
  - Refined the iterative optimization mechanism and the scoring system, and led the evaluation of the system, comparing poem quality across three input modalities and testing optimization on three poem sets of varying quality.

- Apr. 2024 - Jun. 2024: Research Intern (remote)
  - Advisor: [Prof. Yunzhe Liu](https://brain.bnu.edu.cn/kytd/jsyjy/Ljs/18e25c12984e48eb966932924b9b76c7.htm), NKLCNL, Beijing Normal University
  - Pre-processed words data collected on forward flow tasks, inserted seed words, removed repeated or not-found words, and generated embeddings.
  - Explored the correlation between participants' scale scores and statistical indicators, the latter includes sequence length, similarity of embedding, optimality divergence, range of semantic distance, and "forward flow".

  <!-- - Pre-processed words data on forward flow tasks, generated embeddings, and explored correlation between participants’ scale scores and statistical indicators, the latter includes sequence length, similarity of embedding, optimality divergence, range of semantic distance, and "forward flow" -->

<!-- * Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git -->
  
## Project Experience

- **The Working Memory Capacity of RNN models**  (Summer 2024)
  - Computational Neuroscience Program, [Neuromatch Academy](https://neuromatch.io)
  - Developed a RNN-based model with parameters simulating biological factors contributing to working memory, and explored the effects of each parameter as well as their interactions on the WM capacity;
  - Built a neural network to decode firing rates into previous input, and computed correlation between real and decoded input, which denote the WM capacity of RNN-model.
  
  <!-- - Developed a RNN-based model with parameters simulating biological factors contributing to working memory, and investigate the effects of each parameter as well as their interactions on the WM capacity. -->

- **LLM-based Interactive Chinese Poetry Learning Assistant** (Fall 2023)
  - 2023 Large Models Scene Innovation Competition - Innovation Award (Top 8%) 
  - Developed a LLM-based interactive Chinese poetry learning assistant by Gradio with ability of online searching, file analysis, and image production, which can chat with users from different age groups.
  - Designed prompts for image production and text interaction for different users, developed online searching and file analysis based on RAG.
  
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
- Language: English(IELTS 7.0), Mandarin(Native)


> You can download a PDF copy of my CV [here]({{base_path}}/files/CV_ZhidongZhang.pdf).

<iframe src="{{base_path}}/files/CV_ZhidongZhang.pdf" width="80%" height="750px"></iframe>
<!-- <embed src="{{base_path}}/files/CV_ZhidongZhang.pdf" type="application/pdf" width="70%" height="500px"> -->


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
