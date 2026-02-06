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

I am a PhD student at the University of Manchester and the [NaCTeM](https://www.nactem.ac.uk/) group, supervised by Prof. [Sophia Ananiadou](https://research.manchester.ac.uk/en/persons/sophia.ananiadou). Previously, I worked as an NLP researcher at Tencent Technology in Shanghai. I received my Bachelor's and Master's degrees from Shanghai Jiao Tong University, supervised by Prof. Gongshen Liu. 

My research topic is **Interpreting and Improving Large Language Models -- From Internal Mechanisms to Reliable and Capable Systems**.

<span style="color:purple;">I am actively seeking Research Scientist and Applied Scientist positions starting in Fall 2026. Please feel free to contact me at zepingyu@foxmail.com if you have any suitable openings!</span>


# 📝 Research Interests

**a) Diagnosing, Auditing, and building self-improvement systems via mechanistic intepretability** 

I develop interpretability methods, tools, and systems to diagnose, audit, and improve the behavior of LLMs and multimodal LLMs.

1. **Analyzing LLMs: basic capabilities**

   - [EMNLP 2024-a](https://aclanthology.org/2024.emnlp-main.191.pdf): An attribution method for identifying important neurons.
   - [EMNLP 2024-b](https://aclanthology.org/2024.emnlp-main.193.pdf): Analyzing the information flow of arithmetic operations.
   - [EMNLP 2024-c](https://aclanthology.org/2024.emnlp-main.192.pdf): Analyzing the mechanism of in-context learning.

2. **Diagnosing LLMs: advanced capabilities**

   - [EMNLP 2025-a](https://aclanthology.org/2025.emnlp-main.567.pdf): Diagnosing why LLMs fail in latent multi-hop reasoning cases.
   - [arXiv 2024.11](https://arxiv.org/pdf/2411.10950): Debugging multimodal LLMs in VQA cases.

**b) Improving LLM Capabilities** 

Beyond diagnosis, I am interested in improving the capabilities of LLMs.

1. **Improving LLMs' latent multi-hop reasoning ability using back attention module**

   - [EMNLP 2025-a](https://aclanthology.org/2025.emnlp-main.567.pdf): Designing a new module, "back attention", to improve LLMs' latent multi-hop reasoning ability.
     
2. **Mitigating MLLMs' catastrophic forgetting problem through model merging after post-training**
   
   - [EMNLP 2025-b](https://aclanthology.org/2025.findings-emnlp.372.pdf): Designing the locate-then-merge framework for merging base LLM and post-trained LLM, to mitigate the catastrophic forgetting problem.


# 🔥 News

- *2026.02*: New survey: "Locate, Steer, and Improve: A Practical Survey of Actionable Mechanistic Interpretability in Large Language Models".

- *2025.08*: Our work "Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models" is accepted by EMNLP 2025 (main).

- *2025.08*: Our work "Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting in Multimodal LLMs" is accepted by EMNLP 2025 (findings).

- *2025.01*: New preprint: "Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing".

- *2024.12*: I've compiled paper lists of [SAE](https://github.com/zepingyu0512/awesome-SAE) and [neuron in LLMs](https://github.com/zepingyu0512/awesome-LLM-neuron).

- *2024.11*: New preprint: "Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering".

- *2024.09*: Our work "Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis" is accepted by EMNLP 2024 (main).

- *2024.09*: Our work "How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning" is accepted by EMNLP 2024 (main).

- *2024.09*: Our work "Neuron-Level Knowledge Attribution in Large Language Models" is accepted by EMNLP 2024 (main).

- *2024.04*: I've compiled a [paper list](https://github.com/zepingyu0512/awesome-llm-understanding-mechanism) for those interested in exploring the mechanisms of LLMs.


# 📝 Publications
\* Equal contribution

[Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting in Multimodal LLMs](https://aclanthology.org/2025.findings-emnlp.372.pdf)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2025 (findings)**\]

[Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models](https://aclanthology.org/2025.emnlp-main.567.pdf)

**Zeping Yu**, Yonatan Belinkov, Sophia Ananiadou \[**EMNLP 2025 (main)**\]

[Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing](https://arxiv.org/pdf/2501.14457)

**Zeping Yu**, Sophia Ananiadou \[**arxiv 2025.1**\]

[Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering](https://arxiv.org/pdf/2411.10950)

**Zeping Yu**, Sophia Ananiadou \[**arxiv 2024.11**\]

[Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024 (main)**\]

[How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning](https://zepingyu0512.github.io/in-context-mechanism.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024 (main)**\]

[Neuron-Level Knowledge Attribution in Large Language Models](https://zepingyu0512.github.io/neuron-attribution.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024 (main)**\]

[CodeCMR: Cross-modal retrieval for function-level binary source code matching](https://proceedings.neurips.cc/paper/2020/file/285f89b802bcb2651801455c86d78f2a-Paper.pdf) 

**Zeping Yu**, Wenxin Zheng, Jiaqi Wang, Qiyi Tang, Sen Nie, Shi Wu \[**NeurIPS 2020**\]

[Order matters: Semantic-aware neural networks for binary code similarity detection](https://keenlab.tencent.com/en/whitepapers/Ordermatters.pdf) 

**Zeping Yu**\*, Rui Cao\* , Qiyi Tang, Sen Nie, Junzhou Huang, Shi Wu \[**AAAI 2020**\]

[Adaptive User Modeling with Long and Short-Term Preferences for Personalized Recommendation](https://www.ijcai.org/proceedings/2019/0585.pdf) 

**Zeping Yu**, Jianxun Lian, Ahmad Mahmoody, Gongshen Liu, Xing Xie \[**IJCAI 2019**\]

[Sliced recurrent neural networks](https://arxiv.org/pdf/1807.02291.pdf) 

**Zeping Yu**, Gongshen Liu \[**COLING 2018**\]


# 📖 Educations
- *2023.09 - 2026.09 (Expected)*, PhD of Computer Science, University of Manchester.
- *2017.09 - 2020.03*, Master of Computer Science, Shanghai Jiao Tong University.
- *2013.09 - 2017.06*, Bachelor of Engineering, Shanghai Jiao Tong University.
