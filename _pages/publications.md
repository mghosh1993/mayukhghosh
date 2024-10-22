---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Peer-Reviewed Journals {#peer-reviewed-journals .unnumbered}

-   **Ghosh, M.**, Kuiper, A., Mahes, R., and Maragno, D., 2023; [Learn
    global and optimize local: A data-driven methodology for last-mile
    routing](https://doi.org/10.1016/j.cor.2023.106312). Computers &
    Operations Research (159), p. 106312.

-   Emmens, T., Amrit, C., Abdi, A., and **Ghosh, M.**, 2021; [The
    promises and perils of Automatic Identification System
    data](https://doi.org/10.1016/j.eswa.2021.114975). Expert Systems
    with Applications (178), p.114975.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship