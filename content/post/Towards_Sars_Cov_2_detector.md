+++
Description = ""
date = "2020-04-20T22:50:30+08:00"
title = "Towards a SARS-COV-2-Virion-Detektor"
menu = "main"
toc = true
+++

# Towards a SARS-COV-2-Virion-Detektor

As I mentioned in my previous post, I have started a project study the feasibility to detect Coronavirus droplets in closed environments using Particle counters + Raman spectroscopy.
The idea would be to have an early warning system to be able to detect in near real time the presence of droplets containing the virus (from exhaled breath, cough or any other aerosol coming from a carrier).  This would be a tremendous advantage in order to:


1. Evacuate people that could otherwise get exposed to this biohazard cloud
2. Detect potentially asymptomatic carriers so it would be way more effective to stop spreading in the community

Let's have a look at the options available and state of the art. Please keep reading inside


# System envisioning

![System High Level Overview](images/Detektor_System_High_Level_Overview_(Watermarked).jpg)


# Particle counter

It would be the initial part of the system that would detect the presence of a potential biohazardous "cloud" (and would potentially correlate it with an individual/series of individuals) using CCTV cameras. The particle counter would run on additional Deep Learning Algorithms to be able to detect the "type" of hazardous cloud vs. other false signals.

Few reference articles on this particular aspect of the system:

# Long Working Distance Raman Spectroscopy

Then once a cloud has been located, next step would be (the most difficult part) to detect SARS-Cov-2 virions floating on the droplets... The approach to detect this (it is quite a hard problem) would be to use parabolic mirrors ([related work](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5695967/)]) or other optical enhancement techniques. 

There are many challenges related to Raman Spectroscopy (specially the fact that usually samples are just few cm apart from the detector, here we are talking of few or dozens of meters away)...

For articles that could throw some light to this, please check out my article repository -> (https://github.com/p4rk3r/sars-cov-2-virion-detektor/blob/master/README.md#raman-spectroscopy)

Next entry I will commenting few of the findings 



