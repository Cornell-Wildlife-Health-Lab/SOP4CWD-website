---
title: Probability of Disease Freedom Using Clustering
description: Website page
---

# Probability of Disease Freedom Using Clustering Model
*In final QA/QC prior to deployment*

The Probability of Disease Freedom Using Clustering Model is the third of three models used after sampling has occurred and no positive cases are found to estimate the latent prevalence of CWD. 

Unlike the [**Simple Undetected Prevalence Estimator**](SimpleUndetectedPrevalenceEstimator.md), which does not use any auxiliary information for prevalence estimation, or the [**Prevalence Estimator Data Export**](PrevalenceEstimatorDataExport.md), which considers surveillance weights in prevalence estimation, the [**Probability Disease Freedom Using Clustering Model**](ProbabilityDiseaseFreedomClustering.md) considers host clustering to estimate prevalence. Estimates hinge on the assumption that simple random sampling was used to select hosts from the landscape. 

## Geographical Scale
* Administrative area, subdivided into a sub-administrative areas

## Required Data
* Population size or population density of hosts

## User Inputs
* Average cluster size of hosts
* Correlation in disease status among hosts sharing a cluster
* Sensitivity of the diagnostic test used to declare a CWD-positive case

## Outputs
* The probability that each sub-administrative area is disease-free  

## More information
For more details, go to the [CWD Data Warehouse User Manual: Probability of Disease Freedom Using Clustering Model](https://pages.github.coecis.cornell.edu/CWHL/CWD-Data-Warehouse/DiseaseFreedomUsingClustering.html){target="_blank"}.
