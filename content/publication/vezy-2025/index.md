---
title: 'PlantBiophysics.Jl: A High-Performance, Modular Software for Prototyping and
  Scaling Biophysical Models from Leaf to Canopy'
authors:
- Simon Treillou
- Rémi Vezy (joint first author)
- Samuel Mackeown
- Emilie Peynaud
- Raphaël P A Perez
- Thomas Arsouze
- Jean Dauzat
date: '2025-10-01'
publishDate: '2025-10-21T06:08:59.466233Z'
publication_types:
- article-journal
publication: '*in silico Plants*'
doi: 10.1093/insilicoplants/diaf021
abstract: "Process-based biophysical models are essential for understanding and predicting
  plant responses to environment, yet their development and application remains hindered
  by the ``two-language problem'': models are typically prototyped in interactive,
  slow languages and then reimplemented in compiled, fast languages for simulation.
  This workflow requires more human resources, and it may introduce delays, errors,
  and complexity for model evaluation and prototyping iteration.We present PlantBiophysics.jl,
  a pure Julia package that unifies model prototyping, calibration, simulation, and
  evaluation of biophysical models within a single, high-performance and interactive
  environment. The package currently supports four key processes: light interception,
  energy balance, photosynthesis, and stomatal conductance. It provides automated
  model composition and coupling through a modular and extensible architecture. The
  package supports uncertainty propagation and compatibility with 3D plant structures
  and dynamic meteorological inputs.We benchmarked PlantBiophysics.jl against the
  widely used R package plantecophys and the Julia package LeafGasExchange.jl. Simulations
  ran up to $∼$6700x and $∼$460x faster, respectively, while improving predictive
  accuracy (e.g., net assimilation nRMSE: 5% vs. 9% and 12%, respectively). By allowing
  models to be easily swapped, coupled, or extended, and by supporting simulations
  at scales ranging from single leaves to 3D plant canopies, PlantBiophysics.jl provides
  a robust, efficient, and transparent tool for plant ecophysiologists and modelers."
tags:
- Julia
- Plant biophysics
summary: This paper is issued from my internship within the AMAP laboratory.
---
