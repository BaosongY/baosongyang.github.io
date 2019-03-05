---
layout: page
title: Baosong Yang's Home Page
cover: false
---

I develop computational models of natural language learning, 
understanding and generation in people and machines, and my research 
focuses on basic scientific problems related to these models. I am 
especially interested in modeling the rich diversity of linguistic
phenomena across the world’s languages. 

I am a [Reader](https://en.wikipedia.org/wiki/Reader_(academic_rank))
in the [Institute for Language, Cognition, and Computation](http://web.inf.ed.ac.uk/ilcc)
in the [School of Informatics](http://web.inf.ed.ac.uk/)
at the [University of Edinburgh](https://www.ed.ac.uk/). 
[My research group](collaborators) is part of the larger 
[Edinburgh natural language processing group](http://groups.inf.ed.ac.uk/edinburghnlp/)
and we collaborate with many people in Edinburgh and more widely. 
I will be the co-director of the new
[Centre for Doctoral Training in Natural Language Processing](https://edinburghnlp.inf.ed.ac.uk/cdt/),
which will welcome its first students in September 2019.
Currently I am co-director of the 
[Centre for Doctoral Training in Data Science](http://datascience.inf.ed.ac.uk/).


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

