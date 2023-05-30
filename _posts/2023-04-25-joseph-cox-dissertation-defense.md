---
title: Congratulations to Joe for defending his dissertation!
tags:
  - event-based sensors
author: Amit Ashok
member: amit-ashok
---

# Integration of Event-Based Sensing With Traditional Imaging Approaches

### Abstract
The neuromorphic Event-Based Sensor (EBS) is an imaging sensor that asynchronously outputs imaging data as events only when and where a temporal change in scene radiance is detected. An advantage of EBS is its lower read-out bandwidth (up to orders-of-magnitude) relative to equivalently sized conventional frame-based sensor. This readout bandwidth advantage directly leads to related potential advantages such as low sensor power, low processing latency, and high real-time capabilities. Disadvantages of using EBS include potentially lower task performance, higher read-out bandwidth in sub-optimal conditions, a high minimum contrast threshold, and relatively poor understood compatibility with traditional imaging approaches and systems. However, quantified information on these costs and benefits is unavailable, preventing the sensor from adoption in defense and commercial systems. The overarching goal of this dissertation work is to understand these costs and benefits, formalized as two questions: (a) What are quantified costs and benefits of using EBS for defense imaging applications? and (b) How does EBS integrate with traditional optics technology and methods?

We pursue three research directions to explore these questions. First, an image stabilization system is integrated with EBS, which is useful in conditions where the sensor is imaging a cluttered scene from a moving platform. Here, the relative motion of the clutter generates significant events that eliminate EBS’s bandwidth advantages. By canceling the relative motion, the method demonstrates a recovery of one to two orders of magnitude bandwidth advantage. Second, a test bed for comparing EBS and frame-based sensors in moving object detection tasks is demonstrated using receiver operating characteristic (ROC) analysis. For a uniform background, a performance gap between EBS and frame-based imaging system was demonstrated and analyzed, demonstrating that the EBS can produce results similar to a high-noise frame-based sensor. For cluttered backgrounds, motion is shown to degrade both sensors’ detection performance, while also degrading EBS’s bandwidth advantage. Image stabilization, as previously discussed, is then applied to the test bed to recover detection performance and EBS’s bandwidth advantage. Third, a coherent optical high-pass filter is integrated with EBS to increase scene contrast, enabling lower contrast objects to be detectable. Contrast enhancement expectations were simulated and matched with experimental measurements, demonstrating an effective 3x decrease in the minimum detectable object contrast with the applied optical filter.

Each direction addressed the dissertation goal and associated questions in different ways, providing information about EBS’s costs and benefits. The first direction demonstrated the new bandwidth advantage of integrating EBS with traditional image stabilization and extended the EBS bandwidth advantage to additional scenarios. The second direction simultaneously quantified EBS’s task performance cost and EBS’s bandwidth benefits and illustrated the integration of EBS into traditional frame-based imaging systems. The third direction addressed and mitigated the limited contrast performance and demonstrated benefits of using Fourier Optics techniques with EBS. Overall, we expect that the quantification of the costs and benefits justifies EBS usage in larger complex engineering problems. The integration with traditional imaging should also lead to new EBS systems that can solve imaging problems in new, creative, and valuable ways.

**Committee:**
- Dr. Amit Ashok (Chair)
- Dr. Ron Driggers
- Dr. Jon Koshel
