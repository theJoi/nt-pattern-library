---
title: Colors
category: color
colors: ['rgb(6,142,214)','rgb(65,67,80)']
---

<ul>
{% for c in page.colors %}
<li style="font-weight: bold; color: {{c}};">{{c}}</li>
{% endfor %}
</ul>