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


# 📖 About Me

I received my PhD in Computer Science from the University of Manchester, supervised by Prof. Sophia Ananiadou. Previously, I worked as a Research Scientist at Tencent in Shanghai. I received both my Bachelor's and Master's degrees from Shanghai Jiao Tong University, where I was supervised by Prof. Gongshen Liu.

My research focuses on understanding and improving large language models. I follow a diagnose-and-improve paradigm. My research interests include mechanistic interpretability, large language models, and multimodal large language models. In particular, I am interested in understanding how model capabilities emerge, identifying the mechanisms behind their successes and failures, and translating mechanistic insights into more capable, reliable, and effective AI systems.


# 📝 Publications

- Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models

  **Zeping Yu**, Yonatan Belinkov, Sophia Ananiadou **EMNLP 2025 (Main)**

- Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting

  **Zeping Yu**, Sophia Ananiadou **EMNLP 2025 (Findings)**

- Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis
 
  **Zeping Yu**, Sophia Ananiadou **EMNLP 2024 (Main)**

- Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing

  **Zeping Yu**, Sophia Ananiadou **preprint**

- Neuron-Level Knowledge Attribution in Large Language Models

  **Zeping Yu**, Sophia Ananiadou **EMNLP 2024 (Main)**

- How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning

  **Zeping Yu**, Sophia Ananiadou **EMNLP 2024 (Main)**

- Understanding Multimodal LLMs: the Mechanistic Interpretability of LLaVA in VQA

  **Zeping Yu**, Sophia Ananiadou **preprint**

- CodeCMR: Cross-modal retrieval for function-level binary source code matching

  **Zeping Yu**, Wenxin Zheng, Jiaqi Wang, Qiyi Tang, Sen Nie, Shi Wu **NeurIPS 2020**

- Order matters: Semantic-aware neural networks for binary code similarity detection

  **Zeping Yu**\*, Rui Cao\* , Qiyi Tang, Sen Nie, Junzhou Huang, Shi Wu **AAAI 2020**

- Adaptive User Modeling with Long and Short-Term Preferences for Personalized Recommendation

  **Zeping Yu**, Jianxun Lian, Ahmad Mahmoody, Gongshen Liu, Xing Xie **IJCAI 2019**
