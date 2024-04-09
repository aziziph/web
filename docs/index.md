---
layout: default
title: ABINIT
tagline: ABINIT
description: DFT code
---

# Overview

A new open-source library that supports exascale implementations of Green's-function-based methodologies. Its layered design will separate higher-level functionalities (distinguishing between code-independent and code-family-specific parts) from architecture-dependent numerical routines, common to all code families.

Currently, our library supports the following electronic structure methods:

- conventional and low-scaling RPA
- low-scaling \\(GW\\)
- Laplace-transformed direct MP2

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
