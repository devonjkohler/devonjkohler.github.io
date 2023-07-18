---
title: "MSstatsPTM: an R/Bioconductor software for detecting quantitative changes in post-translational modifications"
collection: talks
type: "Talk"
permalink: /talks/US_HUPO_2021
venue: "US HUPO 2021"
date: 2021-03-01
location: "Online"
---

The scientific community widely utilizes mass spectrometry (MS)-based proteomics to quantify the abundance of proteins and their post-translational modifications (PTMs). Experiments targeting PTMs face several specific challenges. These include the low abundance, few representative peptides, and convolution with abundance changes in the overall protein expression. Due to these challenges, a robust approach to estimate relative changes in PTMs should combine PTM sites over several peptides, replicates in multiple conditions, and consider sources of confounding present in the experiment. We propose a general statistical model and workflow that is both reproducible and comprehensive. The method measures PTM and protein abundance by summarizing intensities through Tukey’s median polish method. Then a model based on the family of linear mixed-effects models is fit. Finally, the PTM abundances are adjusted to remove variance from changes in the overall protein. The package can handle a diverse range of acquisition types, including label-free, DDA, DIA, and TMT. We implement this model in the free and open-source R package MSstatsPTM and available at the links below.

[Download poster here](http://devonjkohler.github.io/files/USHUPO2021_MSstatsPTM_Poster.pdf)
