---
layout: page
title: Participants
---

The following people have registered so far:

<ul>
{% for p in site.data.participants %}
  <li>
    <strong>{{ p.name }}</strong>
    {% if p.affiliation != null %} ({{ p.affiliation }}){% endif %} <br/>
    {% comment %}
      {% if p.talk != null %} Talk proposal: {{ p.talk }}{% endif %}
    {% endcomment %}
  </li>
{% endfor %}
</ul>
