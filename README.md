# AWS_Sagemaker
Examples on using AWS Sagemaker to showcase my skill in it

## 1st example using a Notebook Instance
I used a common dataset to predict if a group of individuals had an income above a certain threshold.
In this project you can see how I imported the data, cleansed it, worked with libraries to interact with AWS using Python-like Boto3 and SageMaker-, uploaded data to an S3 bucket, imported the XGBoost algorithm, trained it, downloaded to the EC2 instance the reports generated from training, deployed to an endpoint, and tested its accuracy.

## 2nd example using SageMaker Studio
I created another notebook but this time using Sagemaker studio. The task is to detect fraudulent claims using again an XGBoost model for binary classification.  
This repository showcases my exploration and implementation of Amazon SageMaker tools to streamline the machine learning (ML) workflow. Through SageMaker Pipelines, Model Registry, and SageMaker Clarify, I've automated various ML lifecycle stages, from data processing to model deployment.
The SageMaker pipeline orchestrates data preprocessing, model creation, evaluation, and endpoint deployment. SageMaker Clarify helps ensure model fairness and transparency by assessing bias and explaining predictions.
### Key Features
- Automated ML lifecycle stages with SageMaker Pipelines
- Utilized Model Registry for tracking model versions and metadata
- Analyzed model bias and explained predictions using SageMaker Clarify
- Deployed an XGBoost model
