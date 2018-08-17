---
layout: page
title: AMRI
---

## Autonomous Magnetic Resonance Imaging

Check out a concept video on [YouTube](https://www.youtube.com/watch?v=2XroYwUxzD4).

### Why autonomous?
Globally, there are **0.46 MRI scanners per 100,000** people. In comparison, the United States has 36.72 [[1]](#references) while the **low-income countries have 0.01**. In the United States, as of 2009, the annual wastage related to all healthcare spending annually is 700 billion USD with imaging diagnostics being responsible for at least **125 – 200 billion USD** [[2]](#references). The role of autonomous scanners to alleviate these challenges of reaching a larger population and minimizing spending related to MRI is being envisioned [[3]](#references).

### And what is MR Value?
MR value can be defined to the patient as the ratio of actionable diagnostic information to the costs or time incurred. A simplified and technically relevant definition of MR value is: ratio of contrast-to-noise ratio (CNR) to the total scanner (table) time.

### MRI scanner as an Intelligent Physical System (IPS)
AMRI is capable of transforming a conventional MR system into an IPS that can be characterized by the following capabilities:
- Cognizant
- Taskable
- Adaptive
- Ethical

The above capabilities would deliver an IPS that is knowledge-rich, and capable of long-term autonomy with minimal human intervention and supervision.

### Utilization of file standards
AMRI can be easily built, rebuilt and deployed as it leverages 4 existing file standards and introduces 1 new file standard. These file standards are:
- EMR file standard for subject information encryption
- Situation report (Sitrep) file standard for sampling MR system state (introduced in this work)
- Pulseq file standard for multi-vendor pulse sequence programming
- ISMRMRD file standard for acquired raw data
- DICOM file standard for reconstructed image data

An example of some of these file standards as part of experiments can be found [here](https://github.com/imr-framework/imr-framework/tree/master/amri). YouTube demos can be found [here](https://youtu.be/3107aoRv2Vs) and [here](https://youtu.be/k-HAa3cADqQ).

### References
[1] Atlas of MS 2013, https://www.msif.org/wp-content/uploads/2014/09/Atlas-of-MS.pdf

[2] Kelley, Robert. "Where can $700 billion in waste be cut annually from the US healthcare system." Ann Arbor, MI: Thomson Reuters 24 (2009).

[3] Wang, Ge, et al. "Image Reconstruction is a New Frontier of Machine Learning." IEEE transactions on medical imaging 37.6 (2018): 1289-1296.
