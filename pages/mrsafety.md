---
layout: page
title: MR Safety
---

## Setting up your MRI Safety policies and Test Lab

### MRI Safety: all responsible

<DIV align="justify">When setting up a new MR system - be it manufactured or built - it is essential to have good safety practices in order to avoid accidents [1,2]. Almost every day, new MR-related injuries are reported from various institutions on the FDA-created MAUDE (Manufacturer and User Facility Device Experience) platform [3]. Looking up this events database is very helpful to remind us to always pay attention to, and adjust when needed, the safety policies in MRI. </DIV><br/>

### MRI Safety Basics and Policies
<DIV align="justify">The first step is to understand where the risks are coming from. Indeed, specific risks are associated to each of the three electromagnetic fields used to make an MR image:</DIV> 
<br/>
-	The static field can exert an attraction force and a torque on any ferromagnetic object or implant. This field is thus linked to the so-called “projectile effect”. Importantly, the static field is always on.  
<br/>
-	The radiofrequency (RF) field is responsible for the potential heating or burn of the subject during the scan. This heating risk will be further increased in presence of a metallic medical device. Radiofrequency fields can also induce voltages on active devices such as pacemaker or neurostimulators, which can lead to unwanted or inefficient stimulation.  
<br/>
-	The gradient fields are responsible for the noise made by the MR machine during a scan that can lead to hearing loss without adequate protection. Furthermore, gradients field can induce Peripheral Nerve Stimulation in the subject, and cause vibration on metallic implants. Similarly to radiofrequency, gradient fields can also induce voltages on active devices. 
<br/>
<DIV align="justify">To make it easier to know if an object or device can safely enter the MR magnet room, and under which conditions an implanted subject may be scanned, the FDA created three labels [4]: </DIV>

![MR Safe](/assets/mrsafety/mrsafe.JPG) <br/>
MR Safe: no known hazard in all MR environments;

![MR Conditional](/assets/mrsafety/mrconditional.JPG) <br/>
MR Conditional: no known hazards in a specified MR environment with specified condition of use;

![MR Unsafe](/assets/mrsafety/mrunsafe.JPG) <br/>
MR Unsafe: hazardous in all MR environments. 

<DIV align="justify">An unknown object can be evaluated with a handheld metal detector and a strong handheld magnet (>1000G). 
<br/>
<br/>
The safety policies should cover the labeling of devices, but also the training for researchers and staff, emergency procedures… To ensure everyone complies with these, it is crucial to clearly explain what the risks are and why the safety policies are established as they are. Among other institutions, the ACR published a very useful guidelines document to help establish these policies [5]; a complete description of the MR Safety roles is available in [6]. </DIV>
<br/>
The Columbia University Zuckerman Institute policies are available [here](https://github.com/imr-framework/imr-framework.github.io/blob/master/assets/mrsafety/MBBI%20MR%20Safety%20Policies.zip) as an example. <br/>

### Numerical Simulation 
<DIV align="justify">A numerical simulation system (hardware, software) can be useful to have insights in physical phenomenon through electromagnetic and thermal simulations. However, it is important to note that simulations results alone cannot be used to make any conclusions about safety, until they are validated experimentally. </DIV> <br/>

### MRI Safety Lab
<DIV align="justify">A dedicated MRI safety lab is recommended, for example to evaluate the impact of the MR fields on a medical implant. Again, several setups and test benches can be established from official standards and publications to study the effect of the static field [7,8], radiofrequency field [9] and gradient fields [10,11]. </DIV> 
<br/>
A list of equipment suggestions for RF studies and RF heating tests is available [here](https://github.com/imr-framework/imr-framework.github.io/blob/master/assets/mrsafety/RF-Safety_Lab.xlsx). <br/>

### References
1.	ABC NEWS, Boy, 6, Killed in Freak MRI Accident. 2001. [link](https://abcnews.go.com/US/story?id=92745&page=1)
2.	Sung SJ et al., Full Thickness Burn on the Finger due to Pulse Oximetry during Magnetic Resonance Imaging in a Conscious Patient. Arch Plast Surg. 2016 Nov; 43(6): 612–613.
3.	MAUDE Database: [link](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfmaude/search.cfm)
4.	FDA Poster on MR Safety Labels: [link](https://www.fda.gov/downloads/Radiation-EmittingProducts/RadiationEmittingProductsandProcedures/MedicalImaging/MRI/UCM528081.pdf)
5.	Kanal E et al., J. Magn. Reson. Imaging 2013;37:501–530.
6.	Calamante F et al., J. Magn. Reson. Imaging, 44: 1067-1069
7.	ASTM F2213-17, ASTM International, West Conshohocken, PA, 2017, [link](https://doi.org/10.1520/F2213-17)
8.	ASTM F2052-15, ASTM International, West Conshohocken, PA, 2015, [link](https://doi.org/10.1520/F2052-15) 
9.	ASTM F2182-11a, ASTM International, West Conshohocken, PA, 2011, [link](https://doi.org/10.1520/F2182-11A)  
10.	ISO/TS 10974:2018, International Organization for Standardization, Geneva, Switzerland, [link](https://www.iso.org/standard/65055.html)
11.	P. Ferry et al., Proc. Intl. Soc. Mag. Reson. Med. 25 (2017)
