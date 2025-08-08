---
permalink: /
title: " "
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Recent News
[24 Jan 2025] Our paper on programming language synthsis for automated exploit generation is accepted by Usenix Security 2025.

[27 Jun 2024] I present my poster on programming language synthesis at PLDI SRC 2024.

[16 Dec 2023] Our paper on data minimization is accepted by SANER 2024.

[9 Jan 2023] I become a Ph.D. student at NUS.

[4 Oct 2022] Our paper as well as my Master's dissertation on cryptocurrency-themed malicious browser extensions is accepted by SIGMETRICS 2023.

[17 Aug 2022] Our paper on privacy compliance is accepted by ASE 2022.

[28 Feb 2022] I become a research assistant in PLSE lab at NUS. :)

## About
I'm a Ph.D. student in PLSE lab at National University of Singapore (School of Computing). I received my M.S degree in Information Security from NUS in 2022 and B.S. degree in Software Engineering from Shandong University in 2020. My research interests include software security, program analysis, and programming languages. I am now exploring topics in program synthesis and program logics with [Prof. Ilya Sergey](https://ilyasergey.net/).

I'm also interested in CTF and looking for teammates. You can find my team [Jv5t4Fun](https://ctftime.org/team/164352) here. OK, as yet, there is only myself T_T.


## Publications
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


## Student Research Competition
{% include base_path %}

{% for post in site.srcompetitions reversed %}
  {% include archive-single.html %}
{% endfor %}

