---
layout: archive
title: "信息可视化作品集"
date: 2018-01-04
---

<iframe src="https://public.tableau.com/views/4S_3/1?:embed=y&:display_count=yes" width="794px" height="1122px" frameborder="0"></iframe>
{% for post in site.categories.keshihua %} {% include post-grid.html %} {% endfor %}

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
