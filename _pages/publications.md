---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## <u>Uncertainty Quantification and Experimental Design for Large-Scale Linear Inverse Problems under Gaussian Process Priors</u>
This work extends traditional sequential uncertainty reduction strategies (SUR) 
to large-scale Bayesian inverse problems. 
By introducing a new, implicit representation of the posterior covariance matrix of a 
Gaussian process, we are able to scale SUR real-world 3D problems. 
The introduced techniques are demonstrated on a set estimation problems in gravimetric inversion 
(Stromboli volcano).

[published version at SIAM JUQ](https://doi.org/10.1137/21M1445028)

[arXiv version](https://doi.org/10.48550/arXiv.2109.03457)



## <u>Disintegration of Gaussian Measures for Sequential Assimilation of Linear Operator Data</u>
In this article, we provide a theoretical framework for conditioning Gaussian processes (GP) 
under linear operator data by leveraging the theory of Gaussian measures. 
Disintegrations of Gaussian measures offer a sound theoretical framework for conditioning under 
linear operator data, and we extend previous results to allow conditioning non-centered measures. 
To ensure that the measure results transfer to the GP world, we provide conditions for ensuring 
that a GP with trajectories in a given Banach space induces a measure on that space.

[arXiv version](https://doi.org/10.48550/arXiv.2207.13581)



## <u>Learning excursion sets of vector-valued Gaussian random fields for autonomous ocean sampling</u>
In this work, we extend SUR strategies to multivariate settings. In passing, we provide a new 
way of looking at the GP co-kriging equations that makes them form-invariant across 
all dimensions of the output and allows computing semi-analytical formulae for the SUR criterion. 
The techniques are demonstrated on a river plume estimation problem.

[arXiv version](https://doi.org/10.48550/arXiv.2007.03722)

[published version at Annals of Applied Statistics](https://doi.org/10.1214/21-AOAS1451)



## <u>Non-Sequential Ensemble Kalman Filtering using Distributed Arrays</u>
Ensemble Kalman filtering (EnKF) is the most popular data assimilation technique 
nowadays, owing to its ability to handle high-dimensional state spaces and to 
its flexibility in the specification of the prior. Nevertheless, the implementation 
that is used by most practicioners (localizes, sequential, square root filter) is 
wrong, because of erroneous update equations. Although this fact is well-known in 
the data assimilation community, most choose to ignore it, arguing that the 
inacurracies are small. In this work, we provide a comprehensive study of the 
inacurracies introdued by the use of wrong update equations and show how one can 
fix these by using a distributed implementation of the EnKF. 
Our implementation relies on distributed arrays, which allows us to 
handle very large matrices and thus assimilate all data at once, fixing 
the errors that stem from sequential assimilation.

[arXiv preprint](https://arxiv.org/abs/2311.12909)



## (Thesis) <u>Non-Sequential Ensemble Kalman Filtering using Distributed Arrays</u>
This thesis aims at developing sequential uncertainty reduction techniques for set
estimation in Bayesian inverse problems. Sequential uncertainty reduction (SUR)
strategies provide a statistically principled way of designing data collection plans
that optimally reduce the uncertainty on a given quantity of interest. This thesis
focusses on settings where the quantity of interest is a set that is implicitly defined
by conditions on some unknown function and one is only able to observe the values
of linear operators applied to the function. This setting corresponds to the one en-
coutered in linear inverse problems and proves to be challenging for SUR techniques.
Indeed, SUR relies on having a probabilistic model for the unknown function under
consideration, and these models become untractable for moderately sized problem.
We start by introducing an implicit representation for covariance matrices of Gaus-
sian processes (GP) to overcome this limitation, and demonstrate how it allows one
to perform SUR for excursion set estimation in a real-world 3D gravimetric inversion
problem on the Stromboli volcano. In a second time, we focus on extending vanilly
SUR to multivariate problems. To that end, we introduce the concept of ’generalized
locations’, which allows us to rewrite the co-kriging equations in a form-invariant
way and to derive semi-analytical formulae for multivariate SUR criteria. Those
approaches are demonstrated on a river plume estimation problem. After having
extended SUR for inverse problems to large-scale and multivariate settings, we de-
vote our attention to improving the realism of the models by including user-defined
trends. We show how this can be done by extending universal kriging to inverse
problems and also provide fast k-fold cross-validation formulae. Finally, in order to
provide theoretical footing for the developed approaches, show how the conditional
law of a GP can be seen as a disintegration of a corresponding Gaussian measure
under some suitable condition.

[online version](https://boristheses.unibe.ch/4553/1/23travelletti_c.pdf)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
