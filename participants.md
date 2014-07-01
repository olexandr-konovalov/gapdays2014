---
layout: page
title: Participants
---

The following people have registered so far:

<ul>
{% for p in site.data.participants %}
  <li>
    {{ p.name }}
    {% if p.affiliation != null %} ({{ p.affiliation }}){% endif %} <br/>
    {% if p.talk != null %} Talk proposal: {{ p.talk }}{% endif %}
  </li>
{% endfor %}
</ul>
