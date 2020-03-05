---
layout: page
title: Biography
cover: false
---
I am currently an Algorithm Expert in the [Language Technology Lab](https://damo.alibaba.com/labs/language-technology?lang=en) at Alibaba DAMO Academy. I received my Ph.D at [NLP2CT](http://nlp2ct.cis.umac.mo/) Lab of University of Macau, advised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html). I have studied and practiced in a broad field of natural language processing (NLP) such as Chinese word segmentation, named entity, semantic role labeling, question answering system, machine translation. His current research focuses on deep learning for NLP, including neural machine translation (NMT),  domain adaptation, representation learning, attention mechanism, inductive bias and low-resource learning.

## News
* 2020-02-24: Join [Alibaba DAMO Academy](https://damo.alibaba.com).

* 2019-11-11: Two papers are accepted by [AAAI-2020](https://aaai.org/Conferences/AAAI-20/).

* 2019-09-08: One paper is accepted by [Knowledge-Based Systems](https://www.journals.elsevier.com/knowledge-based-systems).

* 2019-05-14: Two papers are accepted by [ACL-2019](http://www.acl2019.org/).

* 2019-02-23: Three papers are accepted by [NAACL-2019](https://naacl2019.org/).

## Interests
* Machine Learning
* Natural Language Processing
* Machine Translation

## Education
* Ph.D. Expected in 2019. University of Macau, Macau, China.
  Supervised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html) and Prof. [Lidia S. Chao](https://www.fst.um.edu.mo/en/staff/cds/lidiasc.html).
* M.S. 2015. Waseda University, Fukuka, Japan.
  Supervised by Prof. [Yves Lepage](https://www.waseda.jp/fsci/gips/other-en/2015/09/08/2164/)
* B.S. 2014. Sichuan University, Sichuan, China.

## Recent Publications
[Full List](/publications/)
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
* PC Member/Reviewer: ACL, EMNLP, NAACL, AAAI, NLPCC, CCL, etc.
