---
title: Prevalence Estimator Data Export
description: Model Page on Website
---

# Prevalence Estimator Data Export
*Deployed*

The Prevalence Estimator Data Export is the second of three models used after sampling has occurred and no positive cases are found to estimate the latent prevalence of CWD. 

The Prevalence Estimator Data Export allows users to pre-process CWD Data Warehouse sample data for upload and use in the [SpeedGoat Estimation Tool](https://public.spdgt.com/app/wtsurv){target="_blank"}. Of particular interest is the upper bound of the credible interval, which means there is, for example, a 95% probability that true prevalence is at or below the reported level given your sampling effort.  

Unlike the [**Simple Undetected Prevalence Estimator**](SimpleUndetectedPrevalenceEstimator.md), which does not use any auxiliary information for prevalence estimation, or the [**Probability Disease Freedom Using Clustering Model**](ProbabilityDiseaseFreedomClustering.md) which considers host clustering in prevalence estimation, the SpeedGoat Estimation Tool uses prior distributions to estimate prevalence. Only certain prior distributions are accomodated, so sample data depicting select species or sources may not be considered. 

## Geographical Scale
* Administrative area, subdivided into a sub-administrative areas

## Required Data
* Sample data that includes age, sex, species, and sample source

## User Inputs
* Cervid species
* Season-year

## Outputs
* A downloadable file of processed sample data for batch upload in the SpeedGoat Estimation Tool 

## More Information
For more information, go to the [CWD Data Warehouse User Manual: Prevalence Estimator Data Export](https://pages.github.coecis.cornell.edu/CWHL/CWD-Data-Warehouse/speedgoat.html){target="_blank"}.

## Code
To view the code, go to the [GitHub Repository: Prevalence Estimator Data Export](https://github.com/Cornell-Wildlife-Health-Lab/prevalence-estimator-data-export-v2){target="_blank"}.

## Citations
* Heisey DM, Jennelle CS, Russell RE, Walsh DP. 2014. [Using auxiliary information to improve wildlife disease surveillance when infected animals are not detected: A Bayesian approach](https://doi.org/10.1371/journal.pone.0089843). PLoS ONE 9(3): e89843. 

