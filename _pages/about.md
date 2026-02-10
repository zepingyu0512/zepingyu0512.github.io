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

I am a PhD researcher at the University of Manchester and the NaCTeM group, supervised by Prof. Sophia Ananiadou. Previously, I worked as an NLP researcher at Tencent Technology in Shanghai. I received my Bachelor's and Master's degrees from Shanghai Jiao Tong University, supervised by Prof. Gongshen Liu. 

My research topic is **Interpreting and Improving Large Language Models -- From Internal Mechanisms to Reliable and Capable Systems**. My primary methodology follows a diagnose-and-improve paradigm: I first analyze why LLMs fail, and then design targeted methods or architectural modules to enhance their capabilities, for example in latent multi-hop reasoning and catastrophic forgetting.

<span style="color:purple;">I am actively seeking Research Scientist and Applied Scientist positions starting in Fall 2026. Please feel free to contact me at zepingyu@foxmail.com if you have any suitable openings!</span>


# 📝 Research Interests

My research aims to improve the capabilities of LLMs by analyzing their internal mechanisms at the token and neuron levels, and leveraging this understanding to design more reliable and effective systems.

**a) Understanding and Diagnosing LLMs through Mechanistic Interpretability** 

- VQALens: Diagnosing errors, shortcuts, and hallucinations in MLLMs. [[System Demo]](https://www.youtube.com/watch?v=F5EYcGfqaQU)

- Neuron-Level Attribution: Identifying important neurons for model diagnosis. [[EMNLP 2024]](https://aclanthology.org/2024.emnlp-main.191.pdf)
  
- In-Context Learning: Understanding how LLMs perform in-context learning. [[EMNLP 2024]](https://aclanthology.org/2024.emnlp-main.192.pdf)

**b) Enhancing LLM Capabilities through Mechanistic Understanding** 
  
- Back Attention: Improving latent multi-hop reasoning in LLMs. [[EMNLP 2025]](https://aclanthology.org/2025.emnlp-main.567.pdf)
     
- Model Merging: Mitigating catastrophic forgetting in MLLMs. [[EMNLP 2025]](https://aclanthology.org/2025.findings-emnlp.372.pdf)

- Model Pruning: Improving arithmetic reasoning through model pruning. [[EMNLP 2024]](https://aclanthology.org/2024.emnlp-main.193.pdf)

- Model Editing: Reducing gender bias in LLMs via model editing. [[Preprint]](https://arxiv.org/pdf/2501.14457)


# 🔥 News

- *2026.02*: New survey: "Locate, Steer, and Improve: A Practical Survey of Actionable Mechanistic Interpretability in Large Language Models".

- *2025.08*: Two papers are accepted by EMNLP 2025.

- *2024.12*: Paper lists of [SAE](https://github.com/zepingyu0512/awesome-SAE) and [neuron](https://github.com/zepingyu0512/awesome-LLM-neuron) in LLMs.

- *2024.09*: Three papers are accepted by EMNLP 2024.

- *2024.04*: [Paper list](https://github.com/zepingyu0512/awesome-llm-understanding-mechanism) of LLM interpretability.


# 📝 Publications

### Mechanism-Guided Improvement of LLM Capabilities

---

\[P1\] Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting

- **Zeping Yu**, Sophia Ananiadou [\[**EMNLP 2025 (Findings)**\]](https://aclanthology.org/2025.findings-emnlp.372.pdf)

\[P2\] Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models

- **Zeping Yu**, Yonatan Belinkov, Sophia Ananiadou [\[**EMNLP 2025 (Main)**\]](https://aclanthology.org/2025.emnlp-main.567.pdf)

\[P3\] Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing

- **Zeping Yu**, Sophia Ananiadou [\[**preprint**\]](https://arxiv.org/pdf/2501.14457)

\[P4\] Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis

- **Zeping Yu**, Sophia Ananiadou [\[**EMNLP 2024 (Main)**\]](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/)

---

### Interpretability and Diagnostic Analysis of LLMs

---

\[P5\] Understanding Multimodal LLMs: the Mechanistic Interpretability of LLaVA in VQA

- **Zeping Yu**, Sophia Ananiadou [\[**preprint**\]](https://arxiv.org/pdf/2411.10950)

\[P6\] Neuron-Level Knowledge Attribution in Large Language Models

- **Zeping Yu**, Sophia Ananiadou [\[**EMNLP 2024 (Main)**\]](https://zepingyu0512.github.io/neuron-attribution.github.io/)

\[P7\] How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning

- **Zeping Yu**, Sophia Ananiadou [\[**EMNLP 2024 (Main)**\]](https://zepingyu0512.github.io/in-context-mechanism.github.io/)

---

### Earlier Work

---

\[E1\] CodeCMR: Cross-modal retrieval for function-level binary source code matching

- **Zeping Yu**, Wenxin Zheng, Jiaqi Wang, Qiyi Tang, Sen Nie, Shi Wu [\[**NeurIPS 2020**\]](https://proceedings.neurips.cc/paper/2020/file/285f89b802bcb2651801455c86d78f2a-Paper.pdf) 

\[E2\] Order matters: Semantic-aware neural networks for binary code similarity detection

- **Zeping Yu**\*, Rui Cao\* , Qiyi Tang, Sen Nie, Junzhou Huang, Shi Wu [\[**AAAI 2020**\]](https://keenlab.tencent.com/en/whitepapers/Ordermatters.pdf) 

\[E3\] Adaptive User Modeling with Long and Short-Term Preferences for Personalized Recommendation

- **Zeping Yu**, Jianxun Lian, Ahmad Mahmoody, Gongshen Liu, Xing Xie [\[**IJCAI 2019**\]](https://www.ijcai.org/proceedings/2019/0585.pdf) 

\[E4\] Sliced recurrent neural networks

- **Zeping Yu**, Gongshen Liu [\[**COLING 2018**\]](https://arxiv.org/pdf/1807.02291.pdf) 


# 📖 Educations
- *2023.09 - 2026.09 (Expected)*, PhD of Computer Science, University of Manchester.
- *2017.09 - 2020.03*, Master of Computer Science, Shanghai Jiao Tong University.
- *2013.09 - 2017.06*, Bachelor of Engineering, Shanghai Jiao Tong University.
