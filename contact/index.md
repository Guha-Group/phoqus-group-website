---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Reach out to us in regards to research, media, and project sponsorship. We are always looking for new collaborators and students to join our team.

Prof. Guha's Office Address: Room 2236, Kim Engineering Building, 8228 Paint Branch Drive, University of Maryland, College Park, MD 20742

Coordinator Office: Room 2140, Kim Engineering Building, 8228 Paint Branch Drive, University of Maryland, College Park, MD 20742

{%
  include button.html
  type="email"
  text="<smalani@umd.edu>"
  link="<smalani@umd.edu>"
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
  link="<https://maps.app.goo.gl/8YHSBYVuRY7BqxoG8>"
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
> That atoms and the vacuum were the beginning of the universe; and that everything else existed only in opinion.

- Democritus
{% endcapture %}

{% capture col2 %}
> The true logic of this world is to be found in the theory of probability.

- James Clerk Maxwell
{% endcapture %}

{% capture col3 %}
> The Infinite! No other question has ever moved so profoundly the spirit of man.

- David Hilbert
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
