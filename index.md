---
layout: page
title: Baosong Yang
cover: false
---
## Biography
I am currently a Ph.D. candidate in the Natural Language Processing & Portuguese--Chinese Machine Translation (NLP2CT) research group, the Department of Computer and Information Science at the University of Macau.
## Interests
* Machine Learning
* Natrual Language Processing
* Machine Translation
## Education
* Ph.D. excepted at 2019. University of Macau.
* M.S. 2015. The Graduate School of Information, Production and Systems, Waseda University, Fukuka, Japan.
* B.S. 2014. College of Software Engineering, Sichuan University, Sichuan, China.
		Moreover, he had internships at Tencent AI Lab (Shenzhen) in 2018.
## News
* Feb 2019, three papers are accepted by NAACL-2019.
 
* Nov 2018, one paper is accepted by AAAI-2019.

* May 2019, two paper is accepted by EMNLP-2018.

* Jan 2018, I intern at Tecent AI lab working with Dr. Zhaopeng Tu. 

## Selected Publications

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

