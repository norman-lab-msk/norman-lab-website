---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}
