---
layout: page
title: Baosong Yang
cover: false
---
I am currently an Algorithm Expert in the [Language Technology Lab](https://damo.alibaba.com/labs/language-technology?lang=en) at [Alibaba DAMO Academy](https://damo.alibaba.com). I received my Ph.D at [NLP2CT](http://nlp2ct.cis.umac.mo/) Lab of University of Macau, advised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html). I have studied and practiced in a broad field of natural language processing (NLP) such as Chinese word segmentation, named entity, semantic role labeling, question answering system, machine translation. My current research focuses on deep learning for NLP, including neural machine translation (NMT),  cross-lingual language model (XLM), cross-lingual information retrieval (CLIR).

## News
* 2020-09-30: One paper is accepted by [COLING-2020](https://coling2020.org/#).

* 2020-09-15: One paper is accepted by [EMNLP-2020](https://2020.emnlp.org/).

* 2020-07-13: Two papers are accepted by [SIGIR-Ecom-2020](https://sigir-ecom.github.io/).

* 2020-04-04: One paper is accepted by [ACL-2020](http://www.acl2020.org/).

* 2020-02-24: Join [Alibaba DAMO Academy](https://damo.alibaba.com).

* 2019-11-11: Two papers are accepted by [AAAI-2020](https://aaai.org/Conferences/AAAI-20/).

## Interests
* Machine Learning
* Natural Language Processing
* Machine Translation

## Education
* Ph.D. 2019. University of Macau, Macau, China.
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
* PC Member/Reviewer: ACL, AAAI, EMNLP, NAACL, NLPCC, CCL, etc.
