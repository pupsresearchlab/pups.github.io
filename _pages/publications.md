---
title: ""
permalink: /publications/
author_profile: true
---

<h2>Peer-Reviewed Conference Publications</h2>
<b>Bailey Kacsmar</b>, Kyle Tilbury, Miti Mazmudar, Florian Kerschbaum. Caring about Sharing: User Perceptions of Multiparty Data Sharing. USENIX Security 2022. Accepted. &quot;[Survey](https://bkacsmar.github.io/files/Suvey_MPDS_USENIX_2022.pdf)&quot;.
<br>


Rasoul Akhavan Mahdavi,  Thomas Humphries, <b>Bailey Kacsmar</b>, Simeon Krastnikov, Nils Lukas, John Premkumar,  Masoumeh Shafieinejad, Simon Oya, Florian Kerschbaum, Erik-Oliver Blass. &quot;[Practical Over-Threshold Multi-Party Private Set Intersection](https://bkacsmar.github.io/files/overthresholdPSI.pdf)&quot;. The Annual Computer Security Applications Conference (ACSAC 2020), pp. 772-783.


<b>Bailey Kacsmar</b>, Basit Khurram, Nils Lukas, Alexander Norton, Masoumeh Shafieinejad, Zhiwei Shang, Yasser Baseri, Maryam Sepehri, Simon Oya, and Florian Kerschbaum. &quot;[Differentially Private Two-Party Set Operations](https://bkacsmar.github.io/files/DiPSI.pdf)&quot;. The 5th IEEE European Symposium on Security and Privacy, (IEEE EuroS&P 2020). pp. 390-404. 

<b>Bailey Kacsmar</b>, Sarah Plosker, Ryan Henry. &quot;[Computing Low-Weight Discrete Logarithms](https://bkacsmar.github.io/files/Low_weight_DLP_ext.pdf)&quot;. The 24th Annual Conference on Selected Areas in Cryptography (SAC 2017), <i>International Conference on Selected Areas in Cryptography</i>, pp. 106-126. Springer, Cham. [(Slides)](https://bkacsmar.github.io/files/Computing_Low_Weight_DL.pdf)



<h2>Peer-Reviewed Journal Publications</h2>
<b>Bailey Kacsmar</b>, Chelsea H. Komlo, Florian Kerschbaum, Ian Goldberg. &quot;[Mind the Gap: Ceremonies for Applied Secret Sharing](https://bkacsmar.github.io/files/mindthegap.pdf).&quot; <i> Proceedings on Privacy Enhancing Technologies</i>. Vol. 2020, No. 2. 18 pages. April 2020. [(Slides)](https://bkacsmar.github.io/files/PoPETS_2020_Mindthegap.pdf)
<br>

<b>Bailey Kacsmar</b>, Douglas R. Stinson. &quot;[A Network Reliability Approach to the Analysis of Combinatorial Repairable Threshold Schemes](https://bkacsmar.github.io/files/networkReliability.pdf).&quot; <i>Advances in Mathematics of Communications, 2019</i>, 13 (4) : 601-612. doi: 10.3934/amc.2019037.
<br>

Chenkuan Li, Changpin Li, <b>Bailey Kacsmar</b>, Roque Lacroix and Kyle Tilbury. &quot;[The Abel Integral Equations in Distribution](https://bkacsmar.github.io/files/abelIntegral.pdf)&quot;, Advances in Analysis, 2 (2017), pages 88-104.doi:10.2206/aan.




<h2>Conference Presentations without Proceedings</h2>
"State-Level Secrets: When Theory Meets Practice for Journalists Working with Encrypted Documents", Real World Cryptography 2019, San Jose, California, United States. (January 2019). Co-presenter: Chelsea H. Komlo.  [(Slides)](https://bkacsmar.github.io/files/RWC_Talk.pdf)





<h2>Theses</h2>
[Designing Efficient Algorithms for Combinatorial Repairable Threshold Schemes](https://bkacsmar.github.io/files/DesigningEfficientAlgo.pdf). UWSpace: MMath
thesis, University of Waterloo, Waterloo, ON, Canada (October 2018). [(Slides)](https://bkacsmar.github.io/files/MastersThesis_presentation.pdf)



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
