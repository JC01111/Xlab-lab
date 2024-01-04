---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

This is the contact area.

{%
  include button.html
  type="email"
  text="xxx@kennesaw.edu"
  link="xxx@kennesaw.edu"
%}
{%
  include button.html
  type="phone"
  text="(xxx)xxx-xxxx"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% raw %}
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3310.1064383674875!2d-84.52102052248156!3d33.9383904237305!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88f5115510312027%3A0x81ce76f9703afb9c!2sKennesaw%20State%20University!5e0!3m2!1sen!2sus!4v1704409890375!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
{% endraw %}

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

<!-- {% include section.html dark=true %}

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

<!-- {% include cols.html col1=col1 col2=col2 col3=col3 %} -->
