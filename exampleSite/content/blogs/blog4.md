---
title: "Los Angeles and the 10000 km impactor"
date: 2025-03-11T15:07:21+05:30
draft: false 
disqus: true
author: "Gregorio Lince"
tags:
  - Work
  - Social

image: /images/LA.jpeg
description: "I went to LA!"
toc:
---

# The 10000 km impactor

The 10000 km impactor: my greatest foe yet. I ran into the first issues of the code, and have ventured into the depths of the Fortran structure in order to try to fix it. The initial conditions are in a file called hydro.input, and so I have been tweaking 3 main parameters: initial timestep size, time between outputs, and max time. I figured out that since the impactor is so massive, so must be the max time, and increased it proportionally; it worked! I now have the results for the 10000 km impactor, the largest size presented in Dr. Johnson's paper. That culminates, therefore, the recreation of the data that already exists; next step, going smaller. _Wayyyyy_ smaller. Down to millimetric magnitudes, as has been the hope since the beginning of the project. 

This is what the results look like currently:

![Alt text](/images/whatsapp1.jpeg "Current results")