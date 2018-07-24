---
layout: archive
permalink: /Contact/
title: "Contact"
author_profile: false
header:
  image: "/images/art.jpg"
---
Hello

[link](joedziekan14@gmail.com)

{% include base_path %}
{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

Hello

[link](joedziekan14@gmail.com)
