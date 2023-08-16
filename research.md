---
layout: page
title: Research
permalink: /research/
---

Under construction!

### [CV]({{site.url}}/images/cv_2023.pdf)

## Here are some things I've worked on:

### Understanding Large-scale Structure
- Primordial non-Gaussianity: 
	  "[Inflation](https://ned.ipac.caltech.edu/level5/Liddle/Liddle_contents.html)" is our model for the Universe in its earliest moments. There is a zoo of possible inflationary models, which we can only sort through based on their downstream impact on cosmological measurements. For the forseeable future, the best way to characterize an especially interesting subset of these models [(multi-field models](https://arxiv.org/abs/astro-ph/0702187)) is with galaxy surveys. I work, in my own little way, on developing methods to do just this.
- The information content of tracers: 
	  The night of [large-scale structure](https://newscenter.lbl.gov/wp-content/uploads/2022/01/allframe-1000mpc-960x540-1.gif) is dark, but it offers lampposts in the form of luminous tracers, like galaxies and hot gas. It is not very easy to describe how these tracers are located in space, especially when they are almost close enough to overlap. I spent a little time working on this directly, but am thinking about it all the time!
- Massive neutrinos: 
	  More than ten million neutrinos from the early universe are passing through your body *right now*. Neutrinos are sub-atomic particles predicted by the [Standard Model](https://home.cern/science/physics/standard-model), but what was *not* predicted is that they have mass. [It turns out they do have mass](https://www.nobelprize.org/prizes/physics/2015/press-release/), and cosmological measurements can place the tightest upper bound on that mass - that is - if we understand how neutrinos affect large-scale structure. I worked toward this goal by improving the treatment of massive neutrinos in cosmological simulations.


### Modern Numerical Tools for Cosmological Inference
- Differentiable forward models, optimization, and sampling: 
	  Suppose you have to climb a hill as fast as possible. Going straight up seems a pretty good option, but what direction is "up"? [Gradient-based](https://en.wikipedia.org/wiki/Gradient#/media/File:Gradient2.svg) optimization and sampling methods use this directional information to move around spaces of[ very large dimension](https://en.wikipedia.org/wiki/Curse_of_dimensionality). When this information is avaliable, it makes the process of finding the best parameters for a given physical model and their uncertainties much easier. To do this, however, the model has to be differentiable - and I've worked on developing this capability for one model or another since I started at Berkeley! 
- Active Learning: 
	  Budgeting is an (un)fortunate part of daily life, but also an important part of scientific investigation. To actually [learn something from a data analysis](https://en.wikipedia.org/wiki/Bayesian_inference), we want to estimate parameters of a model and attach an *uncertainty* to them. When the model for the physical process in question is expensive (e.g. [a simulation that takes hundreds of years on your laptop](https://www.illustris-project.org/about/#:~:text=The%20Illustris%20simulations%20were%20run,%2C%20or%20about%202%2C000%20years)), we can't afford to run it enough times to capture this uncertainty in the usual way. Instead, we can think very carefully about what parameter values we want to evaluate our model at using active learning. I used some machine learning tools (normalizing flows, gaussian processes, and neural networks) to test a new strategy to do this.

I've had the pleasure of working with several people on these problems, including: [Uroš Seljak](https://physics.berkeley.edu/people/faculty/uros-seljak), [Zack Li](https://zack.li/),the [CPAC group at Argonne National Lab](https://cpac.hep.anl.gov/), [Sukhdeep Singh](https://scholar.google.com/citations?user=ss19CkwAAAAJ&hl=en), and others at [BCCP](http://bccp.berkeley.edu/) & [LBNL](https://cosmology.lbl.gov/sem_bcg_future.html).
I'm also a member of the [DES](https://www.darkenergysurvey.org/), [LSST-DESC](https://lsstdesc.org/), and [CMB-S4](https://cmb-s4.org/) collaborations.

