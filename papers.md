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
  **2019**{% when 2019 %}
  <li>
  {% include paper.html paper=paper %}
  </li>  
  **2018**{% when 2018 %}
  <li>
  {% include paper.html paper=paper %}
  </li>  
  **2017**{% when 2017 %}
  <li>
  {% include paper.html paper=paper %}
  </li>  
  **2016**{% when 2016 %}
  <li>
  {% include paper.html paper=paper %}
  </li>  
  **2015**{% when 2015 %}
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endcase %}
{% endfor %}
</ul>

