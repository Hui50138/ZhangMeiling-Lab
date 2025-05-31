---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Selected Publications

**Zhang, M.**#, Zhang, X.#, Ma, Y., and Yi, C. (2024). New directions for Psi and m(1)A decoding in mRNA: deciphering the stoichiometry and function. RNA (New York, N.Y.) 30, 537-547. 10.1261/rna.079950.124.

Zhang, M.#, Jiang, Z.#, Ma, Y., Liu, W., Zhuang, Y., Lu, B., Li, K., Peng, J., and Yi, C. (2023). Quantitative profiling of pseudouridylation landscape in the human transcriptome. Nature Chemical Biology 19, 1185-1195.

Zhang, M.#, Xiao, Y.#, Jiang, Z.#, and Yi, C. (2023). Quantifying m6A and Ψ modifications in the transcriptome via chemical-assisted approaches. Accounts of Chemical Research 56, 2980-2991.


{% raw %}
{% for post in site.publications reversed %}
  {% if post.category == "manuscripts" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
{% endraw %}

## Other Publications

{% raw %}
{% for post in site.publications reversed %}
  {% if post.category == "conferences" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
{% endraw %}
