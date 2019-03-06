---
layout: page
title: Biography
cover: false
---
Baosong is currently a fifth-year Ph.D. candidate in [NLP2CT](http://nlp2ct.cis.umac.mo/) Lab of University of Macau, being advised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html). He has studied and practiced in a broad field of natural language processing (NLP) such as Chinese word segmentation, named entity, semantic role labeling, question answering system, machine translation. His current research focuses on deep learning for NLP, including neural machine translation (NMT),  domain adaptation, representation learning, attention mechanism, inductive bias and low-resource learning.

## News
* 2019-02-23: Three papers are accepted by [NAACL-2019](https://naacl2019.org/).
 
* 2018-11-01: One paper is accepted by [AAAI-2019](https://aaai.org/Conferences/AAAI-19/).

* 2018-08-10: Two paper are accepted by [EMNLP-2018](https://emnlp2018.org/).

* 2018-01-01: Internship at [Tecent AI Lab](https://ai.tencent.com/ailab/en/index) working with Dr. [Zhaopeng Tu](http://zptu.net/). 

## Interests
* Machine Learning
* Natrual Language Processing
* Machine Translation

## Education
* Ph.D. Excepted in 2019. University of Macau, Macau, China.
  Supervised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html) and Prof. [Lidia S. Chao](https://www.fst.um.edu.mo/en/staff/cds/lidiasc.html).
* M.S. 2015. Waseda University, Fukuka, Japan.
  Supervised by Prof. [Yves Lepage](https://www.waseda.jp/fsci/gips/other-en/2015/09/08/2164/)
* B.S. 2014. Sichuan University, Sichuan, China.

## Recent Publications
[Full List](/papers/)
<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

## Professional Services
* ACL-2019:    Reviewer
* NAACL-2019:  Reviewer
* AAAI-2019:   PC Member/Reviewer
* EMNLP-2018:  Reviewer

