---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: admin" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|admin$)" %}

{% include section.html %}

{% include figure.html image="images/IMG_5788.jpg" width="80%" caption="Conveyor belt sushi" %}

{% include figure.html image="images/mets_game.jpg" width="80%" caption="Mets game" %}

{% include figure.html image="images/paintnpour.jpg" width="80%" caption="Paint 'N Pour!" %}

{% include figure.html image="images/coldspringharbor.jpg" width="80%" caption="Cold Spring Harbor" %}

{% include figure.html image="images/theedge.jpg" width="80%" caption="The Edge" %}

