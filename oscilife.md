---
layout: page
title: OsciLife
subtitle: A code for 1+1-dimensional simulations of oscillons
---

OsciLife is a simple C++ code that simulates the evolution of oscillons in one spatial dimension, and outputs relevant quantities like the profile or the energy distribution. 
The user only needs to specify the field potential and its derivative.

The initial distribution of the oscillon can be specified as a radial function or read it from a text file. The boundary conditions
are dealt with a truncation function that subtracts the field waves as they approach the boundary, see <a href="https://arxiv.org/pdf/1907.00611.pdf" target="_blank" rel="noopener noreferrer">JCAP 1910 (2019) no.10, 002</a>
for more details. The code is also parallelized with OpenMP, in case you have super long-lived oscillons!

I plan to release the code publicly in the future.

