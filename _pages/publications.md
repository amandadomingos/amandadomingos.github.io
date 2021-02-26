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

Publications
======
  * A. Domingos, I. Batista. [Um mapa para transparência e replicabilidade: protocolo TIER](https://periodicos.ufpe.br/revistas/politicahoje/article/view/245776), 2020.
  * M. Cunha, A. Domingos, V. Rocha, M. Torres. [How many could have been saved? Effects of social distancing on COVID-19](http://bibliotecadigital.fgv.br/ojs/index.php/rap/article/view/83026). Brazilian Journal of Public Administration, 2020.
  * D. Figueiredo, R. Lins, A. Domingos, N. Janz, L. Silva. [Seven Reasons Why: A User’s Guide to Transparency and Reproducibility](https://www.scielo.br/scielo.php?pid=S1981-38212019000200400&script=sci_abstract). Brazilian Political Science Review, 2019.
  * M. Batista, A. Domingos. [More Than Good Intentions: Quantitative and Qualitative Technics In The Impact Evaluation](https://www.scielo.br/scielo.php?pid=S0102-69092017000200511&script=sci_abstract&tlng=pt). Revista Brasileira de Ciências Sociais, 2017. (Portuguese).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
