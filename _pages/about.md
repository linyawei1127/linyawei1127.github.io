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

I am a master's student in the College of Computer Science and Technology at National University of Defense Technology (NUDT), jointly advised by [Prof.LiuXinwang](https://xinwangliu.github.io/). Before joining NUDT, I received my B.S. in the School of Artificial Intelligence at Hebei University of Technology.

My research interest includes AI Safety, such as LLM Fairness and Graph Adversarial Robustness.

# 🔥 News
- *2022.02*: &nbsp;🎉🎉 He won the Outstanding Graduate of Hebei Province.

# 📝 Publications 

# 🎖 Honors and Awards
- *2025.05* Outstanding Graduate of Hebei Province. 
- *2021.09* He won the National Scholarship. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, National University of Defense Technology, the College of Computer Science and Technology, Changsha, China. 
- *2021.09 - 2025.06*, Hebei University of Technology, the School of Artificial Intelligence, Tianjin, China. 

# 💬 Invited Talks

# 💻 Internships

# 📚 Read Papers
This section contains my reading notes and summaries of important research papers in AI Safety, LLM Fairness, and Graph Adversarial Robustness.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2024</div><img src='/images/trimmed_use_case_framework.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Actionable Framework For Assessing Bias and  Fairness in Large Language Model Use Cases](assets/pdf/2024_llm_fairness.pdf)

Dylan Bouchard

[**Abstarct**]
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- 本文提出了一个针对大型语言模型（LLMs）偏见和公平性评估的决策框架，通过将偏见风险映射到LLM用例分类法中，帮助从业者在特定应用场景中选择合适的偏见和公平性评估指标。该框架在用例层面同时考虑提示特定风险和模型特定风险，仅基于LLM输出进行计算，具有很强的实用性，并配套开发了Python工具包LangFair来简化实施。 
</div>
</div>

