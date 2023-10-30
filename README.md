<h1 align="center">Fraud Detection</h1>
<p align="center">
 <img src = "https://github.com/AhmedAbdElbassset/Fraud_Detection/assets/63741964/942a7e56-a69d-4b8f-b718-3540c45345af" width = "500">
</p>

## Introduction
This project focuses on building and evaluating machine learning models for fraud detection using the Bank fraud dataset from NeurIPS 2022. The dataset contains transactional data from a bank, labeled with binary indicators of whether each transaction was fraudulent or not. As we all know, fraud is a persistent problem in many industries, causing a huge financial loss, Dange to the reputation of the affected businesses, legal consequences and a lot more. The purpose of this project is to develop a robust fraud detection system that can quickly identify and prevent fraudulent activities before they cause significant harm.

## Motivation
The motivation of this Task lies in the potential consequences of the fraudulent activities. Fraud as we said can lead to a huge financial loss, Dange to the reputation of the affected businesses and legal consequences. Additionally, businesses must consider the ethical amplification of failing to prevent or detect fraud. So, a robust fraud detection system can help prevent these negative outcomes by quickly identifying and flagging potential fraud cases, protecting both the business and its customers.

### Getting Started

To get started with this project, you will need to clone the repository to your local machine. You can do this by running the following command in your terminal:

[git clone ](https://github.com/AhmedAbdElbassset/Fraud_Detection.git)

Once you have cloned the repository, you can navigate to the project directory and install the necessary dependencies by running:

pip install -r requirements.txt


## DataSet
<div>
<img src ="https://t4.ftcdn.net/jpg/04/75/03/07/360_F_475030738_kT8sJumBrd5E3cPDhzn0nWjHsGuP79u9.jpg" width ="200">
<div>
 
[Kaggel](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022) - dataset 

In 2022, the Bank Account Fraud (BAF) datasets were released at NeurIPS. 
There are six different datasets that mimic bank account fraud

we use dataset consist of The base dataset and its five variants include:
   - 1 million data instances each
   - 32 features

## Models
The baseline code has four models: 
 - RandomForest Classifier
 - Logistic Regression
 - XGBclassifier
 - Neural Network
   
 We improved the models' performance by fine-tuning their settings using random search.
 
After that, we added two more models:
  - DecisionTree Classifier 
  - ExtraTrees Classifier.


## Evaluation
We evaluate the performance of each model using several metrics, including AUC, precision, recall, and F1 score.

## Conclusion
Through this project, we have demonstrated the effectiveness of various machine learning models for fraud detection using the Bank fraud dataset. We hope that this project will be useful for researchers and practitioners in the field of fraud detection.  


<div>
 <p align="center">
 <img src= "https://news.mit.edu/sites/default/files/images/201809/MIT-Fraud-Detection-PRESS.jpg" width ="400">
</p>
<div>
