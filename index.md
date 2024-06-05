---
layout: page
title: Baosong Yang
cover: false
---
I am currently an Algorithm Expert in the [Language Technology Lab](https://damo.alibaba.com/labs/language-technology?lang=en) at [Alibaba Tongyi Lab](https://tongyi.aliyun.com/). I received my Ph.D at [NLP2CT](http://nlp2ct.cis.umac.mo/) Lab of University of Macau, advised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html). I have studied and practiced in a broad field of natural language processing (NLP) such as Chinese word segmentation, named entity, semantic role labeling, question answering system, machine translation. My current research focuses on multilingualism of Large Language Model. I have published over 50 papers in leading NLP/AI journals and conferences such as ACL, EMNLP, AAAI, and NAACL.

We have some research intern positions available in Qwen Team. If you are interested in LLM, please feel free to contact us: nlp2ct.baosong[AT]gmail.com.

## News
* 2024-05-16: Two papers are accepted by [ACL-2024](https://2024.aclweb.org/). 

* 2024-02-20: One paper is accepted by [COLING-2024](https://lrec-coling-2024.org/).

* 2024-02-06: We release [Qwen1.5](https://qwenlm.github.io/blog/qwen1.5/), which boasts comparable multilingual capabilities to GPT3.5-Turbo.

* 2023-09-22: One paper is accepted by [NeurlPS-2023](https://nips.cc/). 

* 2023-07-21: We release a 13B multilingual large language model which is trained on 600 billion tokens -- PolyLM ([Demo](https://modelscope.cn/studios/damo/demo-polylm-multialpaca-13b/summary),[Model](https://modelscope.cn/models/damo/nlp_polylm_13b_text_generation/summary),[Paper](https://browse.arxiv.org/pdf/2307.06018.pdf),[Code](https://github.com/modelscope/swift/tree/main/examples/pytorch/llm))

## Interests
* Multilingualism
* Large Language Model
* Machine Translation

## Experience
* Ph.D. 2019. University of Macau, Macau, China.
  Supervised by Prof. [Derek F. Wong](https://www.fst.um.edu.mo/en/staff/fstfw.html) and Prof. [Lidia S. Chao](https://www.fst.um.edu.mo/en/staff/cds/lidiasc.html).
* Research Intern. 2018. Tencent AI Lab, Shenzhen, China.
  Supervised by Dr. [Zhaopeng Tu](http://zptu.net/)  
* M.S. 2015. Waseda University, Fukuka, Japan.
  Supervised by Prof. [Yves Lepage](https://www.waseda.jp/fsci/gips/other-en/2015/09/08/2164/)
* B.S. 2014. Sichuan University, Sichuan, China.

## Selected Publications
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
* Area Chair: EMNLP, AACL; PC Member/Reviewer: ACL, AAAI, NAACL, NLPCC, CCL, etc.
