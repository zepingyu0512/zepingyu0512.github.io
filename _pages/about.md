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

<span style="color:purple;">I am actively seeking (Applied) Research Scientist position starting in Fall 2026. Please feel free to contact me at zepingyu@foxmail.com if you have any suitable openings!</span>

# 📝 Research Interests

My research lies in understanding the inner mechanisms of LLMs and multimodal LLMs (MLLMs). I believe deeper understanding of these models can inform the design of more robust and efficient architectures, and guide practical techniques to improve model performance. Moreover, as we move toward AGI and ASI, the inability to understand how these models make decisions poses a serious risk—without interpretability, we may lose control over increasingly powerful systems. In particular, I work on:

**a) Understanding LLMs and MLLMs' internal mechanisms through mechanistic interpretability** 

I develop and apply interpretability techniques to investigate how LLMs and MLLMs perform a wide range of tasks using a shared architecture. Through these efforts, I aim to establish principled insights that inform and guide the future development of these models.

1. **Fundamental capabilities: knowledge, arithmetic, in-context learning**

   - [EMNLP 2024-a](https://aclanthology.org/2024.emnlp-main.191.pdf): Understanding the mechanism of factual knowledge in LLMs.
   - [EMNLP 2024-b](https://aclanthology.org/2024.emnlp-main.193.pdf): Understanding the mechanism of arithmetic operations in LLMs.
   - [EMNLP 2024-c](https://aclanthology.org/2024.emnlp-main.192.pdf): Understanding the mechanism of in-context learning in LLMs.

2. **Advanced capabilities: latent multi-hop reasoning, visual question answering**

   - [EMNLP 2025-a](https://arxiv.org/pdf/2502.10835): Understanding why LLMs fail on latent multi-hop reasoning.
   - [arXiv 2024.11](https://arxiv.org/pdf/2411.10950): Understanding the mechanism of visual question answering in MLLMs.

**b) Enhancing LLMs and MLLMs' capabilities in post-training** 

Beyond understanding model behavior, I aim to improve the performance and reliability of LLMs and MLLMs. My current efforts focus on three directions:

1. **Improving LLMs' latent multi-hop reasoning ability during post-training**

   - [EMNLP 2025-a](https://arxiv.org/pdf/2502.10835): Designing a new module, ""back attention"", to improve LLMs' latent multi-hop reasoning ability during post-training.
     
2. **Mitigating LLMs' catastrophic forgetting problem through model merging after post-training**
   
   - [EMNLP 2025-b](https://arxiv.org/pdf/2505.16703): Designing the locate-then-merge framework for merging base LLM and post-trained LLM, to mitigate the catastrophic forgetting problem in post-training.

3. **Creating interpretability tools to help users understand and trust LLM generations**

   - [EMNLP 2025-a](https://arxiv.org/pdf/2502.10835): Creating an interpretability tool for analyzing neuron-level information flow and understanding why LLMs cannot perform latent multihop reasoning well.
   - [arXiv 2024.11](https://arxiv.org/pdf/2411.10950): Creating an interpretability tool for identifying important image patches and understanding why MLLMs generate false answers in visual question answering.


# 🔥 News

- *2025.08*: Our work is accepted by EMNLP 2025 (main): Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models

- *2025.08*: Our work is accepted by EMNLP 2025 (findings): Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting in Multimodal LLMs

- *2025.01*: New preprint: Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing

- *2024.12*: I've compiled paper lists of [SAE](https://github.com/zepingyu0512/awesome-SAE) and [neuron in LLMs](https://github.com/zepingyu0512/awesome-LLM-neuron).

- *2024.11*: New preprint: Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering

- *2024.09*: Our work is accepted by EMNLP 2024 (main): Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis

- *2024.09*: Our work is accepted by EMNLP 2024 (main): How do Large Language Models Learn In-Context? Query and Key
Matrices of In-Context Heads are Two Towers for Metric Learning

- *2024.09*: Our work is accepted by EMNLP 2024 (main): Neuron-Level Knowledge Attribution in Large Language Models

- *2024.04*: I've compiled a [paper list](https://github.com/zepingyu0512/awesome-llm-understanding-mechanism) for those interested in exploring the mechanisms of LLMs.

# 📝 Publications
\* Equal contribution

[Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting in Multimodal LLMs](https://arxiv.org/pdf/2505.16703)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2025 (findings)**\]

[Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models](https://arxiv.org/pdf/2502.10835)

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
- *2023.09 - 2026.07 (Expected)*, PhD of Computer Science, University of Manchester.
- *2017.09 - 2020.03*, Master of Computer Science, Shanghai Jiao Tong University.
- *2013.09 - 2017.06*, Bachelor of Engineering, Shanghai Jiao Tong University.
