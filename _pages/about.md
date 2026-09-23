---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi, I am Dian Jin (金典), a Ph.D. student in Electrical and Computer
Engineering (minor in Computer Science) at UW–Madison, advised by Prof.
[Jeremy Coulson](https://jeremycoulson.github.io/). I work on **data-driven
control and robot learning**: building predictive models of system behavior
directly from input–output data, grounded in behavioral systems theory and
DeePC, and using them for planning and control in robotic manipulation.
Previously, I received my B.S. (2022) from Soochow University and M.A. (2023)
from UW–Madison, both in Mathematics. Outside research, I enjoy photography and
the outdoors.

<p class="hiring-note">
  <strong>I am seeking a robotics research internship for Summer 2027.</strong>
  If you think I would be a good fit, feel free to reach out at
  <a href="mailto:djin38@wisc.edu">djin38@wisc.edu</a> or view my
  <a href="/files/Dian_Jin_Resume.pdf">resume</a>.
</p>

## News

<ul class="news-list">
  <li>
    <span class="news-date">Jul 2026</span>
    <span class="news-text">Paper <a href="https://ieeexplore.ieee.org/document/11589305">“On the sensitivity of the subspace predictor to behavioral perturbations”</a> accepted to <strong>IEEE Control Systems Letters (L-CSS)</strong>, with an oral presentation in the invited session <em>Safe Planning and Control with Uncertainty Quantification</em> at the <strong>65th IEEE Conference on Decision and Control (CDC 2026)</strong>, Honolulu, Hawaii.</span>
  </li>
  <li>
    <span class="news-date">Jan 2026</span>
    <span class="news-text">Paper <a href="https://proceedings.mlr.press/v331/jin26a.html">“Online subspace learning on flag manifolds for system identification”</a> accepted to the <strong>8th Annual Learning for Dynamics &amp; Control Conference (L4DC 2026)</strong>, Los Angeles.</span>
  </li>
</ul>

## Research Interests

I develop **data-driven methods that let robots learn predictive models of
their own behavior from trajectory data and use them for planning and control**:

- **Predictive models for manipulation and planning** — learning local
  trajectory models of robot behavior from offline data and demonstrations,
  combined with graph-based motion planning and constrained predictive control.
  Evaluated on MuJoCo reaching and contact-rich pushing tasks.
- **Online adaptation from streaming data** — updating low-dimensional
  predictive models of time-varying systems as new data arrive, via
  optimization on Grassmann and flag manifolds, without knowing the system
  order in advance.
- **Robustness of learned models** — deriving prediction-error bounds that
  quantify how estimation errors in learned models propagate to downstream
  predictions and control.

## Recent Publications

{% include pub-list.html %}

## Academic Services
- Reviewer for: L4DC'25, L4DC'26, CDC'26, Automatica
