---
title: Team
nav:
  order: 3
  tooltip: About our team
---

<!-- # {% include icon.html icon="fa-solid fa-users" %}Team -->

# Welcome to our team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="name: Chloe Yixin Xie" %}

<!-- {% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %} -->

<!-- {% include section.html background="images/background.jpg" dark=true %}


<!-- {% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %} -->

# Graduate students

{% include list.html data="members" component="portrait" filters="role: graduate" %}

# undergraduate students

{% include list.html data="members" component="portrait" filters="role: undergrad" %}

<!-- {% include grid.html style="square" content=content %} -->

# Alumni

{% include list.html data="members" component="portrait" filters="role: alumni" %}

# Visiting Scholars

{% include list.html data="members" component="portrait" filters="role: visiting" %}

# Mascot

{% include list.html data="members" component="portrait" filters="role: mascot" %}


{% include section.html %}

<!-- {% include section.html background="images/background.jpg" dark=true %}
