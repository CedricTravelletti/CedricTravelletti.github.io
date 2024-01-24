---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral researcher in the [Mathematics for Materials Modelling](https://matmat.org/) (MatMat) 
group at EPFL Lausanne, where I focus on applying **Bayesian Optimization**  to **discover new materials**. 

More broadly, I also work on **quantifying uncertainties** in **quantum chemistry calculations** (particularly DFT).

I obtained my PhD in statistics from the University of Bern in June 2023 under the supervision of
[Prof. David Ginsbourger](http://www.ginsbourger.ch/), writing a [thesis](https://boristheses.unibe.ch/4553/1/23travelletti_c.pdf) on 
how to use machine learning to guide data acquisition pocesses in the natural 
sciences.

After my PhD, I worked as an assistant researcher for the 
[Oeschger Center for Climate Change Research](https://www.oeschger.unibe.ch/), 
developing distributed computing algorithms for paleoclimate reconstructions.


Before my PhD, I obtained an MSc in Physics (Hons.) from ETH Zürich and 
worked as a **data scientist** at *SwissRe* and as a **quantitative risk consultant** at *Deloitte*.

News
====
- I have been awarded the[Moser Preis 2023](https://www.imsv.unibe.ch/ueber_uns/news/artikel/cdric_travelletti_erhaelt_den_christian_moser_preis_2023/index_ger.html) of the *Statistics Institute of the University of Bern* for my PhD thesis.

- I have a new preprint online about using [distributed computing for Ensemble Kalman Filtering](https://arxiv.org/abs/2311.12909) with applications 
to paleoclimate reconstruction.

Research Interests
==================
## Bayesian Inverse Problems
[https://doi.org/10.48550/arXiv.2109.03457](https://doi.org/10.48550/arXiv.2109.03457)

Most existing probabilistic inversion techniques have been demonstrated on toy models 
but tend to scale poorly when applied to real-world problems. My aim is to overcome these 
limitations, by focussing on two research directions:
* **Large-scale inversion**
Bayesian inversion on large 3-dimensional domains exhibits an exploding memory footprint 
that limits the achievable resolution.
By introducing new ways of looking at posterior covariance matrices of Gaussian processes (GP), 
our team was able to scale GP-based inversion to large, realistic inverse problems such as 
gravimetric inversion for volcanoes.
* **Realistic priors**


## Sequential Uncertainty Reduction
[https://doi.org/10.1214/21-AOAS1451](https://doi.org/10.1214/21-AOAS1451)

Sequential uncertainty reduction (SUR) strategies aim at computing data collection plans 
that optimally reduce the uncertainty on a given quantity of interest. During my PhD, 
I have worked on developing SUR strategies for set estimation in large-scale inverse problems. 
I have also worked on extending these strategies to multivariate set estimation problems. 
Currently, my research focuses on making the data collection plans proposed by SUR more realistic, 
by including travel costs, location-specific penalties and global constraints.

## Distributed Computing for Large Covariance Modelling
[https://arxiv.org/abs/2311.12909](https://arxiv.org/abs/2311.12909)

When working with probabilistic models discretized on a grid, covariance matrices 
grow quadratically in the grid size. While this used to call for approximations scheme, 
with the avent of cloud-, distributed-computing, researchers are now able to handle the 
covariances on large grids without approximations.

By leveraging state-of-the-art techniques from distributed computing, we build algorithms 
for large-scale data assimilation (*Ensemble Kalman Filter*) and for estimation of large 
covariance matrices; demonstrating how these can be used in climatology and paleoclimate 
reconstruction.

