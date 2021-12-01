---
layout: page
title:  Publications
cover:  false
menu:   true
order:  1
---
[Google Scholar Citations](https://scholar.google.com/citations?user=fXsHJXkAAAAJ)
{% assign my_year = "2023" %} 
{% for paper in site.data.papers.papers %}
 {% if paper.year!=my_year %}
 {% assign my_year = paper.year %}
 <h2>{{ my_year }}</h2>
 {% endif %}
 <ul> 
  <li>{% include paper.html paper=paper %}</li>
 </ul>
{% endfor %}
 

