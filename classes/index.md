---
title: Classes
layout: page
---

A class represents an occupation your character might have, and grants some special abilities that you can use in the game. Choose the one that fits your character best, and try to incorporate it into your character's background.

{% for page in site.pages -%}
    {%- if page.layout == 'class' %}
- [{{ page.title | escape }}]({{ site.baseurl }}{{ page.url }})
    {%- endif -%}
{%- endfor -%}
