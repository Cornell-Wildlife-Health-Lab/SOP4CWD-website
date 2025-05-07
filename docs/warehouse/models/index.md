---
title: Models
description: This is a description of the page.
---

# Models

The CWD Data Warehouse allows agencies to analyze their data using models, which are defined in the Warehouse to be embedded software that intakes agency data and generates synthesized outputs. A 'model' could be as simple as a data summary or as complex as a high-dimensional spatial analysis. Results of models help wildlife agencies efficiently plan CWD surveillance efforts and make data-driven decisions. 

## Use Warehouse Models to: 

### Obtain Surveillance Quotas
* The [**Risk-Weighted Surveillance Quotas Model**](RiskWeightedSurveillanceQuotasModel.md) incorporates risk factors for CWD introduction to calculate surveillance targets by sub-administrative area. This model is particularly applicable to entities that have not yet detected CWD. Surveillance targets minimize unexplored risk. 
* The [**Sample Allocation Model**](SampleAllocationModel.md) uses optimal control theory to distribute sampling resources across a wide jurisdiction to minimize overall disease burden at the moment of first detection. It model is particularly applicable to entities that have not yet detected CWD, but can be used in any set of sites that are thought to be disease-free. Surveillance targets constitute the best use of sampling dollars.
* The [**Statistical Sample Quotas Using Clustering Model**](StatisticalSampleQuotas.md) is used to determine the sample size needed for each sub-administrative area without finding a positive case to declare a population free-from-disease given that host clustering. The sampling scheme is simple random sampling. Suveillance targets produce statistically robust investigations of disease at the population scale.
* The [**Efficient Sample Size Calculator**](EfficientSampleSizeCalculator.md) is used to determine the sample size needed to declare a population free-from-disease given that hosts group together (and share their diseases) on the landscape. Sampling schemes include simple random sampling, high-harvest sampling, and two-stage cluster sampling. Surveillence targets produce statistically robust investigations of disease at the population scale. 

### Understand Outbreak Potential
* The [**Epizootic Risk Model**](EpizooticRiskModel.md) reveals locations on the landscape where herd dynamics may promote or attenuate an outbreak, if prions were to be introduced. The model further allows agencies to see which demographic parameter disproportionately influences disease outcomes. 

### Estimate Prevalence After Sampling Has Occurred
* The [**Simple Undetected Prevalence Estimator**](SimpleUndetectedPrevalenceEstimator.md) uses a statistical framework to determine underlying prevalence based on the number of samples that test negative for disease in a single surveillance year. 
* The [**Prevalence Estimator Data Export**](PrevalenceEstimatorDataExport.md) processes sample data into the format needed for immediate upload into an external software application to estimate the maximum prevalence of CWD in areas for which no positive cases were found. 
* The [**Probability of Disease Freedom Using Clustering Model**](ProbabilityDiseaseFreedomClustering.md) leverages increased disease transmission through host clustering to determine the probability that a populatino is disease-free given the sampling intensity in a single surveillance year. 

### Explore Surveillance Expenses
* The [**Per-Sample Cost Analysis Model**](PerSampleCost.md) collapses agency expense data into an average cost to determine disease status of a single host in by sub-administrative area by season-year. 

### Predict Outbreaks
* [**Positive Predictor Model**](PositivePredictorModel.md) uses all SOP4CWD data in conjunction with machine learning to predict which sub-administrative areas may turn CWD-positive next. 

### Explore an Outbreak
* The [**Disease Cluster Analysis Data Export**](DiseaseClusterAnalysisDataExport.md) processes sample data for immediate upload into an external software application to determine whether disease clusters are statistically significant in time or space.
* The [**Outbreak Response Model**](./OutbreakResponseModel.md) uses resource selection functions to delineate containment areas around the first confirmed or hypothetical CWD-positive cases.
* The [**Disease Control Strategies Model**](DiseaseControlStrategiesModel.md) used an agent-based framework to investigate ways to thwart disease progression.
* The [**Home Range Contamination Model**](HomeRangeContaminationModel.md) uses Bayesian spatial modeling to pinpoint home ranges likely to harbor CWD+ hosts. 
* The [**Spread Model Data Export**](SpreadModelDataExport.md) processes sample data for immediate upload into an external software application that uses a diffusion model to see where CWD might go via host movements. 

<center>![Deer4](../../assets/Deer4.jpg)
<figcaption>Photo credit: Shutterstock </figcaption></center>

