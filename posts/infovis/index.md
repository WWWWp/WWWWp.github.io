---
layout: archive
title: "可视化"
date: 
modified:
excerpt: ""
---

<iframe frameborder="0" id="viz_embedded_frame" ng-src="https://public.tableau.com/views/2_1966/2?%3Aembed=y&amp;%3AshowVizHome=no&amp;%3Adisplay_count=y&amp;%3Adisplay_static_image=y&amp;%3AbootstrapWhenNotified=true" data-load-viz-resize="" data-test-id="vizhome-viz-embed" allowfullscreen="" src="https://public.tableau.com/views/2_1966/2?%3Aembed=y&amp;%3AshowVizHome=no&amp;%3Adisplay_count=y&amp;%3Adisplay_static_image=y&amp;%3AbootstrapWhenNotified=true"></iframe>

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 notes 的列出来-->
