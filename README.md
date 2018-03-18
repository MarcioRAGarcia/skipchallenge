# SkipTheDishes DevOps Challenge


This is a sample of a simple pipeline using Jenkins.

In this sample, we have two pipelines: CI and CD:

*  In the CI pipeline, all code push'ed to GitHub repository is deployed to QA Cluster

![alt text](https://github.com/MarcioRAGarcia/skipchallenge/blob/master/CI_pipeline.png "CI pipeline")

  
*  After tests in QA, we can use the CD pipeline to deploy the changes that are approved in QA to the Production Cluster.

