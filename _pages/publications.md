---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Selected Publications

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
