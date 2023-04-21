# SC1015: Intro to Data Science and AI Mini Project

## Description
This project focuses on using consumer's attributes to study their behaviour and how it affects a company's revenue and performance. This repository contains the Customer Personality Analysis dataset, our [finalised code](https://github.com/rachellimjh/SC1015-Project/blob/dev-Rheanne/SC1015%20Mini%20Project.ipynb) as well as the video presentation.

### Problem Statement: 
Utilising the chosen dataset, Customer Personality Analysis, coupled with various machine learning models, predict the likelihood of Customers responding to marketing campaigns.

On top of that, we analysed which factors influence the company’s revenue through studying the relationship between consumer traits and total expenditure. This allows companies to fine tune marketing strategies and increase revenue. 

Additionally, find the best machine learning model which best predicts revenue and customers' response to marketing strategies. 

### Our dataset: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis 

## Contributors 
 1. Rachel Lim Jia Huan - Data Extraction, Data Visualisation, Linear Regression, Clustering
 2. Rheanne Leong En Ting - Data Extraction, Data Visualisation, Support Vector Machine
 3. Minh - Random Forest
 
## Models used
1. Linear Regression
2. Support Vector Machine
3. Clustering
4. Random Forest Model

## Conclusion 
* Likelihood of customers participating in the company's campaign can be predicted using clustering
* Companies can tweak their marketing techniques to cater to families with children, earn below the mean income and spend less
* Clustering does improve the accuracy of the data but not significant in terms of predicting response 
* ....


## What we learnt
* Collaboration on GitHub
* Peforming feature engineering to improve usability of data
* Using stacked bar charts to analyse influence of predictors on response variables
* Support Vector Machine: 
     - Uses kernel trick to find the transform data to a higher dimension to find the optimal hyperplane which linearly separates the datapoints
     - Extreme data points of one attribute can dominate others, it is thus important to scale data before using SVM
* K-means Clustering
     - having too many features for clustering could become too difficult for clustering as the distance between the data points increases
     - Using elbow method to determine optimal number of clusters
     - Calculating silhouette score for the model to evaluae quality of clusters created by the algorithm
* Random Forest Model
     - Randomized search to find best hyperparameters
     - Grid search to refine results of randomized search 
     - Synthetic Minority Over-sampling Technique to oversample minority class in the imbalanced dataset
     - Association Rule Mining to discover relationships between variables 

## References
* put dataset
* sckilearn 
 
