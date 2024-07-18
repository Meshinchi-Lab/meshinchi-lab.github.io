---
title: Team
nav:
  order: 3
  tooltip: Meet Our Lab
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lab Members

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: manager" %}
{% include list.html data="members" component="portrait" filters="role: fellow" %}
{% include list.html data="members" component="portrait" filters="role: supervisor" %}
{% include list.html data="members" component="portrait" filters="role: bioinformatician" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|manager|fellow|supervisor|bioinformatician)" %}

{% include section.html background="images/background.jpeg" dark=true %}

Collaborators

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
