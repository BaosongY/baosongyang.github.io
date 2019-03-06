---
layout: page
title:  Papers
cover:  false
menu:   true
order:  1
---
[Google Scholar Citations](https://scholar.google.com/citations?user=fXsHJXkAAAAJ)
## 2019
<ul> 
{% assign my_year = "2019" %} 
{% for paper in site.data.papers.papers %}
 {% if paper.year!=my_year %}
 {% assign my_year = paper.year %}
 ## 2019
 {% endif %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
</ul> 

