---
layout: archive
title: "信息可视化高德地图API作品及作品集"
date: 2018-01-04
---

- 沿海多，内陆少
- 日系车较多，德系车中的奥迪、宝马、奔驰相对少点
  - 德系车中的大众数量在7个品牌中最多
 
<style>
h4{background: #EA1D2D; color:white; border-radius:6px; padding:6px;}
h5{background: #D19F2A; color:white; border-radius:3px; padding:3px;}
</style>
<h4>德系车VS日系车：哪个更受欢迎；问高德地图好些</h4>
此研究根据读取高德地图“奥迪、奔驰、宝马、大众、日产、丰田、本田” 七个汽车品牌搜索结果约六千笔数据。

<div class="row">
<div class="col-sm-7" markdown="1"><!-- left -->

##### 结果比较：大众夺冠，成为全国设立4S店最多的汽车品牌
单就选中的汽车品牌为比较单位，大众居冠，符合七个品牌中最受欢迎的汽车品牌。

![品牌比较]({{ "/images/条形图.png" | absolute_url }})

##### 结果比较：日系车更占据国人心

- 单就品牌为比较单位，大众居冠。
- 然而分类别的话，还是日系车更胜一筹。

![系别比较]({{ "/images/tree.png" | absolute_url }})

</div> 
<div class="col-sm-5" markdown="1" ><!-- right -->

##### 分布：全国各地
![高德地图数据-全国各地]({{ "/images/地图.png" | absolute_url }})

* 就沿海地区来看，德系车的数量和日系车的数量有得一拼。
* 然而越往内陆，德系车的数量便逐渐减少，最后只剩下大众。
* 奥迪、奔驰、宝马主打中高档汽车，因而多分布在沿海及中部发达地区。
* 日系车及大众价格亲民且性价比高，国民的承受范围之内，因而在全国大体都有分布。

</div>

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
