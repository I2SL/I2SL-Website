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
  filters="role: pi, status: current"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: admin, status: current"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd, status: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: masters, status: current"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad, status: current"
%}


{% include section.html %}

## Former Members
Here are our former lab members! Check out the exciting work they've gone off to do!

{%
  include list.html
  data="members"
  component="portrait"
  filters="status: former"
%}

{% include section.html %}

{% include link.html icon="fas fa-hands-helping" text="Join the Team" link="join" style="button" %}
{:.center}

## Funding

Our work is made possible by funding from the following organizatiosn.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/funders/DARPA.png"
  link1="https://www.darpa.mil/"
  tooltip1="Defense Advacned Research Projects Agency"

  image2="images/funders/NSF.svg"
  link2="https://www.nsf.gov/"
  tooltip2="National Sciences Foundation"
%}
