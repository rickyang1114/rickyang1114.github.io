---
permalink: /
title: ""
excerpt: "Zhaorui Yang — Ph.D. student at Zhejiang University, working on language models, AI agents, and reinforcement learning."
author_profile: true
last_updated: 2026-09-09
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I'm a Ph.D. student in Software Engineering at State Key Lab of CAD&CG, Zhejiang University, under the supervision of Prof. [Wei Chen](https://scholar.google.com/citations?user=EgQyYGUAAAAJ).

I'm currently interested in language models and agents. I'm currently an intern with the Qwen Foundation Model Team at Alibaba.

# 📖 Education
- *2023.09 - 2028.06 (Expected)* <br> Ph.D. student in Software Engineering in Zhejiang University <img src="../files/logos/zju_blue.svg" alt="Zhejiang University" style="width: 6em;">. Supervisor: [Wei Chen](https://scholar.google.com/citations?user=EgQyYGUAAAAJ).
- *2019.09 - 2023.06* <br> B.E. in Software Engineering, Xi'an Jiaotong University <img src="../files/logos/xjtu.png" alt="Xi’an Jiaotong University" style="width: 6em;">.

# 📝 Publications

{% for paper in site.data.publications %}
<div class="paper-box">
{% if paper.image %}
<div class="paper-box-image"><div><div class="badge">{{ paper.venue }}{% if paper.distinction %} ({{ paper.distinction }}){% endif %}</div><img src="{{ paper.image | relative_url }}" alt="{{ paper.image_alt }}" width="100%"></div></div>
{% endif %}
<div class="paper-box-text"{% unless paper.image %} style="max-width: 100%; padding-left: 0;"{% endunless %}>
{% unless paper.image %}<p><strong>{{ paper.venue }}</strong></p>{% endunless %}
<p><a href="{{ paper.url }}">{{ paper.title }}</a></p>
<p>
{% for link in paper.links %}
<a href="{% if link.url contains '://' %}{{ link.url }}{% else %}{{ link.url | relative_url }}{% endif %}"{% unless link.label == 'Code' %} style="text-decoration: none; color: #a00"{% endunless %}>
{% if link.label == 'Paper' %}<i class="iconfont icon-filepdf" aria-hidden="true"></i> PDF{% elsif link.label == 'Code' and paper.repository %}<img src="https://img.shields.io/github/stars/{{ paper.repository }}?style=social&amp;label=Repo+Stars" alt="Code">{% elsif link.label == 'Poster' %}<i class="iconfont icon-poster" aria-hidden="true"></i> Poster{% elsif link.label == 'Slides' %}<i class="iconfont icon-filepowerpoint" aria-hidden="true"></i> Slides{% else %}{{ link.label }}{% endif %}</a>{% unless forloop.last %} | {% endunless %}
{% endfor %}
</p>
<p>{{ paper.authors }}</p>
<!-- {% if paper.citations %}<p><small>{{ paper.citations }} citations (September 2026).</small></p>{% endif %} -->
<ul><li>{{ paper.summary }}</li></ul>
</div>
</div>

{% endfor %}

# 💻 Internships
- *2026.04 - Present*: Qwen Foundation Model Team, ATH, Alibaba <img src="../files/logos/qwen.png" alt="Qwen" style="width: 6em;"> <br> Contributed to the development of the search teacher model for **Qwen 3.8 Max**, focusing on evaluation and trajectory analysis pipelines, long-horizon training data construction, and large-scale SFT and RL experiments on hundreds of H200 GPUs. Currently working on reinforcement learning for Qwen’s cyber model, targeting long-horizon CTF and exploitation tasks studied by frontier AI labs.
- *2025.07 - 2026.03*: Data Computing Platform Department, TEG, Tencent <img src="../files/logos/tencent.png" alt="Tencent" style="width: 6em;"> <br> Led [ProSPy](https://arxiv.org/abs/2606.05836) from problem formulation and system design to experimentation. It combines data profiling, SQL retrieval, and Python analysis for enterprise Text-to-SQL, reached **No. 2 on Spider 2.0-Lite at submission**. Its successor, Tianqiong Data Agent, ranks **No. 1** now.

# 🎖 Honors and Awards
- *2022.12* China National Scholarship (Undergraduate).
- *2021.12* China National Scholarship (Undergraduate).

<div class="page__footer-copyright">&copy; {{ site.time | date: "%Y" }} {{ site.title }}. Last Modified on:<img src="../files/icons/clock.svg" alt="" style="height: 1em; margin-left: 0.5em"> {{ page.last_updated | date: "%Y-%m-%d" }}</div>
