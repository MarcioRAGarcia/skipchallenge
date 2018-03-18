# SkipTheDishes DevOps Challenge


This is a sample of two simple pipelines using Jenkins.



1. Here we can divide the CI and CD pipeline in two:

*  In the CI pipeline, all code push'ed to GitHub repository is deployed to QA Cluster

![alt text](https://github.com/MarcioRAGarcia/skipchallenge/blob/master/CI_pipeline.png "CI pipeline")

  
*  After tests in QA, we can use the CD pipeline to deploy the changes that are approved in QA to the Production Cluster.

![alt text](https://github.com/MarcioRAGarcia/skipchallenge/blob/master/CD_pipeline.png "CD pipeline")




2. Or the most common approach is using the CI/CD pipeline in the same job, like this:

![alt text](https://github.com/MarcioRAGarcia/skipchallenge/blob/master/CI-CD_pipeline.png "CI CD pipeline")
