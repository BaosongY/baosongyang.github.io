---
layout: page
title:  Papers
cover:  false
menu:   true
order:  1
---
[Google Scholar Citations](https://scholar.google.com/citations?user=fXsHJXkAAAAJ)
{% assign my_year = "2020" %} 
{% for paper in site.data.papers.papers %}
 {% if paper.year!=my_year %}
 {% assign my_year = paper.year %}
 <h2>{{ my_year }}</h2>
 {% endif %}
 <ul> 
  <li style="font-size:40px">{% include paper.html paper=paper %}</li>
 </ul>
{% endfor %}
 

