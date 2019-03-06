---
layout: page
title: Baosong Yang
cover: false
---
I am currently a Ph.D. candidate in the Natural Language Processing & Portuguese--Chinese Machine Translation ([NLP2CT](http://nlp2ct.cis.umac.mo/)) research group, the Department of Computer and Information Science at the University of Macau.

## Interests
* Machine Learning
* Natrual Language Processing
* Machine Translation

## Education
* Ph.D. Excepted in 2019. University of Macau, Macau, China. Supervised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html) and Prof. [Lidia S. Chao](https://www.fst.um.edu.mo/en/staff/cds/lidiasc.html).
* M.S. 2015. Waseda University, Fukuka, Japan. Supervised by Prof. [Yves Lepage](https://www.waseda.jp/fsci/gips/other-en/2015/09/08/2164/)
* B.S. 2014. Sichuan University, Sichuan, China.

## News
* 2019-02-23: Three papers are accepted by [NAACL-2019](https://naacl2019.org/).
 
* 2018-11-01: One paper is accepted by [AAAI-2019](https://aaai.org/Conferences/AAAI-19/).

* 2018-08-10: Two paper are accepted by [EMNLP-2018](https://emnlp2018.org/).

* 2018-01-01. Internship at [Tecent AI Lab](https://ai.tencent.com/ailab/en/index) working with Dr. [Zhaopeng Tu](http://zptu.net/). 

## Recent Publications
[Full List](<ul>{% include paper.html paper=paper %}</ul>) [Google Scholar](https://scholar.google.com/citations?user=fXsHJXkAAAAJ)
<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

