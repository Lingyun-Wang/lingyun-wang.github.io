---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:

---

{% include base_path %}

**CVSR-Net: Axial super-resolution OCT via complex-valued network**  
Axial resolution is important for OCT as a higher axial resolution can reveal more detialed structures, thus helping research and diagnosis. Many researchers have proposed advanced networks to super-resolve OCT but all these methods are real-valued and they ignore the phase of OCT signal. Herein, inspired by complex-valued networks, we proposed the first deep-learning-based super-resolution approach using both amplitude and phase of OCT signal to reconstruct OCT images. The introduction of phase achieves better performance than a network of the same structure without phase introduction.
\[\left[ \begin{matrix}
   \Re (W*I)  \\
   \Im (W*I)  \\
\end{matrix} \right]=\left[ \begin{matrix}
   A & -B  \\
   B & A  \\
\end{matrix} \right]*\left[ \begin{matrix}
   x  \\
   y  \\
\end{matrix} \right].\]

![Projects1Image1](http://Lingyun-Wang.github.io/images/Projects1Image1.png)  
**Figure 1** (A) Schematic of the swept-source OCTA imaging system. (B) Mechanical drawing of the handheld OCT probe. BD, balanced photodetector; 
CL, collimator; FC, fiber coupler; GS, galvo scanner; L, lens; M, mirror; S, sample; SS, swept source  
![Projects1Image2](http://Lingyun-Wang.github.io/images/Projects1Image2.png)  
**Figure 2** Evaluation of CS reconstruction and CGM filter on en-face images of human ear and cheek: (A) raw image of ear. (B–C) 
the corresponding CS-reconstructed image and CGM-filtered image. (D) raw image of cheek. (E–F) the corresponding CS-reconstructed 
image and CGM-filtered image




**Compressive sensing denoising technology for Optical Coherence Tomography Angiography (OCTA)**  
A method based on compressive sensing (CS) is proposed for reducing the acquisition time and noise of optical coherence tomography angiography (OCTA). 
It is aimed at making up for the disadvantages of OCTA including motion-induced artifact and noise. The results show that vasculature structures can be 
reconstructed well through CS on B-scans with a sampling rate of 70%. Moreover, the noise can be significantly eliminated by specially-designed 
CS-Guassian-Median (CGM) filter.  
![Projects1Image1](http://Lingyun-Wang.github.io/images/Projects1Image1.png)  
**Figure 1** (A) Schematic of the swept-source OCTA imaging system. (B) Mechanical drawing of the handheld OCT probe. BD, balanced photodetector; 
CL, collimator; FC, fiber coupler; GS, galvo scanner; L, lens; M, mirror; S, sample; SS, swept source  
![Projects1Image2](http://Lingyun-Wang.github.io/images/Projects1Image2.png)  
**Figure 2** Evaluation of CS reconstruction and CGM filter on en-face images of human ear and cheek: (A) raw image of ear. (B–C) 
the corresponding CS-reconstructed image and CGM-filtered image. (D) raw image of cheek. (E–F) the corresponding CS-reconstructed 
image and CGM-filtered image


