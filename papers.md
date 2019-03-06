---
layout: page
title:  Papers
cover:  false
menu:   true
order:  1
---

[Google Scholar Citations](https://scholar.google.com/citations?user=fXsHJXkAAAAJ)
<ul>
{% for paper in site.data.papers.papers %}
  **2019**
 {% if paper.year==2019 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
  **2018**
 {% if paper.year==2019 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %} 
  **2017**
 {% if paper.year==2019 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %} 
  **2016**
 {% if paper.year==2019 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
   **2015**
 {% if paper.year==2019 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
</ul>

