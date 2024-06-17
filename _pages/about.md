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

I am a PhD student studying computer science at the University of Manchester. My current research consists of three main parts. Firstly, I am interested in understanding the internal mechanisms of large language models. Secondly, I aim to design safer and more robust models based on interpretability analysis. Lastly, I hope to leverage the interpretability findings to enhance the performance of downstream tasks. I believe mechanistic interpretability is the key to AGI.

I was previously an AI researcher at Tencent Keen Lab from 2020 to 2022, where I focused on using AI algorithms for computer security. I graduated from Shanghai Jiao Tong University in 2020 with a Master's degree.

# 🔥 News

- *2024.06*: Preprint on arxiv: [How do Large Language Models Learn In-Context? Query and Key
Matrices of In-Context Heads are Two Towers for Metric Learning](https://arxiv.org/pdf/2402.02872). This work studies the internal mechanism of in-context learning.

- *2024.06*: Preprint on arxiv: [Neuron-Level Knowledge Attribution in Large Language Models](https://arxiv.org/pdf/2312.12141v3). This work is about how to identify important neurons in LLMs.

- *2024.04*: I create a [paper list](https://github.com/zepingyu0512/awesome-llm-understanding-mechanism) for new researchers interested in understanding the mechanism of LLMs. I plan to keep updating it, hopefully on a monthly basis, as I read new papers.

- *2023.09*: I start my PhD in the University of Manchester.

# 📝 Publications

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
- *2020.03 - 2022.03 (work)*, AI researcher for computer security, Tencent Keen Lab.
- *2017.09 - 2020.03*, Master, Computer Science, Shanghai Jiao Tong University.
- *2013.09 - 2017.06*, Bachelor, Computer Science, Shanghai Jiao Tong University.
