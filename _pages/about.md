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

I'm a Ph.D. student at State Key Lab of CAD&CG, Zhejiang University, under the supervision of Prof. [Wei Chen](https://scholar.google.com/citations?user=EgQyYGUAAAAJ). I'm currently insterested in Trustworthy AI and LLMs.

# 🔥 News
- *2024.05*: 🎉🎉 One paper gets accepted by ACL 2024.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/sdft.png' alt="SDFT image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Self-Distillation Bridges Distribution Gap in Language Model Fine-Tuning](https://arxiv.org/abs/2402.13669)

[PDF](https://arxiv.org/pdf/2402.13669) \| [![Code](https://img.shields.io/github/stars/sail-sg/sdft?style=social&label=Repo+Stars)](https://github.com/sail-sg/sdft)

**Zhaorui Yang**, Tianyu Pang, Haozhe Feng, Han Wang, Wei Chen, Minfeng Zhu, Qian Liu

- In this work, we propose a novel fine-tuning approach to mitigate the catastrophic forgetting during the fine-tuning of language models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv:2304.06627</div><img src='images/cosda_setting.png' alt="CoSDA setting image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoSDA: Continual Source-Free Domain Adaptation](https://arxiv.org/abs/2304.06627)

[PDF](https://arxiv.org/pdf/2304.06627) \| [![Code](https://img.shields.io/github/stars/FengHZ/CoSDA?style=social&label=Repo+Stars)](https://github.com/FengHZ/CoSDA)

Haozhe Feng\*, **Zhaorui Yang\***, Hesun Chen\*, Tianyu Pang, Chao Du, Minfeng Zhu, Wei Chen, Shuicheng Yan

- In this work, we investigate the mechanism of catastrophic forgetting of previous Source-Free Domain Adaptation (SFDA) approaches. Motivated by the findings, we propose CoSDA which outperforms SOTA approaches in continuous adaptation.
</div>
</div>

# 🎖 Honors and Awards
- *2022.12* China National Scholarship (Undergraduate).
- *2021.12* China National Scholarship (Undergraduate).

# 📖 Education
- *2023.09 - Present* <br> Ph.D. student in Software Engineering at State Key Lab of CAD&CG, Zhejiang University.
- *2019.09 - 2023.06* <br> B.E. in Software Engineering, Xi'an Jiaotong University.

# 💻 Internships
None yet.
