---
layout: default
title: ABINIT
tagline: ABINIT
description: DFT code
---

# Overview

ABINIT is probably the first electronic-structure package to have been released under an open-source license, 
more than twenty years ago. It implements density functional theory (DFT), density-functional perturbation theory (DFPT),
many-body perturbation theory (GW approximation and Bethe-Salpether equation), and more specific or advanced
formalisms, like dynamical mean-field theory (DMFT) and the "temperature-dependent effective potential" (TDEP)
approach for anharmonic effects. Relying on planewaves for the representation of wavefunctions, density and other
space-dependent quantities, with pseudopotentials or projector-augmented waves (PAW), it is well suited for the study
of periodic materials, although nanostructures and molecules can be treated with the supercell technique.

# Components
- [ABINIT](https://www.abinit.org/)
- [Pseudopotentials and PAW datasets for ABINIT](https://www.abinit.org/psp-tables)
- [Input variables](https://docs.abinit.org/variables/#A)
- [Tutorials](https://docs.abinit.org/tutorial/)
- [Forum](https://discourse.abinit.org/top?period=yearly)
- [Wiki](https://wiki.abinit.org/doku.php?id=start)
- [Download](https://www.abinit.org/packages)
- [Compile ABINIT](https://docs.abinit.org/installation/)

# Technical Details
 GreenX is written in Fortran 2008. Functionality needed for testing and error handling is written in C and Python. In the following we provide a few more details for current and future developers of GreenX. 
- [Coding conventions and regression testing](tests.md)
