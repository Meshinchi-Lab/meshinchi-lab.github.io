---
title: Contact
nav:
  order: 5
  tooltip: Get in touch
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

The Meshinchi lab is a part of the Fred Hutch Cancer Center Campus located in the heart of Seattle, Washington.

{%
  include button.html
  type="email"
  text="smeshinc@fredhutch.org"
  link="smeshinc@fredhutch.org"
%}
{%
  include button.html
  type="phone"
  text="206.667.4077"
  link="+1-206-667-4077"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/eMhAnafCptnPabJF9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Soheil.jpeg"
  caption="Dr. Soheil Meshinchi"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/Fred_Hutch.jpg"
  caption="Fred Hutch Cancer Center"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
