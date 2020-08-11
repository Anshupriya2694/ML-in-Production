## Machine Learning in Production (Machine Learning Engineer Nanodegree Program)

This repository is a culmination of multiple Machine Learning Project created and deployed using AWS Sagemaker. The focus is on deployment tools and the machine learning workflow; answering a few big questions along the way:

* How to decide on the correct machine learning algorithm for a given task?
* How to utilize cloud ML services in SageMaker to work with interesting datasets or improve our algorithms?

To approach these questions, there are multiple real-world case studies, and steps from task and problem formulation to deploying models in SageMaker.

The ipynb files for each study will be present in this repository.

#### Case Study 1 - Population Segmentation using SageMaker

This project trains and deploys unsupervised learning models - PCA and k-Means clustering to group US counties by similaties and differences on AWS Sagemaker.

The data used is a portion of [US census data](https://www.census.gov/data.html). This is combined with unsupervised learning methods, extract meaningful components from that data and group regions by similar census-recorded characteristics. The insights obtained by deep diving into Principal Components Analysis (PCA) and K-Means clustering methods results in groupings that are used to inform things like localized marketing campaigns and voter campaign strategies.

#### Case Study 2 - Payment Fraud Detection

This case will demonstrate how to use supervised learning techniques, specifically SageMaker’s LinearLearner, for fraud detection. The payment transaction dataset is unbalanced, with many more examples of valid transactions vs. fraudulent, and I have investigated methods for compensating for this imbalance and tuning the model to improve its performance according to a specific product goal.

I have also worked on the same kaggle dataset for another project under my course IDS702 during the fall of 2019. The link for that project is - [Credit Card Fraud Detection] (https://github.com/Anshupriya2694/Credit-Card-Fraud-Detection). This project is written in R and explores Machine Learning Techniques like Logistic Regression, K-Nearest Neighbors and Decision Trees.

#### Case Study 3 - Custom Models - Non-Linear Classification [Moon Data Classification]

This case study demonstrates how to manage cases where classes of data are not separable by a linear line. A custom PyTorch neural network used for classifying data is trained and deployed.
The pytorch model classifies "moon data" (2-dimensional data whose classes are distributed to look a bit like moons in 2D space). 

#### Summary of Skills

![ML Production Framework](/Users/anshupriyasrivastava/Desktop/Udacity/Udacity ML Nanodegree/ML-in-Production)
Format: ![Alt Text](/Users/anshupriyasrivastava/Desktop/Udacity/Udacity ML Nanodegree/ML-in-Production)
