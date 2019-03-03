---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Below you can see a list of finished theses that were elaborated under my supervision. If you are looking for a topic for your thesis as well, they might serve as inspiration. If you have any questions, own ideas or if you are just curious, feel free to contact me. 

**Notice**: If you are not a student of the Department of Informatics or the Department of Electrical Engineering and Information Technology of the Karlsruhe Institute of Technology, you are responsible to find a professor who will supervise you.
{: .notice}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
