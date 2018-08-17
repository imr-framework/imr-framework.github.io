---
layout: page
title: AMRI
---

### Why autonomous?
Globally, there are **0.46 MRI scanners per 100,000** people. In comparison, the United States has 39 [[1]](#references) while the **low-income countries have 0.01**. In the United States, as of 2009, the annual wastage related to all healthcare spending annually is 700 billion USD with imaging diagnostics being responsible for at least **125 – 200 billion USD** [[2]](#references). The role of autonomous scanners to alleviate these challenges of reaching a larger population and minimizing spending related to MRI is being envisioned.

### And what is MR Value?
MR value can be defined to the patient as the ratio of actionable diagnostic information to the costs or time incurred. A technically relevant definition of MR value is: ratio of contrast-to-noise ratio (CNR) to the total scanner (table) time.

### The Intelligent Physical System (IPS)
The National Science Foundation in its call for proposals for the Smart and Autonomous Systems program [[3]](#references) defines an IPS as being characterised by the following:
- Cognizant
- Taskable
- Adaptive
- Ethical

The above features would essentially make an IPS knowledge-rich, and capable of long-term autonomy with minimal human intervention.

### Utilization of file standards
AMRI can be easily built, rebuilt and deployed as it leverages 4 existing file standards and introduces 1 new file standard. These file standards are:
- EMR file standard for subject information encryption
- Situation report (Sitrep) file standard for sampling MR system state (introduced in this work)
- Pulseq file standard for multi-vendor pulse sequence programming
- ISMRMRD file standard for acquired raw data
- DICOM file standard for reconstructed image data

An example of some of these file standards as part of experiments can be found [here](https://github.com/imr-framework/imr-framework/tree/master/amri).
