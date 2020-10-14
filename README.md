# Operationalizing ML Models

John Hoff  
Machine Learning Architect  
jhoff@productiveedge.com  

This is the supporting material for presentations given on operationalizing machine learning models using Azure Databricks and Azure Machine Learning Services.

![Step 1: Prepare](https://drive.google.com/uc?export=view&id=1HqlB2DVDpn2rTJxmbtLLg-5_egbVCYvK)

Each of the notebooks created for this presentation have been provided in this library in both IPython notebook format DBC archive format.  The IPython notebooks are for viewing directly within GitHub.  The DBC archives are for importing into Azure Databricks to be run.

## Requirements

### Azure Subscription Quotas
Standard DSv2 Family vCPUs and Total Regional vCPUs
+ 10 for ACI model deployment
+ 20 for AKS model deployment

### Azure Machine Learning Services
+ Active Azure ML Workspace
+ No special configuration required

### Azure Databricks
+ Active Azure Databricks Workspace
+ Running interactive cluster
  + Smallest possible cluster works fine
    + single driver node
    + single worker node 
  + 7.3 TLS ML (non-GPU)
  + Python modules installed
    + azureml-sdk[databricks]

_**Please Note: The ACI and AKS deployment scenarios are not currently supported in these
notebooks.  These notebooks will be updated once Databricks and Microsoft have sorted out
the current issues with native Spark MLlib model deployments.**_
