---
layout: archive
title: "Poromechanical modeling of coupled solid deformation-fluid flow in shale"
collection: research
permalink: /research/poromechanics/
---
Under construction: Anticipated finish date: 2022/10/9 :-)

## Coupled solid deformation-fluid flow in anisotropic elastoplastic media
<p align="justify">
The effective stress concept and the poromechanical framework pioneered by Terzaghi and Biot have been widely adopted to illustrate coupled fluid flow and solid deformation in porous rocks, but there were still some links missing for anisotropic and ductile rocks like shale. Based on the mixture theory and continuum thermodynamics, I derived a novel mathematical framework for coupled solid deformation and fluid flow through anisotropic elastoplastic porous media[1], which involves a new set of governing equations for mass conservation of fluid and solid, and a new effective stress formulation that identifies distinct forms of effective stress for elastic response and plastic response respectively. Coefficients that emerge in the governing equations are evaluated naturally through the derivation, thus the proposed framework won’t require any additional constitutive law or assumption for parameter evaluation. For this work, I also developed a mixed finite element framework for its numerical implementation and conducted simulations of a consolidation problem with strip loading to reveal the unique hydromechanical response in anisotropic elastoplastic porous rocks.  
</p>

<img src="/images/SP_1.PNG"/>  
<h6 align="center">Setup of the consolidation problem in a transversely isotropic medium under a strip load.  
</h6>

<img src="/images/SP_2.jpg"/>  
<h6 align="center">Evolution of ground settlement and pore pressure.  
</h6>

<img src="/images/SP_3.PNG"/>  
<h6 align="center">Contour of pore pressure in the medium for various scenarios.  
</h6>

<img src="/images/SP_4.PNG"/>  
<h6 align="center">Vectors of Darcy velocities in the medium for various scenarios.   
</h6>

<img src="/images/SP_5.PNG"/>  
<h6 align="center">Contour of norm of plastic strain in the medium for various scenarios.   
</h6>

## Poromechanical modeling of anisotropic elastoplastic media with double porosity
<p align="justify">
I have developed a novel continuum poromechanical framework for shale considering the bimodal pore size distribution from the existing form of voids in shale as either microcracks or nanopores. Specifically speaking, I extended the framework discussed in (II) with the double porosity theory, which allows for the consideration of different permeability and constitutive law for fluid flow at different pore scales[2]. This work is the first of its kind to integrate factors including anisotropy, elastoplasticity, and double porosity in the analysis of hydromechanical responses of shale. With this proposed framework, I reproduced the 1-D consolidation process of Opalinus shale, and both the primary and the secondary consolidation processes were captured, which correspond to the dissipation of pore pressure in microcracks and in nanopores respectively. 
</p>
<img src="/images/DP_illu.jpg"/>  
<h6 align="center">Illustration of the double porosity concept.   
</h6>

<img src="/images/DP_1.jpg"/>  
<h6 align="center">Setup of the 1d consolidation problem in Opalinus Shale.   
</h6>

<img src="/images/DP_2.PNG"/>  
<h6 align="center">Evolution of ground settlement given different overburns.   
</h6>

## Reference:
\[1\] <b>Zhao Y.</b>, Borja R.I.\* (2020). A continuum framework for coupled solid deformation–fluid flow through anisotropic elastoplastic porous media. <i>Computer Methods in Applied Mechanics and Engineering</i>, 369, 113225.  <br>
\[2\] <b>Zhao Y.</b>, Borja R.I.\* (2021). Anisotropic elastoplastic response of double-porosity media. <i>Computer Methods in Applied Mechanics and Engineering</i>, 380, 113797.
