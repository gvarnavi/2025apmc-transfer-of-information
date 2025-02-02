---
title: 'APMC2025 | Transfer of Information'
short_title: Transfer of Information
numbering:
  heading_2: false
---

+++ {"part": "abstract"} 

When a converged beam of accelerated electrons is scanned across a thin sample it acquires phaseshifts which scatter the incident wavefunction due to sample interactions.
Reconstructing these scattering sources from a set of phase-less measurements of the propagated probe intensity at farfield detectors, i.e. using 4DSTEM measurements, is a high-dimensional, non-convex, inverse scattering problem.
Recent developments in fast direct-electrons detectors have renewed interest in direct and iterative phase retrieval algorithms, including center-of-mass (CoM) imaging, single side-band (SSB) and Wigner distribution deconvolution (WDD) ptychography, optimum bright-field (OBF) STEM, tilt-corrected bright-field (tc-BF) STEM, and various flavors (e.g., mixed-state, multislice, etc.) of iterative ptychography, for dose-efficient, highfidelity phase reconstructions of materials-science and life-sciences samples.

The plethora of phase-retrieval STEM techniques outlined above all have complementary strengths:
CoM imaging is computationally inexpensive and generalizes readily to fast segmented detectors;
SSB ptychography and OBF STEM offer higher fidelity reconstructions and can be performed in “realtime” during data acquisition; 
tc-BF STEM relaxes scan sampling requirements and provides robust aberration estimates at low electron fluences; and iterative ptychography can achieve superresolution, i.e. information beyond the numerical aperture of the measurement. 
At the same time, none of these techniques can recover the full spectrum of spatial frequencies in the scattering object:
CoM imaging suffers from low-spatial frequency artifacts; SSB ptychography and OBF STEM preferentially transfer more information at half the numerical aperture; 
tc-BF STEM shows strong “Thon-like” oscillations and contrast reversals at larger defocii; 
and iterative ptychography is very slow at converging low-spatial frequencies. 

In the first part of the talk, I will motive the above statements using experimental observations of reconstruction artifacts in various materials-science and life-sciences samples at varying electron fluences. 
I will then introduce a unified framework to evaluate the transfer of information in these phase-retrieval STEM techniques using a combination of analytical expressions and numerical results against white-noise objects. 
We differentiate between “systematic” errors, i.e. arising from the transfer of information of the reconstruction algorithm, and “random” errors, i.e. due to the finite electron fluence. 
This allows us to arrive at experiment design recommendations as a function of electron fluence and defocus.
We further elucidate commonly confused terms in the STEM literature such as contrast transfer functions (CTFs) and signal-to-noise ratios (SNRs) and compare them with other recent definitions such as detective quantum efficiencies (DQEs). 

Finally, I will propose iterative ptychographicholography – where one uses a diffraction grating in the probe forming aperture to split the primary beam in multiple higher-order beams which are then scanned across a sample, while keeping one of the beams over vacuum – as a potential candidate to overcome the recently proposed quantum information limits of 4D-STEM.
In the second part of the talk, I will discuss the robustness of the transfer of information in direct and iterative ptychography techniques against few-pixel and arbitrary geometry segmented detectors.
These hold promise for sub-second acquisitions, opening the door for time-resolved phaseretrieval in STEM.

+++

