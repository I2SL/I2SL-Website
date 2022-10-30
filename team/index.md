---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Meet our group! Here are the people that make this all possible.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: masters"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: admin"
%}

Here are our former lab members! Check out the exciting work they've gone off to do!
{%
  include list.html
  data="members"
  component="portrait"
  filters="group: alum"
%}

{% include section.html %}

{% include link.html icon="fas fa-hands-helping" text="Join the Team" link="join" style="button" %}
{:.center}

## Funding

Our work is made possible by funding from the following organization.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

  image2="images/photo.jpg"
  link2="https://nasa.gov/"
  tooltip2="Cool Institute"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"

  image4="images/photo.jpg"
  link4="https://nasa.gov/"
  tooltip4="Cool Foundation"

  image5="images/photo.jpg"
  link5="https://nasa.gov/"
  tooltip5="Cool Institute"

  image6="images/photo.jpg"
  link6="https://nasa.gov/"
  tooltip6="Cool Initiative"
%}
