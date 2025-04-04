---
title: Models
description: This is a description of the page.
---

# Models

The CWD Data Warehouse allows agencies to analyze data using models, software that intakes agency data and parameters and generates outputs. The model could be as simple as a data summary or as complex as a high-dimensional spatial analysis. Results of models help wildlife agencies efficiently plan CWD surveillance efforts and make data-driven decisions. 

## Available Models

### To Obtain Risk-Based Surveillance Quotas
* The [**Risk-weighted Surveillance Quotas Model**](RiskWeightedSurveillanceQuotasModel.md) incorporates risk factors for CWD to calculate surveillance point quotas per management unit. It is particularly applicable to states/provinces that have not yet detected CWD.

### To Obtain Statistically Rigorous Surveillance Quotas
* The [**Sample Size for Multiple Groups**](FreedomFromDiseaseClusteredPopulation.md) is used to determine the sample size needed to declare a population free from disease given that hosts naturally cluster (and share disease) on the landscape. 
* The [**Statistical Sample Quotas using Clustering**](StatisticalSampleQuotas.md) is used to determine the sample size needed for each subadministrative unit without finding a positive case to declare a population free from disease given that hosts naturally cluster (and share disease) on the landscape. 

### To Understand Outbreak Potential in Your System
* The [**Epizootic Risk Model**](EpizooticRiskModel.md) helps agencies decide where to sample and allows exploration of methods to reduce the epizootic potential of CWD.

### To Understand your System After Sampling Has Occurred
* The [**Prevalence Estimator Data Export**](PrevalenceEstimatorDataExport.md) function processes sample data for upload into an external app to estimate the maximum prevalence of CWD in areas for which no positive cases were found after sampling has been completed.
* The [**Disease Cluster Analysis Data Export**](DiseaseClusterAnalysisDataExport.md) function processes sample data for upload into an external app to determine if disease clusters are present or if disease is randomly distributed over time or space.
 

## In Programming Development
* [Contact Structure Model](ContactStructure.md) uses GPS collar data to determine contact structure among hosts in a herd. 
* [Disease Control Strategies Model](DiseaseControlStrategiesModel.md) used an agent-based framework to investigate ways to thwart disease progression.
* [Home Range Contamination Model](HomeRangeContaminationModel.md) uses Bayesian spatial modeling to pinpoint home ranges likely to harbor diseased hosts. 
* [Outbreak Response Tool](OutbreakResponseTool.md) uses resource selection functions to draw containment areas after the first confirmed disease positive case. 
* [Positive Predictor Model](PositivePredictorModel.md) uses machine learning to predict which counties will next test positive for disease. 
* [Sample Allocation using Optimal Control Model](SampleAllocationOptimalControl.md) uses optimal control theory to allocated resources between surveillance and prevention. It is particularly applicable to states/provinces that have not yet detected CWD.
* [Simple Prevalence Estimator](SimplePrevalenceEstimator.md) uses a statistical framework to determine underlying prevalence based on the number of samples that test negative for disease.  
* [Spread Model Data Export](SpreadModelDataExport.md) uses a diffusion model to see where disease might travel via host movements. 


## In Theoretical Development
The SOP4CWD [modeling team](../../modeling.md) is continually working on developing new models to help wildlife agencies create sound, data-driven CWD surveillance, management, and response plans. 

* The [**Western Expansion of the Risk-weighted Surveillance Quotas Model**](RiskWeightedSurveillanceQuotasModelWestern.md) incorporates risk factors for CWD specific to western North America.
* The [**Expansion of the Sample Allocation Model to Surveillance, Prevention, and Management**](SampleAllocationOptimalControlPartII.md) expands the Sampling Allocation Model using Optimal Control to areas with confirmed disease. 


<center>![Deer4](../../assets/Deer4.jpg)
<figcaption>Photo credit: Shutterstock </figcaption></center>

