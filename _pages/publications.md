---
title: "Publications"
permalink: /publications/
author_profile: true
---

<h2>Peer-Reviewed Conference Publications</h2>
<b>Bailey Kacsmar</b>, Sarah Plosker, Ryan Henry. &quot;[Computing Low-Weight Discrete Logarithms](https://bkacsmar.github.io/files/Low_weight_DLP_ext.pdf).&quot; the 24th Annual Conference on Selected Areas in Cryptography (SAC 2017), in <i>International Conference on Selected Areas in Cryptography</i>, pp. 106-126. Springer, Cham.


<h2>Peer-Reviewed Journal Publications</h2>
<b>Bailey Kacsmar</b>, Douglas R. Stinson. &quot;[A Network Reliability Approach to the Analysis of Combinatorial Repairable Threshold Schemes](https://bkacsmar.github.io/files/networkReliability.pdf).&quot; <i>Advances in Mathematics of Communications, 2019</i>, 13 (4) : 601-612. doi: 10.3934/amc.2019037.
<br>
Chenkuan Li, Changpin Li, <b>Bailey Kacsmar</b>, Roque Lacroix and Kyle Tilbury. &quot;[The Abel integral equations in distribution](https://bkacsmar.github.io/files/abelIntegral.pdf)&quot;, Advances in Analysis, 2 (2017), pages 88-104.DOI:10.2206/aan.

<h2>Conference Presentations without Proceedings</h2>
"State-Level Secrets: When Theory Meets Practice for Journalists Working with Encrypted Documents", Real World Cryptography 2019, San Jose, California, United States. (January 2019). Co-presenter: Chelsea Komlo


<h2>Theses</h2>
[Designing Efficient Algorithms for Combinatorial Repairable Threshold Schemes](https://bkacsmar.github.io/files/DesigningEfficientAlgo.pdf). UWSpace: MMath
thesis, University of Waterloo, Waterloo, ON, Canada (October 2018).






{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
