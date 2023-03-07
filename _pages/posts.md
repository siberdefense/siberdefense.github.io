---
layout: archive
permalink: /posts/
author_profile: false
---

{% for post in site.posts %}
  {% unless post.hidden %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}