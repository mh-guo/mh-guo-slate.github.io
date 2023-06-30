---
layout: page
title: "Research"
permalink: /research/
main_nav: true
---

I am interested in both theoretical and observational astrophysics.

<h1> Toward Horizon-scale Accretion onto Supermassive Black Holes in Elliptical Galaxies </h1>

We present high-resolution, three-dimensional hydrodynamic simulations of the fueling of supermassive black holes in elliptical galaxies from a turbulent medium on galactic scales, taking M87* as a typical case. The simulations use a new GPU-accelerated version of the Athena++ AMR code, and span more than 6 orders of magnitude in radius, reaching scales similar to the black hole horizon. The key physical ingredients are radiative cooling and a phenomenological heating model. We find that the accretion flow takes the form of multiphase gas at radii less than about a kpc. The cold gas accretion includes two dynamically distinct stages: the typical disk stage in which the cold gas resides in a rotationally supported disk and relatively rare chaotic stages ($$ \lesssim 10\% $$ of the time) in which the cold gas inflows via chaotic streams. Though cold gas accretion dominates the time-averaged accretion rate at intermediate radii, accretion at the smallest radii is dominated by hot virialized gas at most times. The accretion rate scales with radius as $$\dot{M}\propto r^{1/2}$$ when hot gas dominates and we obtain $$\dot{M}\simeq 10^{-4}-10^{-3}\rm\,M_\odot\,yr^{-1}$$ near the event horizon, similar to what is inferred from EHT observations. The orientation of the cold gas disk can differ significantly on different spatial scales. We propose a subgrid model for accretion in lower-resolution simulations in which the hot gas accretion rate is suppressed relative to the Bondi rate by $$(\sim r_{\rm g}/r_{\rm Bondi})^{1/2}$$. Our results can also provide more realistic initial conditions for simulations of black hole accretion at the event horizon scale.

<video width="800" controls>
  <source src="/assets/Acc_video_render_d.mp4" type="video/mp4">
  Density perturbation
</video>

<video width="800" controls>
  <source src="/assets/Acc_video_render_v.mp4" type="video/mp4">
  Velocity perturbation
</video>

<h1> Hunting for Wandering Black Hole </h1>

Advisors: [Kohei Inayoshi](https://inayoshi0328.wixsite.com/kohei-inayoshi) [Luis C. Ho](http://kavli.pku.edu.cn/~lho/)

![alt text]({{ site.baseurl }}/assets/wandering_BH.png "Profile Picture"){:.profile}

In the Λ-cold dark matter universe, frequent galaxy mergers and the subsequent central BH interactions would probably create a population of wandering BHs. We investigated low-density accretion flows onto massive black holes orbiting around in the outskirts of their host galaxies (e.g., massive ellipticals, Milky Way, dwarf galaxies), performing three-dimensional simulations and semi-analytical calculations. We constructed radiative inefficient accretion-flow models for accretion near the horizon of a black hole. I applied the simulation results to the emission model and calculated the spectral energy distribution for the accretion flow onto a wandering black hole. I studied the detectability of wandering (super-massive) black holes in different types of galaxies, predicting that ALMA will enable us to hunt for a population of wandering BHs. I published a paper in the Astrophysical Journal as the first-author.

<h1> A New Channel of BulgeFormation via the Destruction of Short Bars </h1>

Advisors: [Luis C. Ho](http://kavli.pku.edu.cn/~lho/), [Victor P. Debattista](http://www.star.uclan.ac.uk/~vpd/)

I studied real and simulated galaxies from both observational and dynamical points of view. Through morphological decomposition for the structures of the galaxy models in N-body simulations using IRAF and GALFIT, I investigated the long-term evolution of barred galaxies with growth of central BHs. After adjusting the models and performing a comprehensive analysis for about one year, we demonstrated that the destruction of short bar contributes significantly to the growth of the bulge which finally bears many similarities to a classical bulge in terms of observation. These results have important implications for the secular evolution of active galaxies and the effect of BH growth in shaping the inner structures of galaxies. This led to a first-author paper published in Astrophysical Journal.

<h1> Numerical Study of Modified Gravity Theory and the Application to Neutron Stars and Gravitational Waves </h1>

Advisor: [Lijing Shao](https://friendshao.github.io/about/)

I investigated a scalar-tensor gravity theory proposed by Damour and Esposito-Farèse (DEF) that predicts large deviations from General Relativity for neutron stars through spontaneous scalarization phenomena. I constructed reduced-order surrogate model for the derived quantities in this theory, coded in a python package [pySTGROMX](https://github.com/AstroMG/pySTGROMX) that speeds up calculations at two orders of magnitude yet still keeps accuracy, compared with the previous algorithms. As an application, we utilized [pySTGROMX](https://github.com/AstroMG/pySTGROMX) to explore constraints on the DEF theory with latest well-timed binary pulsars and gravitational waves through Markov Chain Monte Carlo simulations. The work is summarized in  a first-author paper published in the Physical Review D.