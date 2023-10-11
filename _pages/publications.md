---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my publications and preprints on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

An overview of my research interests
------

During my Master's, I investigated social cognition and loneliness within the context of COVID-19 mainly by employing natural language processing. This pursuit illuminated my non-dyring-out passion and curiosity toward human emotion, and led me to realize how powerful language is as a window to the human mind. 

Furthermore, engaging in human-robot interaction research, I realized how human emotion plays crucial role in shaping the dynamics of human-robot interaction. Moreover, by experimenting with large language models to develop a framework for empathetic social robots, I was fascinated by the potential of large language models for better human-robot interaction.

<b>As a doctoral student, I am passionate about exploring the cultural variations and similarities in emotion semantics, and how that variability or similarity is reflected in human affective experience. Moreover, I am interested in contributing to affective robotics by incorporating large language models to develop better emotion models for social robots.</b>

------

Published Articles
------
You can also find my articles (including preprints) on [my Google Scholar profile](https://scholar.google.co.kr/citations?user=iGl3my0AAAAJ&hl=ko).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
