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

I am a PhD student at University of Manchester, supervised by Prof. [Sophia Ananiadou](https://research.manchester.ac.uk/en/persons/sophia.ananiadou). I worked as an NLP researcher at Tencent Technology (Shanghai) from 2020 to 2022. I graduated from Shanghai Jiao Tong University in 2020 with a Master’s Degree, supervised by Prof. [Gongshen Liu](https://infosec.sjtu.edu.cn/DirectoryDetail.aspx?id=75), and in 2017 with a Bachelor’s Degree. 

I believe mechanistic interpretability is crucial for achieving trustworthy AGI. Moreover, it serves as a powerful tool for analyzing LLMs and informing the design of better methodologies and modules. Therefore, my research focuses on:

**a) Neuron-Level Mechanistic Interpretability of LLMs.** Identifying important neurons and understanding the neuron-level information flow in LLMs, especially on knowledge, arithmetic and reasoning tasks. My research has investigated the underlying mechanisms of [factual knowledge](https://aclanthology.org/2024.emnlp-main.191/), [arithmetic](https://aclanthology.org/2024.emnlp-main.193/), and [latent multi-hop reasoning](https://arxiv.org/pdf/2502.10835) in LLMs. Also, I have explored the mechanisms of [in-context learning](https://aclanthology.org/2024.emnlp-main.192/), [visual question answering](https://arxiv.org/pdf/2411.10950), and [gender bias](https://arxiv.org/pdf/2501.14457) in LLMs.

**b) Improving LLMs.** Applying interpretability techniques to enhance knowledge, arithmetic, and reasoning capabilities. I have designed the [model pruning](https://aclanthology.org/2024.emnlp-main.193/) method for arithmetic tasks, the [back attention](https://arxiv.org/pdf/2502.10835) module for improving latent multi-hop reasoning, and the [neuron-level model editing](https://arxiv.org/pdf/2501.14457) technique that mitigates gender bias while preserving the LLM's existing capabilities.

My email is zepingyu@foxmail.com.

# 🔥 News

- *2025.2*: New preprint: [Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models](https://arxiv.org/pdf/2502.10835). This work investigates the mechanism of latent multi-hop reasoning and propose the back attention module to enhance the latent multi-hop reasoning ability in LLMs. 

- *2025.1*: New preprint: [Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing](https://arxiv.org/pdf/2501.14457). This work investigates the mechanism of gender bias and proposes a neuron-level model editing method to reduce gender bias in LLMs without hurting the existing abilities. 

- *2024.12*: I've compiled paper lists of [SAE](https://github.com/zepingyu0512/awesome-SAE) and [neuron in LLMs](https://github.com/zepingyu0512/awesome-LLM-neuron).

- *2024.11*: New preprint: [Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering](https://arxiv.org/pdf/2411.10950). This work explores the mechanism of Llava in visual question answering. 

- *2024.09*: Our work is accepted by EMNLP 2024 (main): [Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/). This work explores the neuron-level information flow of arithmetic mechanism in LLMs and proposes a model pruning method for arithmetic tasks. 

- *2024.09*: Our work is accepted by EMNLP 2024 (main): [Neuron-Level Knowledge Attribution in Large Language Models](https://zepingyu0512.github.io/neuron-attribution.github.io/). This work introduces how to identify important neurons in LLMs, and explores the neuron-level information flow of factual knowledge mechanism. 

- *2024.09*: Our work is accepted by EMNLP 2024 (main): [How do Large Language Models Learn In-Context? Query and Key
Matrices of In-Context Heads are Two Towers for Metric Learning](https://zepingyu0512.github.io/in-context-mechanism.github.io/). This work explores the mechanism of in-context learning in LLMs.

- *2024.04*: I've compiled a [paper list](https://github.com/zepingyu0512/awesome-llm-understanding-mechanism) for those interested in exploring the mechanisms of LLMs.

# 📝 Publications

[Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models](https://arxiv.org/pdf/2502.10835)

**Zeping Yu**, Yonatan Belinkov, Sophia Ananiadou \[**arxiv: 2502.10835**\]

[Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing](https://arxiv.org/pdf/2501.14457)

**Zeping Yu**, Sophia Ananiadou \[**arxiv: 2501.14457**\]

[Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering](https://arxiv.org/pdf/2411.10950)

**Zeping Yu**, Sophia Ananiadou \[**arxiv: 2411.10950**\]

[Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024 (main)**\]

[Neuron-Level Knowledge Attribution in Large Language Models](https://zepingyu0512.github.io/neuron-attribution.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024 (main)**\]

[How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning](https://zepingyu0512.github.io/in-context-mechanism.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024 (main)**\]

[CodeCMR: Cross-modal retrieval for function-level binary source code matching](https://proceedings.neurips.cc/paper/2020/file/285f89b802bcb2651801455c86d78f2a-Paper.pdf) 

**Zeping Yu**, Wenxin Zheng, Jiaqi Wang, Qiyi Tang, Sen Nie, Shi Wu \[**NeurIPS 2020**\]

[Order matters: Semantic-aware neural networks for binary code similarity detection](https://keenlab.tencent.com/en/whitepapers/Ordermatters.pdf) 

**Zeping Yu**, Rui Cao, Qiyi Tang, Sen Nie, Junzhou Huang, Shi Wu \[**AAAI 2020**\]

[Adaptive User Modeling with Long and Short-Term Preferences for Personalized Recommendation](https://www.ijcai.org/proceedings/2019/0585.pdf) 

**Zeping Yu**, Jianxun Lian, Ahmad Mahmoody, Gongshen Liu, Xing Xie \[**IJCAI 2019**\]

[Sliced recurrent neural networks](https://arxiv.org/pdf/1807.02291.pdf) 

**Zeping Yu**, Gongshen Liu \[**COLING 2018**\]

# 📖 Educations
- *2023.09 - 2027.02 (Expected)*, PhD student, Computer Science, University of Manchester. 
- *2020.03 - 2022.03 (work)*, NLP, Tencent Technology (Shanghai).
- *2017.09 - 2020.03*, Master of Engineering, Shanghai Jiao Tong University.
- *2013.09 - 2017.06*, Bachelor of Engineering, Shanghai Jiao Tong University.
