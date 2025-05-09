---
title: Disease Cluster Analysis Data Export
description: Model Page on Website
---

# Disease Cluster Analysis Data Export
*Deployed*

The Disease Cluster Analysis Data Export allows users to pre-process CWD Warehouse sample data for immediate upload into the [SaTScan software](https://www.satscan.org/){target="_blank"}. The SaTScan software analyzes spatial and temporal data for any of the following interrelated purposes:
* Perform geographical surveillance of disease
* Detect spatial or space-time disease clusters
* Test whether a disease is randomly distributed over space, time, or space and time
* Evaluate the statistical significance of disease clusters

## Geographical Scale
* A collection of exact locations of hosts (latitude, longitude)

## Required Data
* Sample data, including exact latitude/longitude and exact harvest date

## User Inputs
* Cervid species of interest
* Season-years(s) of interest
* Desired scan type (spatial or temporal)

## Outputs
* A downloadable file of processed sample data for use in the SaTScan import wizard
* A downloadable file with a summary of Warehouse-selected inputs to assist in model creation in the SaTScan software

## More Information
For more information, go to the [CWD Data Warehouse User Manual: Disease Cluster Analysis Data Export](https://pages.github.coecis.cornell.edu/CWHL/CWD-Data-Warehouse/satscan.html){target="_blank"}.

## Code and Docker Image
To view the code, go to the [GitHub Repository: Disease Cluster Analysis Data Export](https://github.com/Cornell-Wildlife-Health-Lab/disease-cluster-analysis-data-export-v2){target="_blank"}. To view the docker image, go to the [Docker Hub: cwhl/disease-cluster-analysis-data-export-v2](https://hub.docker.com/r/cwhl/disease-cluster-analysis-data-export-v2){target="_blank"}.

## Citations
* Kulldorff M. 1997. [A spatial scan statistic](https://doi.org/10.1080/03610929708831995). Communications in Statistics: Theory and Methods. 26:1481-1496.
* Kulldorff M, Nagarwalla N. 1995. ]Spatial disease clusters: Detection and inference](https://doi.org/10.1002/sim.4780140809). Statistics in Medicine. 14:799-810.
* Kulldorff M, Athas W, Feuer E, Miller B, Key C. 1998. [Evaluating cluster alarms: A space-time scan statistic and brain cancer in Los Alamos](https://doi.org/10.2105/ajph.88.9.1377). American Journal of Public Health. 88:1377-1380.


