---
layout: page
title: Participants
---

The following people have registered so far:

<ul>
{% for p in site.data.participants %}
  <li>
    {{ p.name }}
    {% if p.affiliation != null %} ({{ p.affiliation }}){% endif %}
  </li>
{% endfor %}
</ul>
