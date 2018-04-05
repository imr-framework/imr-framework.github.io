---
layout: page
title: iMR Framework
---

[`imr_framework`](https://github.com/imr-framework/imr-framework) (previously known as `pulseq-gpi` \[[1\]](#references)) is a one-stop Python package containing all the tools required to work on the MR pipeline:
- acquisition (`imr_framework.pulseq` or `imr_framework.pulseq_gpi`)
- reconstruction (`imr_framework.pulseq_gpi`)
- visualization (`imr_framework.pulseq_gpi`)

Soon, iMR Framework will implement deep-learning based MR image reconstruction techniques.

### `imr_framework.pulseq`:
Python 3.6 based implementation of the [Pulseq](http://pulseq.github.io) framework [\[2\]](#references). Users already familiar with `Pulseq` (in Matlab) should be comfortable with `imr_framework.pulseq`.

#### SETTING UP `imr_framework.pulseq`
The following dependencies are required to program pulse sequences in Python, *imr_pulseq*:
- [numpy](http://www.numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [hdf5](http://www.h5py.org/)

1. Install [Python 3.6](https://www.python.org/downloads/)
2. Clone [this](https://github.com/imr-framework/imr-framework) repo
3. Explore the bundled demo pulse sequence demos

Bundled pulse sequence demos:
- Gradient Recalled Echo
- Spin Echo
- Spin Echo EPI
- 2D Multi-slice Radial
- 2D Multi-slice Spiral

---
### `imr_framework.pulseq_gpi`:
Python 3.6 based implementation of `imr_framework.pulseq` in [GPI](http://gpilab.com) \[[3\]](#references). `imr_framework.pulseq_gpi` allows users to leverage the pulse sequence design capabilities of `imr_framework.pulseq` with GPI's graphical ease-of-use. GPI is a visual environment for developing and organizing scientific algorithms. The basic UI elements in GPI are 'Nodes' and 'Widgets'.

A brief explanation of designing pulse sequences in GPI is as follows:
- 'Nodes' are the primary UI elements used to design and visualize pulse sequences
- 'Widgets' are configurable UI elements used to set the pulse sequence parameters
- A pulse sequence is designed by **chaining** two or more 'Nodes'
- The pulse sequence can be exported as a `.seq` file (file-format as described in [1])

#### SETTNG UP `imr_framework.pulseq_gpi`
0. Install [GPI](http://gpilab.com/)
1. Clone [this](https://github.com/imr-framework/imr-framework) repo
2. Open GPI
3. Click on *Config* > *Generate User Library*. This generates a *gpi* folder in the current user's home directory
4. Place the *imr* and *mr_nodes* folders from the extracted *pulseq-gpi* folder inside this auto-generated folder. On Mac - */Users/[user-name]/gpi/[user-name]/*
5. In GPI, click on *Config* > *Scan for new nodes*

That's it! Now, the *pulseq-gpi Nodes* should show up when you right-click anywhere on the canvas.

`imr_framework.pulseq_gpi` comes bundled with example GPI networks that are runnable out-of-the-box, configured to display plots for a single repetition. Networks for the following pulse sequences are included:
- Gradient Recalled Echo
- Spin Echo
- Spin Echo-EPI
- 2D Multi-slice Radial
- 2D Multi-slice Spiral

To run a GPI network, simply drag and drop the network onto the GPI canvas. Then, open the *ConfigSeq Node* by right-clicking and click on *Compute Events*. Finally, open the *GenSeq Node* by right-clicking and click on *Compute Events* to construct the pulse sequence. The plots are viewable in the *Matplotlib Node*.

### REFERENCES
[1] Sravan, R. Keerthi, et al. "Pulseq-Graphical Programming Interface: Open source visual environment for prototyping pulse sequences and integrated magnetic resonance imaging algorithm development." Magnetic resonance imaging (2018).\\
[2] Layton, Kelvin J., et al. "Pulseq: A rapid and hardware‐independent pulse sequence prototyping framework." Magnetic resonance in medicine 77.4 (2017): 1544-1552.\\
[3] Zwart, Nicholas R., and James G. Pipe. "Graphical programming interface: a development environment for MRI methods." Magnetic resonance in medicine 74.5 (2015): 1449-1460.

### CONTRIBUTING
Fork and PR!
