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

I am a second-year PhD student at the University of Manchester (started in September 2023), supervised by Prof. [Sophia Ananiadou](https://research.manchester.ac.uk/en/persons/sophia.ananiadou). I was previously an AI researcher at Tencent from 2020 to 2022, where I focused on DL4code. I graduated from Shanghai Jiao Tong University in 2020 with a Master’s Degree, supervised by Prof. [Gongshen Liu](https://infosec.sjtu.edu.cn/DirectoryDetail.aspx?id=75), and in 2017 with a Bachelor’s Degree. 

I believe mechanistic interpretability is the key to trustworthy AGI. Currently, I am interested in: 

**a)** Understanding the internal mechanisms of LLMs. I have explored the mechanisms of [factual knowledge](https://zepingyu0512.github.io/neuron-attribution.github.io/), [in-context learning](https://zepingyu0512.github.io/in-context-mechanism.github.io/), [arithmetic](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/) in LLMs, and [visual question answering](https://arxiv.org/pdf/2411.10950) in multimodal-LLMs.

**b)** Leveraging interpretability insights to identify flaws of LLMs' structures, and designing safer and more effective methods/models.

Please feel free to contact me via zepingyu@foxmail.com for discussions.

# 🔥 News

- *2024.11*: New preprint: [Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering](https://arxiv.org/pdf/2411.10950). This work explores the mechanism of Llava in visual question answering. \[[CODE](https://github.com/zepingyu0512/llava-mechanism/tree/main)\]

- *2024.09*: Our work is accepted by EMNLP 2024 (main): [Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/). This work explores the mechanism of arithmetic ability in LLMs. \[[CODE](https://github.com/zepingyu0512/arithmetic-mechanism)\]

- *2024.09*: Our work is accepted by EMNLP 2024 (main): [Neuron-Level Knowledge Attribution in Large Language Models](https://zepingyu0512.github.io/neuron-attribution.github.io/). This work introduces how to identify important neurons in LLMs. \[[CODE](https://github.com/zepingyu0512/neuron-attribution)\]

- *2024.09*: Our work is accepted by EMNLP 2024 (main): [How do Large Language Models Learn In-Context? Query and Key
Matrices of In-Context Heads are Two Towers for Metric Learning](https://zepingyu0512.github.io/in-context-mechanism.github.io/). This work explores the mechanism of in-context learning in LLMs. \[[CODE](https://github.com/zepingyu0512/in-context-mechanism)\]

- *2024.04*: I create a [paper list](https://github.com/zepingyu0512/awesome-llm-understanding-mechanism) for people interested in understanding the mechanism of LLMs. 

- *2023.09*: I start my PhD in the University of Manchester.

# 📝 Publications

[Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024**\]

[Neuron-Level Knowledge Attribution in Large Language Models](https://zepingyu0512.github.io/neuron-attribution.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024**\]

[How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning](https://zepingyu0512.github.io/in-context-mechanism.github.io/)

**Zeping Yu**, Sophia Ananiadou \[**EMNLP 2024**\]

[CodeCMR: Cross-modal retrieval for function-level binary source code matching](https://proceedings.neurips.cc/paper/2020/file/285f89b802bcb2651801455c86d78f2a-Paper.pdf) 

**Zeping Yu**, Wenxin Zheng, Jiaqi Wang, Qiyi Tang, Sen Nie, Shi Wu \[**NeurIPS 2020**\]

[Order matters: Semantic-aware neural networks for binary code similarity detection](https://keenlab.tencent.com/en/whitepapers/Ordermatters.pdf) 

**Zeping Yu**, Rui Cao, Qiyi Tang, Sen Nie, Junzhou Huang, Shi Wu \[**AAAI 2020**\]

[Adaptive User Modeling with Long and Short-Term Preferences for Personalized Recommendation](https://www.ijcai.org/proceedings/2019/0585.pdf) 

**Zeping Yu**, Jianxun Lian, Ahmad Mahmoody, Gongshen Liu, Xing Xie \[**IJCAI 2019**\]

[Sliced recurrent neural networks](https://arxiv.org/pdf/1807.02291.pdf) 

**Zeping Yu**, Gongshen Liu \[**COLING 2018**\]

# 📖 Educations
- *2023.09 - now*, PhD student, Computer Science, the University of Manchester. 
- *2020.03 - 2022.03 (work)*, DL4code, Tencent.
- *2017.09 - 2020.03*, Master of Engineering, Shanghai Jiao Tong University.
- *2013.09 - 2017.06*, Bachelor of Engineering, Shanghai Jiao Tong University.
