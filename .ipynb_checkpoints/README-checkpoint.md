## Predicting age-range from cookies with Amazon SageMaker Autopilot

This repository contains the example code for predicting the age range of web content visitors from their browsing cookies, leveraging AWS managed services such as:
* Amazon SageMaker Autopilot - For running AutoML on the classification problem
* AWS Glue & Amazon Athena - For auto-discovering, catalog, and prepare the source data
* Amazon SageMaker batch transfomation - For running predictions over a list of users finding out their age-range, and calculating the accuracy

---

For starting follow the notebooks provided in order. Examples are best if run on Amazon SageMaker Studio

0. [Prepare](./0-prepare.ipynb): Start with this notebook for setting up your Studio domain, roles, etc.
1. [Build & Train](./1-build_train.ipynb): Goes through the data preparation and AutoML end-to-end 
2. [Transform](./2-transform.ipynb): Runs a batch inference with the best model on the testing data, and evaluates the confusion matrix
3. [Automate](./3-automate.ipynb): Creates an automatic pipeline for running the previous tasks
4. [EMR-Spark](./4-EMR-Spark.ipynb): Shows an example of how to run a training backed-up by a Spark cluster

---
