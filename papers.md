---
layout: page
title:  Papers
cover:  false
menu:   true
order:  1
---
[Google Scholar Citations](https://scholar.google.com/citations?user=fXsHJXkAAAAJ)
<ul> 
{% assign my_year = "2010" %} 
{% for paper in site.data.papers.papers %}
 {% if paper.year!=my_year %}
 {% assign my_year = paper.year %}
 ## {{ my_year }}
 {% endif %}
  <li>{% include paper.html paper=paper %}</li>
{% endfor %}
</ul> 

