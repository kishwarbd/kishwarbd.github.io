---
title: "Research Overview"
permalink: /research/
author_profile: true
---

My work is in the general areas of **high-performance computing (HPC) systems**, **cyber-physical systems**, and **quantum computing systems**. For last couple of years, I have been focused on _accurate_, _scalable_, and _efficient_ modeling and simulation of HPC systems.

## Performance Prediction Modeling of HPC Systems

### Overview
Recent years have witnessed dramatic changes in HPC systems to accommodate the increasing computational demand of scientific applications. New architectural changes, including the rapid growth of multi-core and many-core systems, deeper memory hierarchies, complex interconnection fabrics that facilitate more efficient data movement for massive-scale scientific applications, have complicated the design and implementation of the HPC applications. Modeling and simulation plays an important role for analyzing application performance and evaluating design alternatives of complex systems. We developed Performance Prediction Toolkit (PPT), a simulator mainly to facilitate rapid and accurate performance prediction of large-scale scientific applications on existing and future HPC architectures.

PPT is a library of models of computational physics applications, middleware, and hardware that allows users to predict execution time by running stylized pseudo-code implementations of physics applications. Our middleware model implementation include both message-passing interface (MPI) and open multi-processing (OpenMP). The Hardware models exist for interconnection networks and compute nodes. The interconnection models implement different network topologies (e.g., torus, dragonfly, fat-tree) and can be set up with different configurations. The PPT hardware model of a compute core (such as a Haswell core) consists of a set of parameters, such as clock speed, memory hierarchy levels, their respective sizes, cache-lines, access times for different cache levels, average cycle counts of ALU operations, etc. Our developed models are demonstrated to be accurate, scalable, and efficient.

### Selected Publications
* **Kishwar Ahmed**, Mohammad Obaida, Jason Liu, Stephan Eidenbenz, Nandakishore Santhi, and Guillaume Chapuis, “An Integrated Interconnection Network Model for Large- Scale Performance Prediction,” at [ACM SIGSIM PADS 2016](https://www.acm-sigsim-pads.org/). [[paper](https://dl.acm.org/citation.cfm?id=2901396)]

* **Kishwar Ahmed**, Jason Liu, Stephan Eidenbenz, and Joe Zerr, “Scalable Interconnection Network Models for Rapid Performance Prediction of HPC Applications,” at ([HPCC 2016](http://www.swinflow.org/confs/2016/hpcc/)). [[paper](https://ieeexplore.ieee.org/document/7828492/)]

### Collaborators

## Energy-Efficient Modeling of HPC Systems

### Overview

### Selected Publications

### Collaborators

## Sustainability of Cyber-Physical Systems