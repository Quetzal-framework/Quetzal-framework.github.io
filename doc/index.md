# Welcome to the Quetzal framework

This organization aims at gathering code that is of general use for Statistical
Phylogeography. In the present state, in mainly focuses on simulating neutral genetic
diversity in complex landscapes for inference purposes.

The general structure of this framework is the following, in order of increasing
granularity:

* [Quetzal-CoaTL](https://becheler.github.io/softwares/quetzal-CoalTL/home/) :
  a library of C++ generic components for building simulators of molecular diversity. It is the most
  technical, but also the most general project on this list. Meaning, if you are
  interested by simulating genetic diversity, that may be a useful repository to check out.
* [Quetzal-EGGS](https://github.com/Becheler/quetzal-EGGS) :
  this repository aims at gathering ready-to-use simulators for a variety of users.
  These simulators do not aim at solving the life equation, nor do they pretend to match existent closed-source
  softwares (e.g. Splatche3) in their complexity and generality. Rather, the project
  aims at encouraging the community to master modern C++ tools
  to implement problem-specific, yet tested, open-source and peer-reviewable
  implementations that precisely match their needs. Anyone is welcome to add or ask for new simulators.
* [Quetzal-EGGS](https://github.com/Becheler/quetzal-CRUMBS) :
  this Python package aims at solving common tasks and problems that
  tend to appear when using spatially explicit simulators, like preparing a landscape
  for a simulation.
* [Quetzal-NEST](https://hub.docker.com/r/arnaudbecheler/quetzal-nest) :
  This repository contains a Dockerfile that provides a reproducible environment
  for this kind of analysis. You may find the related Docker image (hosted on Dockerhub)
  to be useful when needing to configure an environment to run simulations on
  distributed clusters where you don't have admin privileges.
* [Quetzal_on_OSG](https://github.com/Becheler/quetzal_on_OSG) :
  this repository is an application example that uses Open Science Grid
  to run a full analysis.

The general articulation of the framework is represented here:

![The Quetzal framework](pipeline_SOFTWARES.svg)
