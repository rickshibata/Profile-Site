---
title: "Flow Past a Square Cylinder"
excerpt: "Computational Fluid Dynamics (CFD) code to compute the flow past a square cylinder at low Reynolds Numbers using a Incompressible 2D Navier-Stokes solver"
header:
  #image: /assets/images/cfd-th.JPG
  teaser: assets/images/cfd-th.JPG
sidebar:
  - title: "Project Type"
    image: /assets/images/cfd-th.JPG
    image_alt: "logo"
    text: "Academic"
  - title: "Tools"
    text: "Matlab, LaTex"
  - title: "Affiliation"
    text: "University of Texas at Austin, Aerospace Engineering"
gallery1:
  - url: /assets/images/X-Vel_Re40.gif
    image_path: /assets/images/X-Vel_Re40.gif
    alt: "X-Velocity over time at Reynolds Number of 40"
    title: "X-Velocity over time at Reynolds Number of 40"
  - url: /assets/images/Vort_Re40.gif
    image_path: /assets/images/Vort_Re40.gif
    alt: "Vorticity over time at Reynolds Number of 40"
    title: "Vorticity over time at Reynolds Number of 40"
gallery2:  
  - url: /assets/images/X-Vel_Re60.gif
    image_path: /assets/images/X-Vel_Re60.gif
    alt: "X-Velocity over time at Reynolds Number of 60"
    title: "X-Velocity over time at Reynolds Number of 60"
  - url: /assets/images/Vort_Re60.gif
    image_path: /assets/images/Vort_Re60.gif
    alt: "Vorticity over time at Reynolds Number of 60"
    title: "Vorticity over time at Reynolds Number of 60"
---

This project was the final project for a graduate-level Computational Fluid Dynamics (CFD) course. A code was developed in Matlab to simulate the flow past a square-cylinder in a low Reynolds Number (Re) flow of up to Re~100. Under a Re of approximately Re=55, the flow converges to a steady solution, but at higher Re the flow exhibits an unsteady phenomena called the "Kármán vortex street" which is caused by vortex shedding off the cylinder.

{% include gallery id="gallery1" caption="The animations above show the x-velocity and vorticity of the flow at Re=40." %}{: .text-center}
{% include gallery id="gallery2" caption="The animations above show the x-velocity and vorticity of the flow at Re=60." %}{: .text-center}


[Final Report](https://drive.google.com/file/d/19v2MI3-VyChZhyBsUEH9VRpBkd3FWU_M/view?usp=sharing)
<\br>
[Source Code](https://drive.google.com/file/d/1KGGJ4mLkh1e_BIdLXWVv-SI-Dxs3nMmw/view?usp=sharing)
