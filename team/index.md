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

{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="group: alum"
%}

{% include section.html %}

## Join Us

### Post-doctoral Researcher (x1)
A description of this position.
- Qualification Requirement
- etc.

### Graduate Student (x2)
A description of this position.
- Qualification Requirement
- etc.

### Undergraduate Student (x3)
A description of this position.
- Qualification Requirement
- etc.


## How to Apply
- Send interest email with CV and letters of rec
-

{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
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
