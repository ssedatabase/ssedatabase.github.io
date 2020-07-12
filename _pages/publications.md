---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Leclerc QJ, Fuller NM, Knight LE et al. What settings have been linked to SARS-CoV-2 transmission clusters? [version 2; peer review: 2 approved]. Wellcome Open Res 2020, 5:83 (https://doi.org/10.12688/wellcomeopenres.15889.2)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
