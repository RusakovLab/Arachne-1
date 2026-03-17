# ARACHNE

**Neural & Neuroglial Network Simulation Environment**  
*Version 3.0*

---

## Overview

ARACHNE is a simulation environment designed for neural and neuroglial network modelling, built around pre-optimised parallel algorithms for remote computation paired with an intuitive local interface.

It enables neuroscientists without an IT background to construct biophysically detailed network models incorporating diverse mechanisms of nerve and astroglial cells. Network complexity is bounded only by available remote computing resources — not by the modelling kernel or interface.

---

## Installation

### Recommended: Installer for Windows

Download **Arachne_web.exe** — a self-contained installer for Windows that supports computation both on a local machine and on a remote cluster.

### Available Versions

| Version | Description |
|---|---|
| **Demo** | Pre-compiled executables + `Core/` directory for cluster use. Compiled under MATLAB R2013a. Requires [MATLAB Runtime R2013a](https://www.mathworks.com/products/compiler/mcr/) on machines without MATLAB. Launch via `START_Arachne.exe`. See `Manual.docx` for details. |
| **Full** | Contains `host/` and `worker/` directories for deploying ARACHNE on a Linux or Windows cluster, with a Windows host machine running MATLAB. |
| **MATLAB** | Host-side MATLAB source files and batch scripts controlling communication between the host computer and a pre-installed cluster. Place anywhere on a Windows machine. See `Readme.md` for setup instructions. |
| **Mobile** | Files for mobile devices running a mobile OS. |

---

## Examples

A set of example parameter files covering five different network configurations is available here:

[`ExamplePLOS/`](https://github.com/LeonidSavtchenko/Arachne/tree/master/ExamplePLOS)

These provide the input parameters needed to reproduce the figures in the associated *PLOS Computational Biology* publication.

---

## Documentation

Full manual and API reference:  
[https://github.com/LeonidSavtchenko/Arachne](https://github.com/LeonidSavtchenko/Arachne)

---

## Contact

**Leonid Savtchenko** — [savtchenko@yahoo.com](mailto:savtchenko@yahoo.com)

[Synaptic Imaging Group](http://www.ucl.ac.uk/ion/departments/epilepsy/themes/synaptic-imaging)  
Department of Clinical and Experimental Epilepsy  
UCL Queen Square Institute of Neurology  
University College London, UK
