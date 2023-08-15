---
title: Congratulations to Trevor for completing his Master's Thesis!
tags:
  - event-based sensors
  - object tracking
author: Amit Ashok
member: amit-ashok
---

# Hybrid Event and Frame-based System for Target Detection, Tracking, and Identification

### Abstract
A hybrid event-based (EBS) and frame-based sensor system is constructed for the task of
automated object search and track. Due to its relatively low read-out bandwidth and high
temporal resolution, an EBS sensor with a wide field of view (FoV) is employed to monitor
a scene and rapidly detect moving targets. A pan/tilt stage holding a frame-based sensor
is driven using positional information extracted from the EBS data, allowing it to track
desired target position within a global (EBS) frame of reference. The frame-based sensor
with a narrow FoV provides high spatial resolution images of the target, enabling real-time
target identification with a convolutional neural network.
The proposed hybrid sensor system’s performance is quantified using a small drone target
flying at various stand-off distances, speeds, contrasts, and trajectories. Outdoor flights were
conducted against a background of clear sky and a cluttered background of woods/plains.
Detection probability with the EBS is compared against stand-off distance, as well as the
precision and recall of the narrow FoV detection/tracking algorithm.
Using field trials, the hybrid system is shown to detect and track a 30 cm drone at
distances up to 100 m and speeds of 12 m/s. Empirical data on detection probability versus
event rate curves suggest that the system can achieve detection rates of 95% with read-out
bandwidths as low as 30±2 kilobytes/second with 200 microsecond resolution. The reduced
bandwidth from an EBS makes it a potential alternative to a wide FoV frame-based imager
for the search-and-track task.

**Committee:**
- Dr. Amit Ashok (Chair)
- Dr. Jon Koshel
- Dr. Brandon Chalifoux
