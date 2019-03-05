---
layout: archive
title: "Students"
permalink: /students/
author_profile: true
---

{% include base_path %}

Below you can see a list of finished theses as well as theses in progress that were elaborated under my supervision. If you are looking for a topic for your thesis, they might serve as inspiration. If you have any questions, own ideas or if you are just curious, feel free to contact me. 

**Notice**: If you are not a student of the  [Department of Informatics](https://www.informatik.kit.edu/english/) or the [Department of Electrical Engineering and Information Technology](http://www.etit.kit.edu/english/) of the Karlsruhe Institute of Technology, you are responsible to find a professor who will supervise you.
{: .notice--danger}

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.teaching reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
