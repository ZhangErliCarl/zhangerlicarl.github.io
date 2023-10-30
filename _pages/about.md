---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👤 About me
Hi, I am Erli Zhang. I am a final-year undergraduate at Nanyang Technological University 🇸🇬, majoring in Computer Science. My current research interests include **Multimodal Large Language Model**, **Visual Quality Assessment** and **AI in Healthcare**. I aspire to contribute significantly to the academic community, looking forward to joining a PhD program where I can further explore this field.

- **Resume:** [Resume](https://github.com/ZhangErliCarl/ZhangErliCarl/blob/d9101d841202d5aff85f377b96e659a974600480/resume.pdf)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?user=gfjYZKMAAAAJ&hl=en-US)
- **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/zhang-erli/)

# 📬 Contact Me
- **Email:** zhangerlicarl@gmail.com or ezhang005@e.ntu.edu.sg
- **Twitter:** [@zhang_erli](https://twitter.com/zhang_erli)

<span class='anchor' id='-news'></span>
# 🔥 News
- *2023.07.26*: &nbsp;🎉🎉 MaxVQA get accepted by ACMMM2023 (CCF-A)!
- *2023.07.14*: &nbsp;🎉🎉 DOVER get accepted by ICCV2023 (CCF-A)!

<span class='anchor' id='-publications'></span>
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://github.com/VQAssessment/Q-Bench/raw/master/qbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-Level Vision](https://github.com/VQAssessment/Q-Bench) [![](https://img.shields.io/github/stars/Q-Future/Q-Bench)](https://github.com/Q-Future/Q-Bench)

Haoning Wu\*, Zicheng Zhang\*, **Erli Zhang**\*, Chaofeng Chen, Liang Liao, Annan Wang, Chunyi Li, Wenxiu Sun, Qiong Yan, Guangtao Zhai, Weisi Lin

- We construct the Q-Bench, a benchmark to examine the progress of MLLMs on low-level visual abilities. Anticipating these large foundation models to be general-purpose intelligence that can ultimately relieve human efforts, we propose that MLLMs should achieve three important and distinct abilities: perception on low-level visual attributes, language description on low-level visual information, as well as IQA.
- Submit your model at [our project page](https://github.com/VQAssessment/Q-Bench/) to compete with existing ones!

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2023</div><img src='https://github.com/VQAssessment/MaxVQA/raw/master/figs/maxwell.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Explainable Video Quality Assessment: A Database and a Language-Prompted Approach](https://github.com/VQAssessment/MaxVQA)
  
Haoning Wu\*, **Erli Zhang**\*, Liang Liao, Chaofeng Chen, Jingwen Hou, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/MaxVQA) [![](https://img.shields.io/github/stars/VQAssessment/MaxVQA)](https://github.com/VQAssessment/MaxVQA),  [**ArXiv**](https://arxiv.org/abs/2305.12726)
  
- We collect over two million human opinions on 13 dimensions of quality-related factors to establish the multi-dimensional Maxwell database. Furthermore, we propose the MaxVQA, a language-prompted VQA approach that modifies CLIP to better capture important quality issues as observed in our analyses. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='https://github.com/teowu/teowu.github.io/raw/main/images/dover.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Video Quality Assessment on User Generated Contents from Aesthetic and Technical Perspectives](https://github.com/VQAssessment/DOVER)
  
Haoning Wu\*, **Erli Zhang**\*, Liang Liao\*, Chaofeng Chen, Jingwen Hou, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/DOVER) [![](https://img.shields.io/github/stars/VQAssessment/DOVER)](https://github.com/VQAssessment/DOVER),  [**ArXiv**](https://arxiv.org/abs/2211.04894v3)
  
- The proposed Disentangled Objective Video Quality Evaluator (**DOVER**) reached state-of-the-art performance (0.91 SRCC for KoNViD-1k, 0.89 SRCC for LSVQ, 0.89 SRCC for YouTube-UGC) in the UGC-VQA problem. More importantly, our subjective studies construct the first aesthetic and technical VQA database, the DIVIDE-3k, proving that UGC-VQA is jointly affected by the two perspectives.
</div>
</div>

<span class='anchor' id='-educations'></span>
# 📖 Educations
- *2020.08.10 - 2024.05.30 (expected)*, Undergraduate Student, Major in Computer Science, Nanyang Technological University
  - Specialization: Artificial Intelligence & Data Science
  - final year project supervised by [Prof. Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html)
  - Research Topic: Explainable Visual Quality Assessments.
- *2021.08.10 - 2021.12.01*, SUSEP Exchange Student, National University of Singapore

<span class='anchor' id='-honors-and-awards'></span>
# 🎖 Honors and Awards
- *2022.7* CFAR Internship Award for Research Excellence
- *2019.6* NTU Science and Engineering Undergraduate Scholarship

<span class='anchor' id='-internships-and-projects'></span>
# 💻 Internships and Projects
- *July 2023-Present*, [**Center for Cognition, Vision, and Learning, Johns Hopkins University**](https://ccvl.jhu.edu/), Research Student
  - Supervisor: Prof Alan L. Yuille
  - Evaluate how the robustness of a sequential learning model changes with every new task relative to jointly trained neural models
  - Adapt current robustness methods to continual learning setups and analyse whether they improve model robustness when learning continually
- *May 2023-July 2023*, [**Sunstella Foundation**](https://sites.google.com/view/sunstella-foundation/home), Summer Research Scholar
  - Supervisor: Prof Jimeng Sun
  - Worked on MedBind, an AI model combining multiple modalities to generate synthetic patient records to enhance clinical research
  - Contributed to PyHealth, a comprehensive deep learning toolkit for supporting clinical predictive modelling
- *July 2022-May 2023*, [**Institute for Infocomm Research**](https://www.a-star.edu.sg/i2r/research-capabilities/healthcare-medtech), AI Research Engineer
  - Supervisor: Dr Weimin Huang
  - Conducted insightful research into the field of medical image processing, specifically in mammogram analysis
  - Developed a model using weakly semi-supervised learning and transformers to predict breast cancer risk at multiple time points based on traditional mammograms and common risk factors and clinical data
- *July 2021-May 2022*, [**Undergraduate Research Experience on Campus, Nanyang Technological University**](https://www.ntu.edu.sg/education/undergraduate-research-experience-on-campus-(ureca)), URECA Research Student
  - Supervisor: Prof Weisi Lin
  - Identified common factors that lead to bias in facial analysis, e.g., occlusions, pose variation, expressions, etc.
  - Evaluated current state-of-the-art face recognition methods on various datasets with bias
  - Compared common feature detection and description techniques in occluded datasets 

