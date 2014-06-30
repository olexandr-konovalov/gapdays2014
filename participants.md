---
layout: page
title: Participants
names:
---

<p class="message">
  The list of participants is not yet available.
</p>

{% comment %}

<ul>
{% for p in site.data.participants %}
  <li>
    {{ p.name }}
    {% if p.affiliation != null %} ({{ p.affiliation }}){% endif %}
  </li>
{% endfor %}
</ul>

{% endcomment %}
