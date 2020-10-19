---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?hl=en&user=20W38KYAAAAJ&view_op=list_works&sortby=pubdate}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Work experience
======
* 2020 ~ Now: Associate Director
  * ACOE@IQVIA

* 2018 ~ 2020: Senior Researcher
  * Medical AI Lab@Tencent
  
* 2016 ~ 2018: Research Scientist
  * China Research Lab@IBM

* Half-a-year in 2015: Intern
  * Microsoft Reaserch Asia

* 2011 ~ 2012: Visiting
  * Victoria University

