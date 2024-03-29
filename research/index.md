---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# <i class="fas fa-microscope"></i>Research Overview

The Intelligent Imaging and Sensing Lab I<sup>2</sup>SL , under the leadership of Prof. Amit Ashok, focuses on developing novel concepts and approaches in image science with the goal of quantifying and improving task-based performance for a variety of tasks, e.g. image formation, target tracking/detection/classification, across different modalities spanning the electromagnetic spectrum from radio frequencies (RF), infrared/visible (EO/IR) to X-rays. This inter-disciplinary area of research in image science draws from multiple disciplines such as, physical optics, multi-dimensional signal processing, inverse problems, statistical inference, information theory, optimization theory, and seeks to: (a) quantify performance limits of imaging modalities and (b) develop system (measurement) design strategies towards achieving these limits using robust and scalable engineering design principles that can be implemented in lab and real-world operational scenarios.

More specifically, the overarching theme of our research group is to develop scalable information-theoretic approaches to quantify the fundamental limits of a particular imaging/sensing system design using physics-based system forward models and statistical scene models. We have successfully applied such information-theoretic system analysis and design principles to demonstrate significant and realizable system performance improvements for various RF/EO/IR, and X-ray imaging and sensing systems, within the framework of computational imaging. More recently, we have been also pursuing fundamental performance limits of optical imaging and sensing systems arising from the quantum description of electromagnetic fields, using tools from quantum information, estimation, and detection theory. For example, we have made contributions in the analysis of two-point source resolution and extended line source estimation problems in the sub-Rayleigh regime limited fundamentally only by the quantum optical description of light and physically realizable measurement of such light fields.

{% include section.html %}

# Current Projects

{% capture text %}
Natural scenes are often sparse in a wavelet basis. We are employing a multi-parameter adaptive Bayesian measurement strategy to estimate the wavelet coefficients of sub-rayleigh features with imposed sparsity priors.
Our algorithm exercises a measurement feedback loop wherein we sort the optical field into a set of orthogonal spatial modes and subsequently count the number of photons detected in each mode.
At each adaptation our algorithm supplies a spatial modal basis that minimizes the joint mean-square-error of all the estimation parameters.

{%
  include link.html
  type="github"
  link="I2SL/Compressive-Quantum-Imaging"
  text="Project Repository"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research/CQI_flowchart.svg"
  link="research"
  title="Compressive Quantum Superresolution Imaging"
  text=text
%}

{% capture text %}
The 2023 published Hybrid Event and Frame-based System for Target Detection, Tracking, and Identification is being modified to simultaneous UAV detection, tracking, and identification. The system leverages the change detection ability of the Event-Based Sensor (EBS), with relatively low read-out bandwidth for the Unmanned Aerial Vehicle (UAV) target detection task within a wide FoV. The frame-based sensor with a narrow FoV provides high spatial resolution images of the target, enabling real-time target identification with a convolutional neural network (CNN). We are testing multiple-size YOLO CNN image classification models to detect, track, and identify multiple UAVs within a given scene.

{%
  include link.html
  type="github"
  link="I2SL/Event-Based-Imaging"
  text="Project Repository"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research/"
  link="research"
  title="Multi-Target Hybrid Event and Frame-Based Drone Identification"
  text=text
%}


{% capture text %}
Combining event-based and rolling shutter data may offer several order-of-magnitude enhancement in temporal-spatial resolution for video than alternative global shutter systems of similar cost can produce. Since interpolation is computationally demanding for high resolution sensors, we are developing artificial neural networks that may provide a means of encoding and matching the feature vectors from both cameras. We investigate how such a technique can be applied to wavefront sensing applications to enhance signal reconstruction of the sampled wavefronts.

{%
  include link.html
  type="github"
  link="I2SL/"
  text="Project Repository"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/"
  link="research"
  title="Optical Temporal Super-Resolution in Wavefront Sensing"
  text=text
%}


{% include section.html %}

# Past Projects

{% capture text %}
We construct a Bayesian adaptive (greedy) measurement scheme for multiparameter estimation. We illustrate our proposed measurement scheme with the application of localizing a cluster of point emitters in a highly sub-Rayleigh angular field-of-view, an important problem in fluorescence microscopy and astronomy.
Our algorithm translates to a multi-spatial-mode transformation prior to a photon-detection array, with electro-optic feedback to adapt the mode sorter. We show that this receiver performs superior to quantum-noise-limited focal-plane direct imaging.
{%
  include link.html
  type="github"
  link="I2SL/Quantum-Imaging-Constellations"
  text="Project Repository"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research/constellation_personick.JPG"
  link="research"
  title="Constellation Quantum Superresolution Imaging"
  text=text
%}


{% include section.html %}

# Publications

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
