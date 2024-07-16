---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact Us


{%
  include button.html
  type="email"
  text="houlahke@mcmaster.ca"
  link="houlahke@mcmaster.ca"
%}
{%
  include button.html
  type="phone"
  text="(905) 525-9140 x 20605"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Michael+G.+DeGroote+Centre+for+Learning+and+Discovery/@43.2610324,-79.9168325,15z/data=!4m2!3m1!1s0x0:0x2784d8d7d243d501?sa=X&ved=1t:2428&ictx=111"
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

<!-- {% include cols.html col1=col1 col2=col2 %} -->

{% include section.html dark=true %}

<!-- {% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %} -->

<!-- {% include cols.html col1=col1 col2=col2 col3=col3 %} -->
