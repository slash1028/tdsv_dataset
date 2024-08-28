---
title: About Us
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}About Us

Acknowledgements: This work is supported by the EPSRC program grant Seebibyte EP/M013774/1: Visual Search for the Era of Big Data.

{%
  include button.html
  type="email"
  text="ruichenzuo@foxmail.com"
  link="ruichenzuo@foxmail.com"
%}
{%
  include button.html
  type="phone"
  text="(852) 867-5309"
  link="+852-5665-8669"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps"
  link="https://maps.app.goo.gl/buxChGFGYULrLfkb9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
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

{% include section.html dark=true %}

{% capture col1 %}
345345345
{% endcapture %}

{% capture col2 %}
234234234
{% endcapture %}

{% capture col3 %}
123123123
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
