---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Feasible Reachable Policy Iteration**\
Shentao Qin\*, Yujie Yang\*, Yao Mu\*, Jie Li, Wenjun Zou, Shengbo Eben Li, Jingliang Duan\
*International Conference on Machine Learning (ICML)*, 2024\
[paper](https://openreview.net/forum?id=ks8qSwkkuZ)
[website](https://jackqin007.github.io/FRPI/)|
[code](https://github.com/JackQin007/FRPI)