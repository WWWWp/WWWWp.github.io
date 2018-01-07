---
layout: archive
title: "可视化"
date: 
modified:
excerpt: ""
---

<iframe src="https://public.tableau.com/views/2_1966/2?:embed=y&:display_count=yes"
 width="100%" ></iframe>

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 notes 的列出来-->
