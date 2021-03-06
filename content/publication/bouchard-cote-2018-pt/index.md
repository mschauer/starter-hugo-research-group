---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The Bouncy Particle Sampler: A Nonreversible Rejection-Free Markov Chain Monte
  Carlo Method'
subtitle: ''
summary: ''
authors:
- Alexandre Bouchard-Côté
- Sebastian J Vollmer
- Arnaud Doucet
tags: []
categories: []
date: '2018-04-01'
lastmod: 2021-09-26T12:37:56+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-09-26T10:37:56.560651Z'
publication_types:
- '2'
abstract: ABSTRACTMany Markov chain Monte Carlo techniques currently available rely
  on discrete-time reversible Markov processes whose transition kernels are variations
  of the Metropolis?Hastings algorithm. We explore and generalize an alternative scheme
  recently introduced in the physics literature (Peters and de With 2012) where the
  target distribution is explored using a continuous-time nonreversible piecewise-deterministic
  Markov process. In the Metropolis?Hastings algorithm, a trial move to a region of
  lower target density, equivalently of higher ?energy,? than the current state can
  be rejected with positive probability. In this alternative approach, a particle
  moves along straight lines around the space and, when facing a high energy barrier,
  it is not rejected but its path is modified by bouncing against this barrier. By
  reformulating this algorithm using inhomogeneous Poisson processes, we exploit standard
  sampling techniques to simulate exactly this Markov process in a wide range of scenarios
  of interest. Additionally, when the target distribution is given by a product of
  factors dependent only on subsets of the state variables, such as the posterior
  distribution associated with a probabilistic graphical model, this method can be
  modified to take advantage of this structure by allowing computationally cheaper
  ?local? bounces, which only involve the state variables associated with a factor,
  while the other state variables keep on evolving. In this context, by leveraging
  techniques from chemical kinetics, we propose several computationally efficient
  implementations. Experimentally, this new class of Markov chain Monte Carlo schemes
  compares favorably to state-of-the-art methods on various Bayesian inference tasks,
  including for high-dimensional models and large datasets. Supplementary materials
  for this article are available online.
publication: '*J. Am. Stat. Assoc.*'
---
