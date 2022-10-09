---
layout: page
title: Baosong Yang
cover: false
---
I am currently an Algorithm Expert in the [Language Technology Lab](https://damo.alibaba.com/labs/language-technology?lang=en) at [Alibaba DAMO Academy](https://damo.alibaba.com). I received my Ph.D at [NLP2CT](http://nlp2ct.cis.umac.mo/) Lab of University of Macau, advised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html). I have studied and practiced in a broad field of natural language processing (NLP) such as Chinese word segmentation, named entity, semantic role labeling, question answering system, machine translation. My current research focuses on deep learning for NLP, including neural machine translation (NMT),  cross-lingual language model (XLM), cross-lingual information retrieval (CLIR). I have published over 30 papers in leading NLP/AI journals and conferences such as ACL, EMNLP, AAAI, and NAACL.

We have some research intern positions available in Alibaba DAMO Academy. If you are interested in NLP and ML, please feel free to contact us: nlp2ct.baosong[AT]gmail.com.

## News
* 2022-10-07: Two papers are accepted by [EMNLP-2022](https://2022.emnlp.org/).

* 2022-08-30: Our model UniTE wins 2 of 4 tasks in [WMT-2022 Quality Estimation Shared Tasks](https://codalab.lisn.upsaclay.fr/competitions/6866#results).

* 2022-04-08: Three papers are accepted by [NAACL-2022](https://2022.naacl.org/).

* 2022-02-25: Four papers are accepted by [ACL-2022](https://www.2022.aclweb.org/).

* 2021-12-01: Two papers are accepted by [AAAI-2022](https://aaai.org/Conferences/AAAI-22/).

* 2021-11-01: Our model RoBLEURT wins 5 of 8 English-target tasks in [WMT-2021 Metrics Shared Tasks](http://www.statmt.org/wmt21/metrics-task.html).

## Interests
* Machine Learning
* Natural Language Processing
* Machine Translation

## Experience
* Ph.D. 2019. University of Macau, Macau, China.
  Supervised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html) and Prof. [Lidia S. Chao](https://www.fst.um.edu.mo/en/staff/cds/lidiasc.html).
* Research Intern. 2018. Tencent AI Lab, Shenzhen, China.
  Supervised by Dr. [Zhaopeng Tu](http://zptu.net/)  
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
* Area Chair: EMNLP; PC Member/Reviewer: ACL, AAAI, NAACL, NLPCC, CCL, etc.
