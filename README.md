## Predicting age-range from cookies with Amazon SageMaker Autopilot

This repository contains the example code for predicting the age range of web content visitors from their browsing cookies, leveraging AWS managed services such as:
1. Amazon SageMaker Autopilot - For running AutoML on the classification problem
2. AWS Glue & Amazon Athena - For auto-discovering, catalog, and prepare the source data
3. Amazon SageMaker batch transfomation - For running predictions over a list of users finding out their age-range, and calculating the accuracy

For starting follow the notebooks provided in order.
Examples are best if run on Amazon SageMaker Studio, start with the notebook "[0-prepare](./0-prepare.ipynb)" for instructions.

---
