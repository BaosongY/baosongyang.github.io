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
* Ph.D. Excepted at 2019. University of Macau, Macau, China. Supervised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html) and Prof. [Lidia S. Chao](https://www.fst.um.edu.mo/en/staff/cds/lidiasc.html).
* M.S. 2015. Waseda University, Fukuka, Japan. Supervised by Prof. [Yves Lepage](https://www.waseda.jp/fsci/gips/other-en/2015/09/08/2164/)
* B.S. 2014. Sichuan University, Sichuan, China.
## News
* 2019-02-23: Three papers are accepted by NAACL-2019.
 
* 2018-11-01: One paper is accepted by AAAI-2019.

* 2018-08-10: Two paper is accepted by EMNLP-2018.

* 2018-01-01. Internship at Tecent AI lab. Work with Dr. [Zhaopeng Tu](http://zptu.net/). 

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

