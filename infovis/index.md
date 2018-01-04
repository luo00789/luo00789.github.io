---
layout: archive
title: "数据可视化作品"
date: 2018-01-4T11:40:45-04:00
excerpt: "tableau"
---

在此展示数据可视化作品

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
