---
title : "윤명현의 블로그"
excerpt : "단 하나의 밀알이 세상을 바꾸고 기적을 만든다."
# title: "Posts by Category"
layout: categories
permalink: /categories/
header:
  overlay_image : /assets/images/butterfly.jpg
author_profile: true
---


---
layout: archive
title: "Posts by Collection"
permalink: /collection-archive/
author_profile: true
---

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}
    {% capture label %}{{ collection.label }}{% endcapture %}
    {% if label != written_label %}
      <h2 id="{{ label | slugify }}" class="archive__subtitle">{{ label }}</h2>
      {% capture written_label %}{{ label }}{% endcapture %}
    {% endif %}
  {% endunless %}
  {% for post in collection.docs %}
    {% unless collection.output == false or collection.label == "posts" %}
      {% include archive-single.html %}
    {% endunless %}
  {% endfor %}
{% endfor %}
© 2021 GitHub, Inc.
