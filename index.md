---
---

<!-- # XLAB -->

Kennesaw State University X-Lab
offers a dynamic environment where undergraduate and graduate students collaborate with faculty mentors to conduct cutting-edge research across diverse disciplines.
Our multidisciplinary team aims to revolutionize healthcare through innovative science, including bioengineering, drug discovery, dynamics simulations.

{% include section.html %}

## Highlights

{% capture text %}

Brah brah brah...

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Brah brah brah...

{%
  include button.html
  link="tools"
  text="Browse our tools"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="tools"
  title="Our tools"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Brah brah brah...

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
