---
permalink: /
title: "Computational Physics @GT"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Research Summary
======

At the Computational Physics Group, we work on developing developing fast and accurate solutions to multiphase compressible flow problems by utilizing state-of-the-art numerical and computational models. These models are often combined with machine learning tools to obtain better predictions. Some applications of these numerical solvers include artificial heart valves, burst-wave lithotripsy and aerobreakup of liquid droplets. In particular, we are currently working on developing MFC, an open source multi-phase  and multi-component fluid flow solver that also incorporates sub-grid scale models for bubbly flow. MFC is GPU-accelerated via OpenACC and demonstrates near ideal weak and strong scaling on large supercomputers. 40X speedup is observed for a single compute node on OLCF Summit. Ideal weak scaling is achieved for upto 13824 GPUs on Summit. CUDA Aware MPI is used to reduce MPI communication time between GPUs. 
