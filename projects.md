---
layout: page
title: Projects
permalink: /projects/
sidebar_link: true
sidebar_sort_order: 2
---
## A Statistical Physics Approach to Modelling the Joint Activity of Cortical Populations

This was my masters thesis project. In ML terms, this was an unsupervised learning project that involved estimating the probability density of neural spike train recordings. 
The approach used here is the maximum entropy apporach, with the first and second order non-centered moments as constraints. I explored equilibrium and non-equilibrium versions of this model, 
on both simulations and calcium imaging recordings from mouse area M2.

### Abstract

In this thesis we apply likelihood maximization methods as well as mean-field approximations to construct
equilibrium and non-equilibrium Ising models for neural activity in the form of calcium imaging recordings.
Before applying these methods to the neural data, we carried out tests on samples generated from the
models themselves. We also assessed statistical properties of the neural recordings, as well as the
performance of the inference methods under various circumstances. While the mean-field methods appear
to break down for large numbers of neurons, the exact likelihood maximization procedures for these two
models are reliable also for larger system sizes. Our findings indicate that both the equilibrium and
non-equilibrium Ising models are capable of capturing the essential statistical features of the calcium
imaging recordings, not only reproducing constraint observables but also predicting statistical properties of
the neural activity not used to fit the models. There were clear differences between the models, however,
with the non-equilibrium model outperforming its equilibrium counterpart on generalization.

- [GitHub](https://github.com/mbmahiout/ising)
- [Thesis PDF]({{ site.baseurl }}/assets/pdf/main.pdf){: download}

## Inverse Reinforcement Learning

This was the course project for a [course](https://www.uio.no/studier/emner/matnat/ifi/IN-STK9100/v23/beskjeder/welcome-to-instk-5100-and-9100.html) in reinforcement learning at the University of Oslo. 
We replicated the first experiment in Ng. and Russell, 2000. This involved making a simple agent that could traverse a grid to reach a rewarding location, and using linear programming to infer the reward function on the basis 
of the actions taken by the agent.

- [GitHub](https://github.com/mbmahiout/INSTK5100_IRL_proj)
- [Slides PDF]({{ site.baseurl }}/assets/pdf/IRL_slides.pdf){: download}