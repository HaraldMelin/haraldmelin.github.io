---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a PhD student at [Lagergren Lab](https://lagergrenlab.org/), [KTH](https://www.kth.se/en)/[SciLifeLab](https://www.scilifelab.se), Stockholm.
My research interests are within probabilistic Machine Learning for biological applications, in particular,
developing models and methods for Bayesian inference in phylogenetics, cancer evolution and metastatic patterns using
Next Generation Sequencing data.

Papers
====== 
[VICTree - a Variational Inference method for Clonal Tree reconstruction](https://www.biorxiv.org/content/10.1101/2024.02.14.580312v1.full.pdf)
Accepted to, and will be presented at RECOMB 2024 with [Vittorio Zampinetti](https://www.polito.it/en/staff?p=vittorio.zampinetti),
[Andrew McPherson](https://www.mskcc.org/research-areas/labs/members/andrew-mcpherson)
and [Jens Lagergren](https://lagergrenlab.org/).

The paper introduces the first framework for joint Bayesian inference of clonal trees and
site-dependent copy number evolution without reducing the state space of copy number (CN) profiles. We acheive this by 
deriving a Coordinate Ascent Variational Inference (CAVI) framework for a Tree-structured Mixture Hidden Markov Model (TSMHMM), 
a novel HMM suited for clonal trees and CN evolution.


[VaiPhy: a Variational Inference Based Algorithm for Phylogeny](https://arxiv.org/abs/2203.01121)
Published and selected for oral presentation at NeurIPS 2022
with [Hazal Koptagel](https://scholar.google.fr/citations?user=pdKQwIIAAAAJ&hl=fr),
[Oskar Kviman](https://okviman.github.io/),
[Negar Safinianaini](https://www.mskcc.org/research-areas/labs/members/negar-safinianaini)
and [Jens Lagergren](https://lagergrenlab.org/).

We propose a CAVI-based algorithm for Bayesian phylogenetic inference. We also introduce two sampling algorithms: 
1. The JC sampler, which samples branch lengths directly from the Jukes-Cantor model.
2. SLANTIS, an algorithm for sampling tree topologies.


["Multiple Importance Sampling ELBO and Deep Ensembles of Variational Approximations"](https://proceedings.mlr.press/v151/kviman22a.html)
Published in AISTATS 2022
with [Oskar Kviman](https://okviman.github.io/), [Hazal Koptagel](https://scholar.google.fr/citations?user=pdKQwIIAAAAJ&hl=fr),
[Víctor Elvira](https://victorelvira.github.io/) and [Jens Lagergren](https://lagergrenlab.org/).


Teaching
========
I am the main teaching assistant in [Machine Learning, Advanced Course](https://www.kth.se/student/kurser/kurs/DD2434?l=en) at KTH. 
The course focuses on probabilistic Machine Learning, mainly from the Bayesian perspective, and covers topics such as
algorithms for learning on probabilistic graphical models, CAVI, Stochastic VI, Black-Box VI and Variational Autoencoders.
My responsibilities include holding lectures and exercise sessions, developing course content and examining material for the course.