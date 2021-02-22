---
layout: archive
permalink: /publications/
title: "Publications"
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=e9JynrAAAAAJ).

{% include base_path %}

{% capture written_year %}'None'{% endcapture %}
{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}