---
title: Contact
nav:
  order: 5
  tooltip: Get in touch
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

The Meshinchi Lab believes strongly that collaboration can lead to better science! Please get in touch with us. 

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
  image="images/Soheil.jpg"
  caption="Dr. Soheil Meshinchi"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
