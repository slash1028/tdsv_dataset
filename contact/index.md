---
title: About Us
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}About Us

Acknowledgements: Thanks to Xuerui Huang, Chong-Xin Gan, and Lishi Zuo for the help in manual check and participation in discussion.

{%
  include button.html
  type="email"
  text="ruichen.zuo@connect.polyu.hk"
  link="ruichen.zuo@connect.polyu.hk"
%}
{%
  include button.html
  type="phone"
  text="(852) 5665-8669"
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
  image="images/PolyU Logo.png"
  caption="The Hong Kong Polytechnic University"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/EEE.png"
  caption="Department of Electrical and Electronic Engineering"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
This dataset is used for paper: "The Sub-3Sec Problem: From Text-Independent to Text-Dependent Corpus"
{% endcapture %}

{% capture col2 %}
234234234
{% endcapture %}

{% capture col3 %}
123123123
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
