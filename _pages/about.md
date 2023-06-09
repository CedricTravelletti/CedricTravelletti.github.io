---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a researcher in Statistics an Machine Learning at the University of Bern 
interessted in using machine learning to guide data acquisition pocesses in the natural 
sciences.

After obtaining a PhD in statistics in June 2023 under the supervision of
[Prof. David Ginsbourger](http://www.ginsbourger.ch/).
at the University of Bern, I am now working as an assistant researcher.
<!---
[Oeschger Center for Climate Change Research](https://www.oeschger.unibe.ch/).
-->

Before joining the University of Bern, I obtained an MSc in Physics from ETH Zürich and 
worked as a data scientist at SwissRe and as a quantitative risk consultant at Deloitte.


Research Interests
======
## Bayesian Inverse Problems

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
Sequential uncertainty reduction (SUR) strategies aim at computing data collection plans 
that optimally reduce the uncertainty on a given quantity of interest. During my PhD, 
I have worked on developping SUR strategies for set estimation in large-scale inverse problems. 
I have also worked on extending these strategies to multivariate set estimation problems. 
Currently, my research focuses on making the data collection plans proposed by SUR more realistic, 
by including travel costs, location-specific penalties and global constraints.

## Distributed Computing for Large Covariance Modelling
When workin with probabilistic models discretized on a grid, covariance matrices 
grow quadratically in the grid size. While this used to call for approximations scheme, 
with the avent of cloud-, distributed-computing, researchers are now able to handle the 
covariances on large grids without approximations.

By leveraging state-of-the-art techniques from distributed computing, we build algorithms 
for large-scale data assimilation (*Ensemble Kalman Filter*) and for estimation of large 
covariance matrices; demonstrating how these can be used in climatology and paleoclimate 
reconstruction.

