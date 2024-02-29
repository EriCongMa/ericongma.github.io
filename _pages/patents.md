---
layout: archive
title: "Patents"
permalink: /patents/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}




1. 发明专利：CN114626392B, 端到端文本图像翻译模型训练方法, 授权时间：2023.02.21
2. 发明专利：CN113011202B, 基于多任务训练的端到端图像文本翻译方法、系统、装置， 授权时间：2023.07.25

---

