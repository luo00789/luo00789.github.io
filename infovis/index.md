---
layout: archive
title: "数据可视化作品"
date: 2018-01-04
excerpt: "tableau"
---

# 学习Tableau以及数据可视化，
- 要懂得去寻找发现数据，发现事物之间的关联性的，以至于能够做出有效的数据表以及易懂的数据可视化
- 需要扎实的python基础，对于数据的收集和清理有很大的帮助

## 在此展示数据可视化作品

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
