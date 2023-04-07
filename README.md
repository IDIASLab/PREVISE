
# Introduction
This repository provides the code for the manuscript titled "Bayesian Network Modeling and Prediction of Transitions within the Homelessness System" by Khandker Sadia Rahman, Daphney-Stavroula Zois, and Charalampos Chelmis.

<!-- ## Citation
To cite our paper, please use the following reference:

Charalampos Chelmis and Khandker Sadia Rahman "Learning to Predict Transitions within the Homelessness System from Network Trajectories." IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining (ASONAM '22).

BibTeX:
``` 
@article{rahman2022asonam, 
  author = {Rahman, Khandker Sadia and Chelmis, Charalampos},
  title = {Learning to Predict Transitions within the Homelessness System from Network Trajectories},
  year = {2022},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  booktitle = {Proceedings of the 2022 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining},
  keywords = {socially important data science, computational social science, applied network science, human services},
  location = {Virtual Event, Netherlands},
  series = {ASONAM '22}
}
```
-->

## Quick Overview
Administrative data collected by homeless service providers offer a unique opportunity to understand how homeless individuals navigate the homeless system towards securing stable housing. However, the literature on predictive models in the context of homeless service provision has neglected the sequential nature of services that an individual receives over time. Our work addresses this gap by learning, from administrative data, a Bayesian network, which in turn can be used to accurately predict whether an individual will exit the system, or alternatively, the service she would be assigned to the next time she experiences homelessness. Experimental evaluation shows that the proposed approach outperforms prior art not only at predicting exit, but also the less frequent services (and thus more challenging to predict).

### Prerequisites
Python 2.7 or above and the following libraries
```
pandas, numpy, random, datetime, matplotlib, seaborn, bnlearn
```

### Files
```
   ToyDataset.csv: A sample dataset with the features and trajectories 
   Functions.ipynb: Contains the functions associated with the rest of files
   PREVISE: Computes the prediction for PREVISE model
```

### How to use

The toy dataset shows a snippet of the data used after data cleaning and feature preprocessing have been done. This data can be directly run through the jupyter notebook files for the following purposes:

1. Prepare the data for PREVISE
2. Split the data into train and test set
3. Predict the next step using the PREVISE
