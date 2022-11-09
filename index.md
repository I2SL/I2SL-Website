---
title: Home
---

# Optics and Algorithms

Welcome to our lab page!

We are a computational imaging lab in the [Wyant College of Optical Sciences](https://www.optics.arizona.edu/) at the University of Arizona. We develop new imaging modalities that perform optimally with respect to task-specific information measures. Our current research efforts include x-ray imaging for materials classification, event-based imaging, and quantum-limited superresolution imaging.

{:.center}
{%
  include link.html
  type="github"
  icon=""
  text="I<sup>2</sup>SL GitHub"
  link="greenelab/lab-website-template"
  style="button"
%}

# Highlights

{% capture text %}
Our research involves the joint design of optics and algorithms allowing us to process signals in the optical and electrical domain.
Across our projects we take an information theoretic approach to our system design.

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research_thumbnail.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
The algorithms our lab has developed are available for you to try! Check out our
project repositories and datasets.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/resources_thumbnail.jpg"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
Come learn about the people doing this work!

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
