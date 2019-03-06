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
{% case paper.year %}
  {% when 2019 %}**2019**
  <li>
  {% include paper.html paper=paper %}
  </li>  
  {% when 2018 %}**2018**
  <li>
  {% include paper.html paper=paper %}
  </li>  
  {% when 2017 %}**2017**
  <li>
  {% include paper.html paper=paper %}
  </li>  
  {% when 2016 %}**2016**
  <li>
  {% include paper.html paper=paper %}
  </li>  
  {% when 2015 %}**2015**
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endcase %}
{% endfor %}
</ul>

