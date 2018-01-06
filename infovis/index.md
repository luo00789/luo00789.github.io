---
layout: archive
title: "信息可视化作品集"
date: 2018-01-04
image:
  teaser: 故事1.png
  feature: 故事1.png
excerpt: "tableau wokrs"
---

在此展示信息可视化作品集


<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
