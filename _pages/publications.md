---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
#### <u>Uncertainty Quantification and Experimental Design for Large-Scale Linear Inverse Problems under Gaussian Process Priors</u>
This work extends traditional sequential uncertainty reduction strategies (SUR) 
to large-scale Bayesian inverse problems. 
By introducing a new, implicit representation of the posterior covariance matrix of a 
Gaussian process, we are able to scale SUR real-world 3D problems. 
The introduced techniques are demonstrated on a set estimation problems in gravimetric inversion 
(Stromboli volcano).

[published version at SIAM JUQ](https://doi.org/10.1137/21M1445028)

[arXiv version](https://doi.org/10.48550/arXiv.2109.03457)




#### <u>Disintegration of Gaussian Measures for Sequential Assimilation of Linear Operator Data</u>
In this article, we provide a theoretical framework for conditioning Gaussian processes (GP) 
under linear operator data by leveraging the theory of Gaussian measures. 
Disintegrations of Gaussian measures offer a sound theoretical framework for conditioning under 
linear operator data, and we extend previous results to allow conditioning non-centered measures. 
To ensure that the measure results transfer to the GP world, we provide conditions for ensuring 
that a GP with trajectories in a given Banach space induces a measure on that space.

[arXiv version](https://doi.org/10.48550/arXiv.2207.13581)



#### <u>Learning excursion sets of vector-valued Gaussian random fields for autonomous ocean sampling</u>
In this work, we extend SUR strategies to multivariate settings. In passing, we provide a new 
way of looking at the GP co-kriging equations that makes them form-invariant across 
all dimensions of the output and allows computing semi-analytical formulae for the SUR criterion. 
The techniques are demonstrated on a river plume estimation problem.

[arXiv version](https://doi.org/10.48550/arXiv.2007.03722)

[published version at Annals of Applied Statistics](https://doi.org/10.1214/21-AOAS1451)





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
