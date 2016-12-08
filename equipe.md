---
layout: default
title: L'équipe
---

Page de l'équipe

{% for member in site.data.members %}

<h2>Membre no 1</h2> 

{{ member.nom }}<br>
{{ member.hobbies }}<br>
{{ member.cursus }}<br>
{{ member.motivation }}<br>
<img src="{{ member.avatar }}" alt="{{member.nom}}"><br>
{% endfor %}


<h2>Des équipes plus grandes, de foot</h2>


{% for club in site.data.foot %}


nom:{{ligue[0]}}
{% for club in ligue[1] %}
{{ club.key }}
{% endfor %}
{% endfor %}