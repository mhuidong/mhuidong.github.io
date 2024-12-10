---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

Conference Publications
======
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


---

Journal Publications
======
{% include base_path %}

{% for post in site.journals reversed %}
  {% include archive-single.html %}
{% endfor %}