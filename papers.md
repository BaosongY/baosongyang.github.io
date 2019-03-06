---
layout: page
title:  Papers
cover:  false
menu:   true
order:  1
---

[Google Scholar Citations](https://scholar.google.com/citations?user=fXsHJXkAAAAJ)
<ul>
**2019** 
{% for paper in site.data.papers.papers %}
 {% if paper.year==2019 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
**2018** 
{% for paper in site.data.papers.papers %}
 {% if paper.year==2018 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
**2017** 
{% for paper in site.data.papers.papers %}
 {% if paper.year==2017 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
**2016** 
{% for paper in site.data.papers.papers %}
 {% if paper.year==2016 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
**2015** 
{% for paper in site.data.papers.papers %}
 {% if paper.year==2015 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %} 
</ul>

