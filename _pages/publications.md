---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

An overview of my research interests
------

During my Master's, I investigated Koreans' social cognition and loneliness during COVID-19 using psychological analysis and natural language processing. Through this process, I realized how powerful language is as a window to the human mind, and became more interested in the relationship between language and human mind. 

I also engaged in projects designing technologies to aid human life and increase mental health. Through this experience, I developed my passion in extending and enhancing human mental capacities using large language models and communication technologies.

Currently, I am exploring how language shapes emotion acquisition & perception, and how large language models reveal the relationship between language and human cognitive abilities. I am also interested in how computers could augment human emotional experiences (-coming soon!)

------

Published Articles
------
You can also find my articles (including preprints) on [my Google Scholar profile](https://scholar.google.co.kr/citations?user=iGl3my0AAAAJ&hl=ko).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
