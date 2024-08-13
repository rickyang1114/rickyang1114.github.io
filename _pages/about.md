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

<span class="anchor" id="about-me"></span>

I'm a Ph.D. student at State Key Lab of CAD&CG, Zhejiang University <img src="../files/logos/zju_blue.svg" style="width: 6em;">, under the supervision of Prof. [Wei Chen](https://scholar.google.com/citations?user=EgQyYGUAAAAJ). I'm currently insterested in Trustworthy AI and LLMs.

<!-- I have a citation of <strong><span id='total_cit'></span></strong>. -->

# 🔥 News
- *2024.05*: 🎉🎉 One paper gets accepted by ACL 2024 <img src="../files/logos/acl_2024.png" style="width: 6em;">.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src="../files/sdft/sdft.png" alt="SDFT image" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Self-Distillation Bridges Distribution Gap in Language Model Fine-Tuning](https://aclanthology.org/2024.acl-long.58)

<a href="https://aclanthology.org/2024.acl-long.58.pdf" style="text-decoration: none; color: #a00" target="_blank"><i class="iconfont icon-filepdf" aria-hidden="true"></i> PDF</a> \| [![Code](https://img.shields.io/github/stars/sail-sg/sdft?style=social&label=Repo+Stars)](https://github.com/sail-sg/sdft) \| <a href="../files/sdft/sdft_poster.pdf" style="text-decoration: none; color: #a00" target="_blank"><i class="iconfont icon-poster"></i> Poster</a> \| <a href="../files/sdft/sdft_slide.pdf" style="text-decoration: none; color: #a00" target="_blank"><i class="iconfont icon-filepowerpoint" aria-hidden="true"></i> Slides</a>

<!-- This is effective only if <span id='total_cit'></span> exists. -->
<!-- <span class="show_paper_citations" data="AGjSco8AAAAJ:qjMakFHDy7sC"></span> -->

**Zhaorui Yang**, Tianyu Pang, Haozhe Feng, Han Wang, Wei Chen, Minfeng Zhu, Qian Liu

- In this work, we propose a novel fine-tuning approach to mitigate the catastrophic forgetting during the fine-tuning of language models.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">arxiv:2304.06627</div><img src="../files/cosda/cosda_setting.png" alt="CoSDA setting image" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[CoSDA: Continual Source-Free Domain Adaptation](https://arxiv.org/abs/2304.06627)

<a href="https://arxiv.org/pdf/2304.06627" style="text-decoration: none; color: #a00" target="_blank"><i class="iconfont icon-filepdf" aria-hidden="true"></i> PDF</a> \| [![Code](https://img.shields.io/github/stars/FengHZ/CoSDA?style=social&label=Repo+Stars)](https://github.com/FengHZ/CoSDA)

Haozhe Feng\*, **Zhaorui Yang\***, Hesun Chen\*, Tianyu Pang, Chao Du, Minfeng Zhu, Wei Chen, Shuicheng Yan

- In this work, we investigate the mechanism of catastrophic forgetting of previous Source-Free Domain Adaptation (SFDA) approaches. Motivated by the findings, we propose CoSDA which outperforms SOTA approaches in continuous adaptation.
</div>
</div>

# 🎖 Honors and Awards
- *2022.12* China National Scholarship (Undergraduate).
- *2021.12* China National Scholarship (Undergraduate).

# 📖 Education
- *2023.09 - **Present*** <br> Ph.D. student in Software Engineering at State Key Lab of CAD&CG, Zhejiang University <img src="../files/logos/zju_blue.svg" style="width: 6em;">.
- *2019.09 - 2023.06* <br> B.E. in Software Engineering, Xi'an Jiaotong University <img src="../files/logos/xjtu.png" style="width: 6em;">.

# 💻 Internships
None yet.

<div class="page__footer-copyright">&copy; {{ site.time | date: "%Y" }} {{ site.title }}. Last Modified on:<img src="../files/icons/clock.svg" style="height: 1em; margin-left: 0.5em"> {{ site.time | date: "%Y-%m-%d" }}</div>

<!-- <div class="page__footer-copyright">&copy; {{ site.time | date: "%Y" }} {{ site.title }}. Last Modified at: {{ page.last_modified_at | date: "%Y-%m-%d %H:%M:%S"}}</div> -->
