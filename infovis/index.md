---
layout: archive
title: "信息可视化作品集"
date: 2018-01-04
---

# 信息可视化高德地图API作品
- 沿海多，内陆少
- 日系车较多，德系车中的奥迪、宝马、奔驰相对少点
  - 德系车中的大众数量在7个品牌中最多
  
![tableau](https://luo00789.github.io/images/%E6%95%85%E4%BA%8B.png)

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
