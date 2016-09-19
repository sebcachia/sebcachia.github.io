---
layout: archive
author_profile: true
permalink: /personal/
comments: false
header:
  image: homepage.png
---

The posts here reflect my personal life. This will be a dumping ground for anything from short pieces of writing, images or longer essays on topics of personal interest.

<h3 class="archive__subtitle">Personal Posts</h3>
{% include base_path %}
{% for post in site.categories.personal %}
    {% include archive-single.html %}
{% endfor %}
