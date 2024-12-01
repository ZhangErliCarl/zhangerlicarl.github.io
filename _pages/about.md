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
Hi, I am Erli Zhang. I am a first year PhD student at National University of Singapore 🇸🇬, supervised by Asst Prof [Jin Yueming](https://cde.nus.edu.sg/ece/staff/jin-yueming/). My current research interests include **AI in Healthcare**, **Medical/Surgical Video Generation** and **Surgical Foundation Model**.

- **Resume:** [Resume](https://github.com/ZhangErliCarl/ZhangErliCarl/blob/d9101d841202d5aff85f377b96e659a974600480/resume.pdf)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?user=gfjYZKMAAAAJ&hl=en-US)
- **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/zhang-erli/)

# 📬 Contact Me
- **Email:** zhangerlicarl@gmail.com or erli.z@nus.edu.sg
- **Twitter:** [@zhang_erli](https://twitter.com/zhang_erli)

<span class='anchor' id='-news'></span>
# 🔥 News
- *2024.10.12*: &nbsp;🎉🎉 SurgSAM2 get accpepted by AIM-FM Workshop @ NeurIPS'24!
- *2024.05.22*: &nbsp;🎉🎉 Received PhD offer from National University of Singapore, Department of Biomedical Engineering
- *2024.02.27*: &nbsp;🎉🎉 Q-Instruct get accepted by CVPR2024!
- *2024.01.16*: &nbsp;🎉🎉 Q-Bench get accepted by ICLR2024 (spotlight)!
- *2023.07.26*: &nbsp;🎉🎉 MaxVQA get accepted by ACMMM2023 (oral)!
- *2023.07.14*: &nbsp;🎉🎉 DOVER get accepted by ICCV2023!

<span class='anchor' id='-publications'></span>
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 Workshop</div><img src='https://github.com/ZhangErliCarl/Surgical-SAM-2/raw/main/assets/architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Surgical SAM 2: Real-time Segment Anything in Surgical Video by Efficient Frame Pruning](https://github.com/jinlab-imvr/Surgical-SAM-2)

Haofeng Liu\*, **Erli Zhang**\*, Junde Wu\*,Mingxuan Hong, Yueming Jin

[**GitHub**](https://github.com/jinlab-imvr/Surgical-SAM-2) [![](https://img.shields.io/github/stars/jinlab-imvr/Surgical-SAM-2)](https://github.com/jinlab-imvr/Surgical-SAM-2),  [**Paper**](https://arxiv.org/pdf/2408.07931)

- We introduce Surgical SAM 2 (SurgSAM-2), an innovative model that leverages the power of the Segment Anything Model 2 (SAM2), integrating it with an efficient frame pruning mechanism for real-time surgical video segmentation. 
- SurgSAM-2 dramatically reduces memory usage and computational cost of SAM2 for real-time clinical application, achieving superior performance with 3× FPS (86 FPS), and making real-time surgical segmentation in resource-constrained environments a feasible reality.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='https://github.com/Q-Future/Q-Instruct/raw/main/new_q_instruct.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Instruct: Improving Low-level Visual Abilities for Multi-modality Foundation Models](https://github.com/Q-Future/Q-Instruct)

Haoning Wu\*, Zicheng Zhang\*, **Erli Zhang**\*, Chaofeng Chen, Liang Liao, Annan Wang, Kaixin Xu, Chunyi Li, Jingwen Hou, Guangtao Zhai, Geng Xue, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/Q-Future/Q-Instruct) [![](https://img.shields.io/github/stars/Q-Future/Q-Instruct)](https://github.com/Q-Future/Q-Instruct),  [**Paper**](https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_Q-Instruct_Improving_Low-level_Visual_Abilities_for_Multi-modality_Foundation_Models_CVPR_2024_paper.pdf)


- We construct the Q-Instruct, the first instruction tuning dataset that focuses on human queries related to low-level vision.
- We have now supported to run the Q-Instruct demos on your own device! See [local demos](https://github.com/Q-Future/Q-Instruct/tree/main/local_demos) for instructions. (Now support mplug_owl-2 only)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='https://github.com/VQAssessment/Q-Bench/raw/master/qbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-Level Vision](https://github.com/VQAssessment/Q-Bench) 
Haoning Wu\*, Zicheng Zhang\*, **Erli Zhang**\*, Chaofeng Chen, Liang Liao, Annan Wang, Chunyi Li, Wenxiu Sun, Qiong Yan, Guangtao Zhai, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/Q-Bench) [![](https://img.shields.io/github/stars/Q-Future/Q-Bench)](https://github.com/Q-Future/Q-Bench), [**Paper**](https://openreview.net/pdf?id=0V5TVt9bk0)


- We construct the Q-Bench, a benchmark to examine the progress of MLLMs on low-level visual abilities. Anticipating these large foundation models to be general-purpose intelligence that can ultimately relieve human efforts, we propose that MLLMs should achieve three important and distinct abilities: perception on low-level visual attributes, language description on low-level visual information, as well as IQA.
- Submit your model at [our project page](https://github.com/VQAssessment/Q-Bench/) to compete with existing ones!

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2023</div><img src='https://github.com/VQAssessment/MaxVQA/raw/master/figs/maxwell.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Explainable Video Quality Assessment: A Database and a Language-Prompted Approach](https://github.com/VQAssessment/MaxVQA)
  
Haoning Wu\*, **Erli Zhang**\*, Liang Liao, Chaofeng Chen, Jingwen Hou, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/MaxVQA) [![](https://img.shields.io/github/stars/VQAssessment/MaxVQA)](https://github.com/VQAssessment/MaxVQA), [**Paper**](https://dl.acm.org/doi/pdf/10.1145/3581783.3611737)
  
- We collect over two million human opinions on 13 dimensions of quality-related factors to establish the multi-dimensional Maxwell database. Furthermore, we propose the MaxVQA, a language-prompted VQA approach that modifies CLIP to better capture important quality issues as observed in our analyses. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='https://github.com/teowu/teowu.github.io/raw/main/images/dover.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Video Quality Assessment on User Generated Contents from Aesthetic and Technical Perspectives](https://github.com/VQAssessment/DOVER)
  
Haoning Wu\*, **Erli Zhang**\*, Liang Liao\*, Chaofeng Chen, Jingwen Hou, Annan Wang, Wenxiu Sun, Qiong Yan, Weisi Lin

[**GitHub**](https://github.com/VQAssessment/DOVER) [![](https://img.shields.io/github/stars/VQAssessment/DOVER)](https://github.com/VQAssessment/DOVER),  [**Paper**](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_Exploring_Video_Quality_Assessment_on_User_Generated_Contents_from_Aesthetic_ICCV_2023_paper.pdf)
  
- The proposed Disentangled Objective Video Quality Evaluator (**DOVER**) reached state-of-the-art performance (0.91 SRCC for KoNViD-1k, 0.89 SRCC for LSVQ, 0.89 SRCC for YouTube-UGC) in the UGC-VQA problem. More importantly, our subjective studies construct the first aesthetic and technical VQA database, the DIVIDE-3k, proving that UGC-VQA is jointly affected by the two perspectives.
</div>
</div>

<span class='anchor' id='-educations'></span>
# 📖 Educations
- *2024.08.01 - current*, PhD Student, Major in Biomedical Engineering, National University of Singapore
  - Supervisor: [Asst Prof Jin Yueming](https://cde.nus.edu.sg/ece/staff/jin-yueming/)
  - Research Focus: AI in Healthcare, Medical/Surgical Video Generation and Surgical Foundation Models.
- *2020.08.10 - 2024.05.30*, Undergraduate Student, Major in Computer Science, Nanyang Technological University
  - Specialization: Artificial Intelligence & Data Science
  - Final year project supervised by [Prof. Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html)
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
