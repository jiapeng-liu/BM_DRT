# BM_DRT

## Project

This repository contains an implementation of the source code used for the paper entitled "Adaptive Distribution of Relaxation Time Analysis Using Bayesian Mixtures" https://pubs.acs.org/doi/full/10.1021/acs.jpcc.5c04766

## Description

Herein, we present a fully automated Bayesian nonparametric framework using a Bayesian mixture model to recover the distribution of relaxation times (DRT) from the electrochemical impedance spectroscopy (EIS) data. Our approach automatically determines a finite number of relaxation processes and their parameters directly from experimental data, yielding parsimonious representations that naturally suppress artifacts. The method performs unsupervised deconvolution while providing rigorous uncertainty quantification for the DRT itself and its underlying parameters through Markov Chain Monte Carlo sampling.

![GraphModel diagram](resources/BM_DRT illustration.jpg)
<div align='center'><strong>Schematic illustration of the BM DRT method.</strong></div>

## Citation

```
@article{acs.jpcc.5c04766,
author = {Liu, Jiapeng and Ciucci, Francesco},
title = {Adaptive Distribution of Relaxation Time Analysis Using Bayesian Mixtures},
journal = {The Journal of Physical Chemistry C},
volume = {0},
number = {0},
pages = {null},
year = {0},
doi = {10.1021/acs.jpcc.5c04766},
URL = {https://doi.org/10.1021/acs.jpcc.5c04766}
```