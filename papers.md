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
{% for paper in site.data.papers.papers %}
 {% if paper.year==2019 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
</ul> 
## 2018
<ul>
{% for paper in site.data.papers.papers %}
 {% if paper.year==2018 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
</ul> 
## 2017
<ul>
{% for paper in site.data.papers.papers %}
 {% if paper.year==2017 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
</ul> 
## 2016
<ul>
{% for paper in site.data.papers.papers %}
 {% if paper.year==2016 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %}
{% endfor %}
</ul> 
## 2015
<ul>
{% for paper in site.data.papers.papers %}
 {% if paper.year==2015 %}
  <li>{% include paper.html paper=paper %}</li>
 {% endif %} 
</ul>

