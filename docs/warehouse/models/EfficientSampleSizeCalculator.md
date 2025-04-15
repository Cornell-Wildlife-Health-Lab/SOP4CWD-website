---
title: Efficient Sample Size Calculator
description: Infectious disease model for population health
---

# Efficient Sample Size Calculator

This model estimates the sample size needed to declare a population free from disesae, explicitly accounting for biological clusterings within the overall population. Users can select simple random sampling, high-harvest, or two-stage cluster sampling schemes. 

## Geographical Scale
* Biological population of interest (N)

## Required Data
* None

## Suggested Data
* None

## User Inputs
* Total population size estimate
* Average cluster size
* Whether cluster sizes are fixed or random
* Correlation of disease status within cluster
* Diagnostic test sensitivity 

## Outputs
* The number of animals that need to be tested to have high probability (95%) that disease prevalence in the overall population is at or below 1% or 2%. 

<center>![graph of sample size vs probability of freedom from disease at a given prevalence](../../assets/freedomfromdiseaseclusteredpopulation.jpg)
<figcaption>Example of model output showing sample size required to substantiate disease prevalence below 1% and 2% prevalence.</figcaption></center>

## More information

* [CWD Data Warehouse User Manual: Efficient Sample Size Calculator](https://pages.github.coecis.cornell.edu/CWHL/CWD-Data-Warehouse/sample-size.html){target="_blank"}
* [The interactive application](https://cwhl2.shinyapps.io/EfficientSampleCalculator/){target="_blank"}
