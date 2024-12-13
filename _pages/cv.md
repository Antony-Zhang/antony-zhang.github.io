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

- **Large Model Based Crossmodal Chinese Poetry Creation** (Jul. 2024 - Oct. 2024, Wuhan, China)
  - Advisor: [Dr. Weiping Zhu](https://cs.whu.edu.cn/info/1019/2920.htm), Wuhan University
  - **System Dewvelopment:** Led the development of modules supporting cross-modal text and image inputs.
  - **Optimization Evaluation:** Enhanced iterative optimization mechanisms and evaluated poem quality across three input modalities and optimization on three poem sets.

- **Data Analysis on Forward Flow Task** (Apr. 2024 - Jun. 2024, Remote)
  - Advisor: [Prof. Yunzhe Liu](https://brain.bnu.edu.cn/kytd/jsyjy/Ljs/18e25c12984e48eb966932924b9b76c7.htm), NKLCNL, Beijing Normal University
  - **Data Prepocessing:** Pre-processed word data for forward flow tasks, inserting seed words, removing duplicates, and generating embeddings.
  - **Correlation Analysis:** Analyzed the correlation between participants’ scale scores and statistical indicators, including sequence length, embedding similarity, optimality divergence, semantic distance range, and "forward flow".

  <!-- - Pre-processed words data on forward flow tasks, generated embeddings, and explored correlation between participants’ scale scores and statistical indicators, the latter includes sequence length, similarity of embedding, optimality divergence, range of semantic distance, and "forward flow" -->

<!-- * Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git -->
  
## Project Experience

- **The Working Memory Capacity of RNN models**  (Summer 2024)
  - Computational Neuroscience Program, [Neuromatch Academy](https://neuromatch.io) (NMA)
  - **Memory Decoding:** Built a neural network to decode firing rates into previous inputs, computing correlations to assess the WM capacity of RNN models.
  - **Parameter Exploration:** Led the exploration of effects of parameter simulating biological factors and interactions on WM capacity.
  
  <!-- - Developed a RNN-based model with parameters simulating biological factors contributing to working memory, and investigate the effects of each parameter as well as their interactions on the WM capacity. -->

- **LLM-based Interactive Chinese Poetry Learning Assistant** (Fall 2023)
  - 2023 Large Models Scene Innovation Competition - Innovation Award (Top 8%) 
  - **Interface Design:** Designed the web interface and user-specific prompts for image production and text interaction.
  - **Module Development:** Developed modules incorporating online search and file analysis based on Retrieval-Augmented Generation (RAG).
  
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
