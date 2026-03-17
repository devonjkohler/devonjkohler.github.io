---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research develops **statistical and machine learning methods for
computational biology** with a focus on **mass spectrometry-based
proteomics**, **measurement-aware statistical modeling**, and **causal
inference for biological systems**. Across these areas, I build methods
that account for the realities of biological experiments: complex
measurement processes, limited replication, missing data, and variable
measurement quality.

I aim to develop methods that are both statistically rigorous and
practically useful. In addition to methodological research, I translate
these ideas into open-source software and collaborative workflows that
support researchers in academia and industry.

## Statistical methods and software for proteomics

A major part of my research focuses on developing statistical methods for
quantitative proteomics experiments, especially mass spectrometry-based
assays with complex designs and heterogeneous sources of variability.
These experiments often require specialized models that account for the
structure of peptide- and protein-level measurements, missingness,
experimental design, and assay-specific confounding.

I have developed methods for multiple classes of proteomics experiments,
including post-translational modification analysis, limited proteolysis
experiments, and scalable workflows for large data-independent
acquisition studies. I am also a lead developer and maintainer of the
**MSstats ecosystem**, a collection of open-source Bioconductor tools
for statistical analysis of proteomics experiments. These tools are used
across academic and pharmaceutical laboratories and are designed to make
rigorous statistical workflows accessible, reproducible, and extensible.

## Measurement quality-aware statistical modeling

Modern large-scale proteomics experiments often contain substantial
variation in measurement quality across runs, features, and conditions.
Most downstream statistical methods treat all summarized measurements as
equally reliable, even when some observations are clearly less
trustworthy because of poor chromatographic behavior, noisy peaks, or
other acquisition artifacts.

My recent work develops **quality-aware statistical methods** that
explicitly model measurement reliability and propagate this information
into downstream protein-level inference. In particular, I developed the
**MSstats+** framework, which integrates anomaly detection and
longitudinal quality metrics into differential analysis for DIA
proteomics. These methods allow high-quality observations to contribute
more strongly while reducing the influence of poorly quantified
measurements.

This work reflects a broader research interest in models that account
for how biological data are generated, not just the final summarized
measurements. I am especially interested in statistical approaches that
connect experimental quality control with downstream inferential
robustness.

## Causal modeling for biological systems

Beyond proteomics-specific methodology, I am developing **causal
modeling frameworks for biological systems** that integrate molecular
measurements with prior biological knowledge. These approaches are aimed
at estimating the effects of perturbations, predicting responses to new
interventions, and improving inference in settings with sparse
replication and incomplete experimental coverage.

My current work in this area combines proteomics, transcriptomics,
structured pathway knowledge, and Bayesian modeling to support
interventional prediction in molecular systems. This includes the
software platform **Causomic**, which integrates biological knowledge
resources with causal inference models for systems-level analysis.

Looking ahead, I am interested in building context-aware and multi-omics
causal models that can represent how regulatory relationships vary
across tissues, conditions, and molecular modalities. More broadly, my
long-term goal is to develop machine learning and statistical frameworks
that support iterative, data-driven modeling of cellular systems.

## Collaborative and translational focus

My research is shaped by close collaboration with experimental
scientists, method developers, and pharmaceutical researchers. I have
worked with collaborators at **Genentech, Pfizer, AstraZeneca, and Talus
Bio**, where methodological questions arise directly from real
experimental workflows and translational research settings. These
collaborations help ground my research in practical scientific problems
while motivating new methodological directions.

## Selected themes

- Statistical methods for quantitative proteomics
- Measurement quality-aware inference
- Causal modeling of biological systems
- Multi-omics integration
- Open-source scientific software
