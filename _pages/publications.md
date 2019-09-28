---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


Bailey Kacsmar, Sarah Plosker, Ryan Henry. &quot;[Computing Low-Weight Discrete Logarithms](https://bkacsmar.github.io/files/Low_weight_DLP_ext.pdf).&quot; the 24th Annual Conference on Selected Areas in Cryptography (SAC 2017), in <i>International Conference on Selected Areas in Cryptography</i>, pp. 106-126. Springer, Cham.







{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
