---
layout: archive
title: "信息可视化作品集"
date: 2018-01-04
excerpt: "tableau wokrs"
image: 
  feature: 故事.png
  teaser: 故事.png
---

在此展示信息可视化作品集

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
