---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Meet our group! Here are the people that make this all possible.
{:.center}
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
{:.center}
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

Our work is made possible by funding from the following organizations.
{:.center}


{% capture col1content %}
{% include figure.html
  image="images/funders/DARPA.svg"
  caption=""
  link="https://www.darpa.mil/"
  width="400px"
  tooltip="Defense Advanced Research Projects Agency"
%}
{% endcapture %}
{% capture col2content %}
{% include figure.html
  image="images/funders/NSF.svg"
  caption=""
  link="https://www.nsf.gov/"
  width="400px"
  tooltip ="National Sciences Foundation"
%}
{% endcapture %}

{% include two-col.html col1=col1content col2=col2content %}
