---
layout: page
title: Participants
---

The following people have registered so far:

<ol>
{% for p in site.data.participants %}
  <li>
    <strong>{{ p.name }}</strong>
    {% if p.affiliation != null %} ({{ p.affiliation }}){% endif %}
    {% if p.slides != null %} <a href="../talks/{{ p.slides }}">(slides)</a> {% endif %}
    <br/>
    {% comment %}
      {% if p.talk != null %} Talk: {{ p.talk }}{% endif %}
    {% endcomment %}
  </li>
{% endfor %}
</ol>
