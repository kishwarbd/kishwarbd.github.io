---
title: "Research"
permalink: /research/
author_profile: true
---

My work is in the general areas of **high-performance computing (HPC) systems**, **cyber-physical systems**, and **quantum computing systems**. For last couple of years, I have been focused on accurate, scalable, and efficient modeling and simulation of HPC systems.

## Performance Prediction Modeling of HPC Systems

### Overview
Recent years have witnessed dramatic changes in HPC systems to accommodate the increasing computational demand of scientific applications. New architectural changes, including the rapid growth of multi-core and many-core systems, deeper memory hierarchies, complex interconnection fabrics that facilitate more efficient data movement for massive-scale scientific applications, have complicated the design and implementation of the HPC applications. Modeling and simulation plays an important role for analyzing application performance and evaluating design alternatives of complex systems. We developed Performance Prediction Toolkit (PPT), a simulator mainly to facilitate rapid and accurate performance prediction of large-scale scientific applications on existing and future HPC architectures.

PPT is a library of models of computational physics applications, middleware, and hardware that allows users to predict execution time by running stylized pseudo-code implementations of physics applications. Our middleware model implementation include both message-passing interface (MPI) and open multi-processing (OpenMP). Our hardware model implementation includes models for interconnection networks and compute nodes. The interconnection models implement different network topologies (e.g., torus, dragonfly, fat-tree) and can be set up with different configurations. The PPT hardware model of a compute core (such as a Haswell core) consists of a set of parameters, such as clock speed, memory hierarchy levels, their respective sizes, cache-lines, access times for different cache levels, average cycle counts of ALU operations, etc. Our developed models are demonstrated to be scalable, fast,  accurate, and efficient.

### Selected Publications
* **Kishwar Ahmed**, Mohammad Obaida, Jason Liu, Stephan Eidenbenz, Nandakishore Santhi, and Guillaume Chapuis, “An Integrated Interconnection Network Model for Large- Scale Performance Prediction,” at [ACM SIGSIM PADS 2016](https://www.acm-sigsim-pads.org/). [[paper](https://dl.acm.org/citation.cfm?id=2901396)]
* **Kishwar Ahmed**, Jason Liu, Stephan Eidenbenz, and Joe Zerr, “Scalable Interconnection Network Models for Rapid Performance Prediction of HPC Applications,” at [IEEE HPCC 2016](http://www.swinflow.org/confs/2016/hpcc/). [[paper](https://ieeexplore.ieee.org/document/7828492/)]

### Collaborators
* Stephan Eidenbenz, [Los Alamos National Laboratory](https://www.lanl.gov/)
* Nandakishore Santhi, [Los Alamos National Laboratory](https://www.lanl.gov/)
* Gopinath Chennupati, [Los Alamos National Laboratory](https://www.lanl.gov/) 

## Energy-Efficient Modeling of HPC Systems

### Overview
HPC systems (e.g., supercomputers) can consume an enormous amount of electricity during their operation, and consequently incur significant energy consumption and energy cost. For example, China’s 34-petaflops Tianhe-2 supercomputer has been reported to consume almost 18MWs of power, sufficient to power a small town of 20,000 residences. We address supercomputer’s massive energy consumption problem through demand response participation. Demand response aims at energy reduction and power stability during peak load periods, e.g., during an emergency or extreme weather conditions, by providing financial incentives to consumers to reduce energy consumption. 

We developed energy-efficient algorithms to reduce HPC systems’ energy consumption during emergency demand response periods (when supply shortage situations or emergency conditions occur). Our proposed power and performance prediction model, job scheduling, and resource allocation schemes reduce HPC system’s energy consumption during demand response periods. We also addressed economic demand response (which requires voluntary participation) participation from HPC systems. We developed a rewarding scheme to encourage the willing participation of the HPC users in demand response programs based on contract theory (a tool from microeconomics). Our developed model benefits all the involved participants: HPC system can reduce energy cost, HPC users can earn reward from such participation and energy service provider can achieve grid stability through overall energy reduction.

### Selected Publications
*  **Kishwar Ahmed**, Jason Liu, and Xingfu Wu, “An Energy Efficient Demand-Response Model for High Performance Computing Systems,” at [IEEE MASCOTS 2017](https://mascots2017.cs.ucalgary.ca/). [[paper](https://ieeexplore.ieee.org/document/8107444/)]
* **Kishwar Ahmed**, Jason Liu, and Kazutomo Yoshii, “Enabling Demand Response for HPC Systems Through Power Capping and Node Scaling,” at [IEEE HPCC 2018](https://cse.stfx.ca/~hpcc2018/). [[paper](https://kishwarbd.github.io/files/paper-hpcc18.pdf)]

### Collaborators
* Xingfu Wu, [Argonne National Laboratory](https://www.anl.gov/)
* Kazutomo Yoshii, [Argonne National Laboratory](https://www.anl.gov/)
* Jesse Bull, [Department of Economic, FIU](https://economics.fiu.edu/)

## Sustainability of Cyber-Physical Systems