---
layout: page
permalink: /
title: Mathematics and Computer Science Projects
---






## Stochastic Analysis 

The following document is a project I initiated in January 2021 as part of my self-study of Stochastic Processes. 
As stochastic analysis is my main research interest, I thought it would essential to have a comprehensive reference covering the foundations, all the way from Measure theory to special topics in Stochastic Partial Differential Equations. 
The document also focuses on filling out details of the proofs given by authors in the field, with the aim being self-containment and completeness. 

[Personal Notes on Stochastic Processes. (Work in progess)]({{ site.baseurl}}/pdfs/sp/main.pdf)


## Traveling Waves of the Hasegawa-Mima Equation

As part of my Master's thesis, I am currently investigating the behavior of traveling wave solutions to the Hasegawa-Mima equation given by 

$$(I-\Delta)\frac{\partial u}{\partial t}=\{u,\Delta u\} + 
    k\frac{\partial u}{\partial y}, $$

where $$\{\cdot,\cdot\}$$ is the Poisson bracket and $$u$$ satisfies *perodic boundary value conditions*.
This equation is used to model turbulent plasma inside a tokamak reactor. 

<div class="row">
  <div class="column">
    <img src="{{ site.baseurl}}/images/ny-modon-plotted.gif" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="{{ site.baseurl}}/images/ny-modon-simulated.gif" alt="Forest" style="width:100%">
  </div>
</div>

 The goal of this inquiry is to adress, numerically and analytically, a certain discrepency between classical results obtained in the literature on one hand, and some more recent results on the other.

 - Report: [Modon Cases for Hasegawa Mima Equation. (Work in progess)]({{ site.baseurl }}/pdfs/hm/mywork.pdf)
 - Code: [Github repository.](https://github.com/adelsaleh/hmSimulator)


## A Simulator for Quantum Algorithms

An ambitious project aimed at simulating MG-QTMs, a generalization of Stationary Rotational Quantum Turing Machines (SR-QTMs). 
It started out as a final year project for [George Zakhour](https://grgz.me/) and Bayan Rafeh and is kept under occasional maintenance.
I am responsible for developing and maintaining the Arithmetic Logic Unit (ALU) of Quantum Virtual Machine (QVM for short) which simulates these QTM's.  

- Report: [A Simulator for Quantum Algorithms.]({{ site.baseurl }}/pdfs/qvm/qvm.pdf)
- Code: [Quantum Virtual Machince Github page.](https://github.com/adelsaleh/qvm)

## Personal Notes on Polynomial Method

These are my personal notes for the Polynomial Method course (MATH 307: Special Topics in Analysis) given by [Dr. Bassam Shayya](https://sites.aub.edu.lb/bshayya/) (American University of Beirut).   

These notes serve as an introduction to the recent method (2010-2015) used by Larry Guth (MIT) to solve the [Erdős distinct distances problem](https://en.wikipedia.org/wiki/Erd%C5%91s_distinct_distances_problem ). 

[Notes on Polynomial Method.]({{ site.baseurl }}/pdfs/307/307.pdf)
