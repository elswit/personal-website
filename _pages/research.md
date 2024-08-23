---
layout: archive
title: "Research Interests"
permalink: /research/
author_profile: true
---

<br>
<video muted autoplay loop width=700>
    <source src="/images/Smoke-flow-demo.mp4" type="video/mp4">
</video>
---

1.  **Scientific Machine learning**
  * Data driven models, System identification, Neural and deep learning for physics-informed applications.
1. **Numerical methods for forward and inverse problems**
  * Ensemble learning, Bayesian inference, and Numerical optimization methods with applied for model order reduction, PDE-Constrained optimization and inverse problems
1. **Quantitative Social science research**
  * Exploratory and explanatory data analysis for chronic disease prevention intervention
  * Quantitative social research at the intersection of online learning and Gerontology
1. **Time-stepping methods for PDEs**
  * High-order time discretizations for multi-physics systems. Implicit-Explicit, variable time-stepping
and error control strategies. Parallel and Jacobian-free methods Advanced methods for fluid
simulations, DAEs and stiff problems

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/aMSOWr9UoI8?si=3ROIpG6BGeGrGCr3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> -->


## Explore our research projects
<nbsp>
{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
