---
layout: default
---

{% for character in site.characters %}
[{{ character.character }} ({{character.style}})]({{ character.url }}) at {{character.path}} to render to {{ character.url }}
{% endfor %}