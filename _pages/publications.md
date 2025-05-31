---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Selected Publications

**Zhang, M.**#, Zhang, X.#, Ma, Y., and Yi, C. (2024). New directions for Psi and m(1)A decoding in mRNA: deciphering the stoichiometry and function. RNA (New York, N.Y.) 30, 537-547. 10.1261/rna.079950.124.

**Zhang, M.**#, Jiang, Z.#, Ma, Y., Liu, W., Zhuang, Y., Lu, B., Li, K., Peng, J., and Yi, C. (2023). Quantitative profiling of pseudouridylation landscape in the human transcriptome. Nature Chemical Biology 19, 1185-1195.

**Zhang, M**.#, Xiao, Y.#, Jiang, Z.#, and Yi, C. (2023). Quantifying m6A and Ψ modifications in the transcriptome via chemical-assisted approaches. Accounts of Chemical Research 56, 2980-2991.

**Zhang, M.**#, Sun, H.#, Li, K., Xiao, Y., and Yi, C. (2022). m6Am RNA modification detection by m6Am-seq. Methods 203, 242-248.

## Other Publications

Luo N. #, Huang Q. #, Zhang M. #, Yi C. (2025). Functions and therapeutic applications of pseudouridylation. Nature Reviews Molecular Cell Biology. 10.1038/s41580-025-00852-1.

Xiang B. #, Zhang M. #, Li K. #, Zhang Z. #, Liu Y., Gao M., Wang X., Xiao X., Sun Y., He C., Shi J., Fan H., Xing X., Xu G., Yao Y., Chen G., Zhu H., Yi C., Zhang J. (2025). The epitranscriptional factor PCIF1 orchestrates CD8(+) T cell ferroptosis and activation to control antitumor immunity. Nature Immunology 26, 252-264.



{% raw %}
{% for post in site.publications reversed %}
  {% if post.category == "conferences" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
{% endraw %}
