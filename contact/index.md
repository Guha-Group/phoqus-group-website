---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Reach out to us in regards to research, media, and project sponsorship. 

{%
  include button.html
  type="email"
  text="jackpost@umd.edu"
  link="jackpost@umd.edu"
%}
{%
  include button.html
  type="phone"
  text="(301) 405-0267"
  link="+1-301-405-0267"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/8YHSBYVuRY7BqxoG8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/gcrb.jpeg"
  caption="Meinel and Grand Challenges Research Building at the University of Arizona"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/keb.jpeg"
  caption="Kim Engineering Building at the University of Maryland, College Park"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
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
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
