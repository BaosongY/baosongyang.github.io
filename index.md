---
layout: page
title: Baosong Yang
cover: false
---
I am currently a Ph.D. candidate in the Natural Language Processing & Portuguese--Chinese Machine Translation (NLP2CT) research group, the Department of Computer and Information Science at the University of Macau.
## Interests
* Machine Learning
* Natrual Language Processing
* Machine Translation
## Education
* Ph.D. Excepted at 2019. University of Macau, Macau, China.
* M.S. 2015. Waseda University, Fukuka, Japan.
* B.S. 2014. Sichuan University, Sichuan, China.
		Moreover, he had internships at Tencent AI Lab (Shenzhen) in 2018.
## News
* 2019-02-23: Three papers are accepted by NAACL-2019.
 
* 2018-11-01: One paper is accepted by AAAI-2019.

* 2018-08-10: Two paper is accepted by EMNLP-2018.

* 2018-01-01. intern at Tecent AI lab working with Dr. Zhaopeng Tu. 

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

