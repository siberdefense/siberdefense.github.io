---
layout: archive
permalink: /posts/
author_profile: false
---

{% for post in site.pages %}
  {% unless post.hidden %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}