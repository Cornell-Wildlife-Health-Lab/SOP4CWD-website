---
title: Efficient Sample Size Calculator
description: Infectious disease model for population health
---

# Efficient Sample Size Calculator
*Deployed*

The Efficient Sample Size Calculator simulates the sample size needed to declare a population free-from-disesae while explicitly accounting for the natural clustering behavior of hosts. The Calculator can be used to plan investigations using simple random sampling, high-harvest, or two-stage cluster sampling designs. 

## Geographical Scale
* Population size of interest, regardless of the spatial scale

## User Inputs
* Population of interest
* Average cluster size of hosts
* Whether clusters are fixed or variable in size
* Correlation in disease status among hosts sharing a cluster
* Sensitivity of the diagnostic test used to declare CWD-positive

## Outputs
* The number of hosts that need to be tested without finding a positive case to have high probability (95%) that disease prevalence in the overall population is at or below 1% or 2%. 

<center>![graph of sample size vs probability of freedom from disease at a given prevalence](../../assets/Efficient.jpg)
<figcaption>Example output from the Efficient Sample Size Calculator.</figcaption></center>

## More information
For more details, go to the [CWD Data Warehouse User Manual: Efficient Sample Size Calculator](https://pages.github.coecis.cornell.edu/CWHL/CWD-Data-Warehouse/sample-size.html){target="_blank"}.
