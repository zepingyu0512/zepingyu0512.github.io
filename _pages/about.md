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

I am a PhD student at the University of Manchester, supervised by Prof. [Sophia Ananiadou](https://research.manchester.ac.uk/en/persons/sophia.ananiadou). Previously, I worked as an NLP researcher at Tencent Technology. I received my Bachelor's and Master's degrees from Shanghai Jiao Tong University, supervised by Prof. Gongshen Liu.

My research lies in understanding the inner mechanisms of LLMs and multimodal LLMs (MLLMs). I believe deeper understanding of these models can inform the design of more robust, controllable, and efficient architectures, and guide practical techniques to improve model performance. In particular, I work on:

**a) Mechanistic interpretability of LLMs and MLLMs.** 

I develop and apply interpretability techniques to investigate how LLMs and MLLMs perform a wide range of tasks using a shared architecture. Through these efforts, I aim to establish principled insights that inform and guide the future development of these models.

1. **Understanding fundamental abilities**
   
   I analyze how core skills emerge in LLMs, including factual knowledge, arithmetic reasoning, and in-context learning.

   - [EMNLP 2024](https://aclanthology.org/2024.emnlp-main.191.pdf): Understanding the mechanism of factual knowledge.
   - [EMNLP 2024](https://aclanthology.org/2024.emnlp-main.193.pdf): Understanding the mechanism of arithmetic operations.
   - [EMNLP 2024](https://aclanthology.org/2024.emnlp-main.192.pdf): Understanding the mechanism of in-context learning.

2. **Understanding higher-order capabilities**
   
   I study more complex behaviors in LLMs and MLLMs, such as latent multi-hop reasoning and visual question answering.

   - [arXiv 2024.11](https://arxiv.org/pdf/2411.10950): Understanding the mechanism of visual question answering in MLLMs.
   - [arXiv 2025.02](https://arxiv.org/pdf/2502.10835): Understanding why LLMs fail on latent multi-hop reasoning.

**b) Improving LLM and MLLM capabilities.** 

Beyond understanding model behavior, I aim to improve the performance and reliability of LLMs and MLLMs. My current efforts focus on three directions:

1. **Creating interpretability tools to help users understand and trust LLM outputs**

   I build interpretability tools that expose how LLMs and MLLMs reason internally, helping users understand the rationale behind model responses. These tools aim to improve transparency and increase user confidence in the model’s outputs, especially in high-stakes or ambiguous scenarios.

   - [arXiv 2024.11](https://arxiv.org/pdf/2411.10950): Interpretability tool for visual question answering.
   - [arXiv 2025.02](https://arxiv.org/pdf/2502.10835): Interpretability tool for analyzing neuron-level information flow.

2. **Analyzing model failures to inform architectural design**

   I use interpretability techniques to analyze how and why models fail, guiding the design of new architectures, modules, and strategies.

   - [arXiv 2025.02](https://arxiv.org/pdf/2502.10835): A new module, back attention, to improve the latent multi-hop reasoning ability.
     
3. **Improving LLM/MLLM capability via model editing and model merging**

   I develop methods to identify specific neurons or weights responsible for different capabilities, enabling targeted parameter change such as model editing and merging.

   - [arXiv 2025.01](https://arxiv.org/pdf/2501.14457): Locate-then-edit for neuron-level model editing, to reduce gender bias and improve general ability.
   - [arXiv 2025.05](https://arxiv.org/pdf/2505.16703): Locate-then-merge for post-training (visual instruction tuning), to mitigate catastrophic forgetting and improve multimodal ability.

I am actively seeking a Research Scientist position starting in late 2026 or early 2027. Please feel free to contact me at **zepingyu@foxmail.com** if you are interested in working together.

# 🔥 News

- *2025.5*: New preprint: [Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting in Multimodal LLMs](https://arxiv.org/pdf/2505.16703). This work investigates how to mitigate the catastrophic forgetting problem after visual instruction tuning in MLLMs.

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
\* Equal contribution

[Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting in Multimodal LLMs](https://arxiv.org/pdf/2505.16703)

**Zeping Yu**, Sophia Ananiadou \[**arxiv 2025.5**\]

[Back Attention: Understanding and Enhancing Multi-Hop Reasoning in Large Language Models](https://arxiv.org/pdf/2502.10835)

**Zeping Yu**, Yonatan Belinkov, Sophia Ananiadou \[**arxiv 2025.2**\]

[Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing](https://arxiv.org/pdf/2501.14457)

**Zeping Yu**, Sophia Ananiadou \[**arxiv 2025.1**\]

[Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering](https://arxiv.org/pdf/2411.10950)

**Zeping Yu**, Sophia Ananiadou \[**arxiv 2024.11**\]

[Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024 (main)**\]

[Neuron-Level Knowledge Attribution in Large Language Models](https://zepingyu0512.github.io/neuron-attribution.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024 (main)**\]

[How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning](https://zepingyu0512.github.io/in-context-mechanism.github.io/)

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
- *2017.09 - 2020.02*, Master of Engineering, Shanghai Jiao Tong University.
- *2013.09 - 2017.06*, Bachelor of Engineering, Shanghai Jiao Tong University.
