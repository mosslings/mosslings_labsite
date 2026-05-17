---
title: Team
nav:
  order: 3
  tooltip: About our mosslings
---

# {% include icon.html icon="fa-solid fa-users" %}Team
{% comment %}
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
  incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
  nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% endcomment %}
{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

# Alumni
{% for alumni1 in site.data.alumni %}
{{ forloop.index }}. {{ alumni1.name }} – {{ alumni1.role }},{{ alumni1.period }}, {{ alumni1.institute }}
{% endfor %}

{% include section.html %}
{% comment %}
  {% capture content %}

  {% include figure.html image="images/photo.jpg" %}
  {% include figure.html image="images/photo.jpg" %}
  {% include figure.html image="images/photo.jpg" %}

  {% endcapture %}

  {% include grid.html style="square" content=content %}
{% endcomment %}
