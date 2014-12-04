---
title: Schedule
permalink: /schedule.html
weight: 0
---

## Workshop schedule

The schedule for our workshop follows. Below that are short abstracts for each
of our invited speakers.

| --------:| ---------------------------------------------------
|  8:30 AM | Introduction and opening remarks
|  8:50 AM | Nando de Freitas (University of Oxford)
|  9:25 AM | Robert Gramacy (University of Chicago)
| 10:00 AM | Coffee Break
| 10:30 AM | Daniel Russo (Stanford University)
| 11:05 AM | Poster spotlights
| 11:20 AM | Poster session 1
| 12:00 PM | Break
|  3:00 PM | Steve Scott (Google)
|  3:25 PM | Aish Fenton (Netflix)
|  3:50 PM | Julien Cornebise (DeepMind)
|  4:15 PM | Poster session 2
|  5:00 PM | Coffee Break
|  5:30 PM | Panel discussion&mdash;Bridging research and Industry
|  6:30 PM | End 


### Nando de Freitas

I will present of an overview of current challenges in Bayesian optimization,
some recent progress, and open problems.

### Daniel Russo

### Robert Gramacy

Constrained blackbox optimization is a difficult problem, with most
approaches coming from the mathematical programming literature. The
statistical literature is sparse, especially in addressing problems
with nontrivial constraints. This situation is unfortunate because
statistical methods have many attractive properties: global scope,
handling noisy objectives, sensitivity analysis, and so forth. To
narrow that gap, we propose a combination of response surface
modeling, expected improvement, and the augmented Lagrangian numerical
optimization framework. This hybrid approach allows the statistical
model to think globally and the augmented Lagrangian to act locally.
We focus on problems where the constraints are the primary bottleneck,
requiring expensive simulation to evaluate and substantial modeling
effort to map out. In that context, our hybridization presents a
simple yet effective solution that allows existing objective-oriented
statistical approaches, like those based on Gaussian process
surrogates and expected improvement heuristics, to be applied to the
constrained setting with minor modification. This work is motivated by
a challenging, real-data benchmark problem from hydrology where, even
with a simple linear objective function, learning a nontrivial valid
region complicates the search for a global minimum.


### Steve Scott

The modern service economy is substantively different from the agricultural and
manufacturing economies that preceded it. In particular, the cost of
experimenting is dominated by opportunity cost rather than the cost of obtaining
experimental units. The different economics require a new class of experiments,
in which stochastic models play an important role. This article briefly
summarizes mulit-armed bandit experiments, where the experimental design is
modified as the experiment progresses to make the experiment as inexpensive as
possible.

### Aish Fenton

### Julien Cornebise
