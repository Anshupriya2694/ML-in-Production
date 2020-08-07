## Machine Learning in Production (Machine Learning Engineer Nanodegree Program)

This repository is a culmination of multiple Machine Learning Project created and deployed using AWS Sagemaker. The focus is on deployment tools and the machine learning workflow; answering a few big questions along the way:

* How to decide on the correct machine learning algorithm for a given task?
* How to utilize cloud ML services in SageMaker to work with interesting datasets or improve our algorithms?

To approach these questions, there are multiple real-world case studies, and steps from task and problem formulation to deploying models in SageMaker.

The ipynb files for each study will be present in this repository.

### Case Study 1 - Population Segmentation using SageMaker

This project trains and deploys unsupervised learning models - PCA and k-Means clustering to group US counties by similaties and differences on AWS Sagemaker.

The data used is a portion of [US census data](https://www.census.gov/data.html). This is combined with unsupervised learning methods, extract meaningful components from that data and group regions by similar census-recorded characteristics. The insights obtained by deep diving into Principal Components Analysis (PCA) and K-Means clustering methods results in groupings that are used to inform things like localized marketing campaigns and voter campaign strategies.

