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

I am a PhD student at the University of Manchester and the NaCTeM group, supervised by Prof. Sophia Ananiadou. Previously, I worked as an NLP researcher at Tencent Technology in Shanghai. I received my Bachelor's and Master's degrees from Shanghai Jiao Tong University, supervised by Prof. Gongshen Liu. 

My research topic is **Interpreting and Improving Large Language Models -- From Internal Mechanisms to Reliable and Capable Systems**. I develop tools and methods to explain, debug, and enhance LLMs/MLLMs — grounding predictions to diagnose failures and build more trustworthy systems.

<span style="color:purple;">I am actively seeking Research Scientist and Applied Scientist positions starting in Fall 2026. Please feel free to contact me at zepingyu@foxmail.com if you have any suitable openings!</span>


# 📝 Research Interests

**a) Mechanistic Interpretability and Diagnostic Analysis of LLMs** 

- VQALens: A system for diagnosing errors, shortcuts, and hallucinations. [[System Demo]](https://arxiv.org/pdf/2411.10950)

- Neuron-Level Attribution: Identifying important neurons for model diagnosis [[EMNLP 2024]](https://aclanthology.org/2024.emnlp-main.191.pdf)
  
- In-Context Learning Mechanisms: Understanding how LLMs perform ICL [[EMNLP 2024]](https://aclanthology.org/2024.emnlp-main.192.pdf)

**b) Mechanism-Guided Improvement of LLM Capabilities** 
  
- Back Attention: Improving latent multi-hop reasoning in LLMs [[EMNLP 2025]](https://aclanthology.org/2025.emnlp-main.567.pdf)
     
- Locate-then-Merge: Mitigating catastrophic forgetting in MLLMs [[EMNLP 2025]](https://aclanthology.org/2025.findings-emnlp.372.pdf)

- Arithmetic Reasoning via CNA: Analysis and pruning for arithmetic tasks [[EMNLP 2024]](https://aclanthology.org/2024.emnlp-main.193.pdf)


# 🔥 News

- *2026.02*: New survey: "Locate, Steer, and Improve: A Practical Survey of Actionable Mechanistic Interpretability in Large Language Models".

- *2025.08*: Two papers are accepted by EMNLP 2025.

- *2024.12*: Paper lists of [SAE](https://github.com/zepingyu0512/awesome-SAE) and [neuron](https://github.com/zepingyu0512/awesome-LLM-neuron) in LLMs.

- *2024.09*: Three papers are accepted by EMNLP 2024.

- *2024.04*: [Paper list](https://github.com/zepingyu0512/awesome-llm-understanding-mechanism) of LLM interpretability.


# 📝 Publications

### Mechanism-Guided Improvement of LLM Capabilities

---

Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting in Multimodal LLMs

- **Zeping Yu**, Sophia Ananiadou [\[**EMNLP 2025 (findings)**\]](https://aclanthology.org/2025.findings-emnlp.372.pdf)

Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models

- **Zeping Yu**, Yonatan Belinkov, Sophia Ananiadou [\[**EMNLP 2025 (main)**\]](https://aclanthology.org/2025.emnlp-main.567.pdf)

Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing

- **Zeping Yu**, Sophia Ananiadou [\[**preprint**\]](https://arxiv.org/pdf/2501.14457)

Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis

- **Zeping Yu**, Sophia Ananiadou [\[**EMNLP 2024 (main)**\]](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/)

---

### Interpretability and Diagnostic Analysis of LLMs

---

Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering

- **Zeping Yu**, Sophia Ananiadou [\[**preprint**\]](https://arxiv.org/pdf/2411.10950)

How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning

- **Zeping Yu**, Sophia Ananiadou [\[**EMNLP 2024 (main)**\]](https://zepingyu0512.github.io/in-context-mechanism.github.io/)

Neuron-Level Knowledge Attribution in Large Language Models

- **Zeping Yu**, Sophia Ananiadou [\[**EMNLP 2024 (main)**\]](https://zepingyu0512.github.io/neuron-attribution.github.io/)

---

### Earlier Work

---

CodeCMR: Cross-modal retrieval for function-level binary source code matching

- **Zeping Yu**, Wenxin Zheng, Jiaqi Wang, Qiyi Tang, Sen Nie, Shi Wu [\[**NeurIPS 2020**\]](https://proceedings.neurips.cc/paper/2020/file/285f89b802bcb2651801455c86d78f2a-Paper.pdf) 

Order matters: Semantic-aware neural networks for binary code similarity detection

- **Zeping Yu**\*, Rui Cao\* , Qiyi Tang, Sen Nie, Junzhou Huang, Shi Wu [\[**AAAI 2020**\]](https://keenlab.tencent.com/en/whitepapers/Ordermatters.pdf) 

Adaptive User Modeling with Long and Short-Term Preferences for Personalized Recommendation

- **Zeping Yu**, Jianxun Lian, Ahmad Mahmoody, Gongshen Liu, Xing Xie [\[**IJCAI 2019**\]](https://www.ijcai.org/proceedings/2019/0585.pdf) 

Sliced recurrent neural networks

- **Zeping Yu**, Gongshen Liu [\[**COLING 2018**\]](https://arxiv.org/pdf/1807.02291.pdf) 


# 📖 Educations
- *2023.09 - 2026.09 (Expected)*, PhD of Computer Science, University of Manchester.
- *2017.09 - 2020.03*, Master of Computer Science, Shanghai Jiao Tong University.
- *2013.09 - 2017.06*, Bachelor of Engineering, Shanghai Jiao Tong University.
