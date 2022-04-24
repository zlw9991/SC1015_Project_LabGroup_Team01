# SC1015_Project_LabGroup_Team01

| Members       |
| ------------- |
| Wei Zi      |
| Alphonsus      |
| Gracie |

## Table of Contents  
1. [Problem Definition](#problem-definition)  
2. [Files](#files)
3. [Dataset](#dataset)
4. [Data Visualization](#data-visualization)
5. [Best Random State Script](#best-random-state-script)
6. [Classification Tree](#classification-tree)
7. [Random Forest](#random-forest)
8. [Support Vector Machines](#support-vector-machines)
9. [Conclusions](#conclusions)
10. [Contributions](#contributions)
11. [References](#references)

<a name="headers"/>


## Problem definition:
Using the percentage change of variables yesterday & the percentage change of Bitcoin's price today, can we create a model that will use the percentage change of variables today to determine if the percentage change of Bitcoin's price tomorrow will be positive or negative?

Some notes:
- the time period will be 24/3/2022 to 14/9/2017.
- we consider zero percentage change to be still positive percentage change as buying with zero percentage change is still not a loss.
- negative change will be represented as 'N', positive or zero change will be represented with 'P'.

## Files:
This [Powerpoint](https://github.com/zlw9991/SC1015_Project_LabGroup_Team01/blob/main/LabGroup_Team01.pptx) will provide a detailed explaination for our project.

Each folder can be downloaded seperately: the jupiter notebooks are inside and can be run independently of each other.

There is a video reading out the presentation, but due to how github does not allow videos larger than 25MB, you will have to request, DM me to see it.

## Dataset:
The source csvs for our dataset cmb1/cmb1e.csv can be found [here](https://github.com/zlw9991/SC1015_Project_LabGroup_Team01/tree/main/1_DataVisualization).

The Dataset for the models used is cmb1.csv. cmb1e.csv is used for SVM only.

Datasets are present in each folder.

## Data Visualization:
The data visualization jupiter notebook can be found [here](https://github.com/zlw9991/SC1015_Project_LabGroup_Team01/tree/main/1_DataVisualization)

Visualizations used:
- Correlation Heatmap.
- Time Series.
- Linear best fit.
- Multi Variate Boxplot.

## Best Random State Script:
The Best Random State Script jupiter notebook can be found [here](https://github.com/zlw9991/SC1015_Project_LabGroup_Team01/tree/main/2_ClassficationTree_And_BestRandomState)

This script may take quite awhile to run due to searching for the best random state value from 1 to 1 million.

## Classification Tree:
The Classification Tree jupiter notebook can be found [here](https://github.com/zlw9991/SC1015_Project_LabGroup_Team01/tree/main/2_ClassficationTree_And_BestRandomState)

Details about accuracy, FPR, FNR, etc can be found in the slides.

## Random Forest:
The Random Forest jupiter notebook can be found [here](https://github.com/zlw9991/SC1015_Project_LabGroup_Team01/tree/main/3_RandomForest)

This script may take quite awhile due to gridsearch looking for the best depth and n value.

Details about accuracy, FPR, FNR, etc can be found in the slides.

## Support Vector Machines:
The Support Vector Machines jupiter notebook can be found [here](https://github.com/zlw9991/SC1015_Project_LabGroup_Team01/tree/main/4_SupportVectorMachines)

Details about accuracy, FPR, FNR, etc can be found in the slides.

## Conclusions:

- Classification Tree has the best test classification accuracy. 
- But depending on different requirements, other models may still be used:
    - Ie: Random Forest has the best FPR.


## Contributions

| Member/s:        | Worked on:           |
| ------------- |:-------------:|
| All (Various Contributions)*    | Dataset & Data Visualization |
| All (Various Contributions)*      | Best Random State Script      |
| Wei Zi | Classification Tree      |
| Gracie | Random Forest      |
| Alphonsus | Support Vector Machines      |

* The Dataset, Data Visualization & Best Random State Script was something we worked on together through trying different sources and methods while improving or correcting each others work. The final result you see here is what we agreed upon was the best to use.

## References:

For Dataset:
  - Quandl
  - Investing.com


