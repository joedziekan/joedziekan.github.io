---
title: "NASA’s Space Grant Midwest High-power Rocket Competition: Lucky Bucky"
date: 2018-6-10
tags: [rocketry, machining]
header:
  image: "/images/Lucky Bucky.jpg"
excerpt: "Rocketry, Lucky Bucky, AIAA"
---


{% include base_path %}
{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
