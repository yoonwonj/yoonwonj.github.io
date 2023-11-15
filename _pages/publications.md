---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

An overview of my research interests
------

During my Master's program, I investigated social cognition and loneliness within the context of COVID-19 mainly by employing natural language processing. These research experiences illuminated my enduring passion for understanding human emotion and led me to realize how language is deeply connected to the human mind.

Furthermore, my involvement in human-robot interaction research revealed the pivotal role of human emotion in shaping the dynamics of these interactions. In addition, while experimenting with large language models to create a framework for empathetic social robots, I became fascinated by their potential to enhance human-robot interactions.

<b>As a doctoral student, I am passionate about exploring the individual and cultural variations and similarities in emotion semantics, and how that variability or similarity shapes human affective experiences. Moreover, I wish to contribute to affective robotics by incorporating large language models to improve emotion representation and expression models for social robots.</b>

------

Papers
------
You can also find my papers (including preprints) at [my Google Scholar profile](https://scholar.google.co.kr/citations?user=iGl3my0AAAAJ&hl=ko).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
