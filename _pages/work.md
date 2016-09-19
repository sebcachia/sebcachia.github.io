---
layout: archive
author_profile: true
permalink: /work/
comments: false
header:
  image: homepage3.png
---

The posts here reflect ongoing thoughts about my professional life. Expect insights into building digital products, leading teams and more. All opinions are my own and should not be interpreted as reflecting those of my employer.

<h3 class="archive__subtitle">Work Posts</h3>
{% include base_path %}
{% for post in site.categories.work %}
    {% include archive-single.html %}
{% endfor %}
