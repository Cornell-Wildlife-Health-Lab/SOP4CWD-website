---
title: Statistical Sample Quotas Model Using Clustering
description: Website page
---

# Statistical Sample Quotas Using Clustering Model
*In final QA/QC prior to deployment*

The Statistical Sample Quotas Using Clustering Model estimates the sample size needed in each sub-administrative area without finding a positive case to have high probability that prevalence in the population is at or below a threshold. The model explicitly accounts for increased disease transmission through the natural clustering behavior of hosts in the population and assumes a simple random sampling design.

## Geographical Scale
* Administrative area, subdivided into a sub-administrative areas

## Required Data
* Population size or population density of hosts in each sub-administrative area

## User Inputs
* Average cluster size of hosts
* Correlation in disease status among hosts sharing a cluster
* Sensitivity of the diagnostic test used to declare a CWD-positive case

## Outputs
* The number of randomly selected hosts that need to be tested in each sub-administrative area to have high probability (95%) that the prevalence of CWD in the overall population is at or below 0.5%, 1%, 1.5%, 2%, 3%, 4%, or 5%. 

<center>![graph of sample size vs probability of freedom from disease at a given prevalence](../../assets/freedomfromdiseaseclusteredpopulation.jpg)
<figcaption>Example of model output showing a sample size requirement.</figcaption></center>

## More information
For more details, go to the [CWD Data Warehouse User Manual: Statistical Sample Quotas Using Clustering Model](https://pages.github.coecis.cornell.edu/CWHL/CWD-Data-Warehouse/sample-size-quotas.html){target="_blank"}.
