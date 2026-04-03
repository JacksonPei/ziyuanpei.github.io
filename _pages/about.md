---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /_config.yml
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a second-year master's student at the Data Driven Software Technology (DDST) Laboratory of Shanghai Jiao Tong University, focusing on RAG, Context Engineering, and LLM-based applications. Google Scholar: [Follow Me!](https://scholar.google.com/citations?view_op=list_works&hl=zh-CN&user=F1DUfAMAAAAJ)

# 🔥 News
- *2025.09*: &nbsp;🎉🎉 Our paper accepted to NeurIPS 2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/neurips2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Influence Guided Context Selection for Effective Retrieval-Augmented Generation**

Jiale Deng, Yanyan Shen, **Ziyuan Pei**, Youmin Chen, Linpeng Huang

[**Project**]([https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=F1DUfAMAAAAJ&citation_for_view=F1DUfAMAAAAJ:YsMSGLbcyi4C)) <strong><span class='show_paper_citations' data='F1DUfAMAAAAJ:YsMSGLbcyi4C'></span></strong>
- Proposes a method for automatic context document selection in the RAG scenario called CSM. Specifically, we introduce the use of Contextual Influence (CI) values to measure the usefulness of contexts. Two training methods, Supervised training and end-to-end training, are employed to train the CSM model to predict context CI values. During inference, CSM predicts the CI values for all contexts and selects those with CI values greater than 0. We provide extensive experimental evidence demonstrating the effectiveness of CSM. 
</div>
</div>

# 📖 Educations
- *2024.09 - 2027.03 (now)*, Master Student, Shanghai Jiao Tong University. 
- *2020.09 - 2024.06*, Undergraduate Student, Dalian University of Technology. 

