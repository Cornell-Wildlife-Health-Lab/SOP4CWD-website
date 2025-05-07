---
title: Probability of Disease Freedom Using Clustering
description: Website page
---

# Probability of Disease Freedom Using Clustering Model
*In development*

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

## More Information
For more information, go to the [CWD Data Warehouse User Manual: Probability of Disease Freedom Using Clustering Model](https://pages.github.coecis.cornell.edu/CWHL/CWD-Data-Warehouse/DiseaseFreedomUsingClustering.html){target="_blank"}.

## Code
To view the code once deployed, go to the [GitHub Repository: Probability of Disease Freedom Using Clustering Model](https://github.com/Cornell-Wildlife-Health-Lab/probability-of-disease-freedom-using-clustering){target="_blank"}.

## Citations
* Booth JG, Hanley BJ, Hodel FH, Jennelle CS, Guinness J, Them CE, Mitchell CI, Ahmed MS, Schuler KL. 2024. [Sample size for estimating disease prevalence in free-ranging wildlife populations: A Bayesian modeling approach](https://doi.org/10.1007/s13253-023-00578-7). Journal of Agricultural, Biological, and Environmental Sciences. 29, 438–454.
* Booth JG, Hanley BJ, Thompson NE, Gonzalez-Crespo C, Christensen SA, Jennelle CS, Caudell JN, Delisle Z, Guinness J, Hollingshead NA, Them CT, Schuler KL. [Management agencies can leverage animal social structure for wildlife disease surveillance](https://meridian.allenpress.com/jwd/article/doi/10.7589/JWD-D-24-00079/506128/Management-Agencies-Can-Leverage-Animal-Social). Journal of Wildlife Diseases.
