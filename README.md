# SC1015: Intro to Data Science and AI Mini Project

## Description
This project focuses on using consumer's attributes to study their behaviour and how it affects a company's revenue and performance. This repository contains the Customer Personality Analysis dataset, our [finalised code](https://github.com/rachellimjh/SC1015-Project/blob/dev-Rheanne/SC1015%20Mini%20Project.ipynb), [our video presentation](xxlink to youtubexx) and [presentation slides](https://docs.google.com/presentation/d/1V_O93jwCH7PgBfjQjZVZRz-8-6U-Xy1T1Y123nR3gIc/edit?usp=sharing)


![SC1015 Slides (1)](https://user-images.githubusercontent.com/125848730/233756231-5fa24fbc-6215-44e8-9724-d1af482e2d55.png)



### Problem Statement: 
Utilising the chosen dataset, Customer Personality Analysis, coupled with various machine learning models, predict the likelihood of Customers responding to marketing campaigns.

On top of that, we analysed which factors influence the company’s revenue through studying the relationship between consumer traits and total expenditure. This allows companies to fine tune marketing strategies and increase revenue. 

Additionally, find the best machine learning model which best predicts revenue and customers' response to marketing strategies. 

### Our dataset: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis 
 
## Models used
1. Linear Regression
2. Support Vector Machine
3. Clustering
4. Random Forest Model

## Conclusion 
* Based on the clustering model, companies should use marketing techniques that are able to better target groups of customers that have a family, earn lower than average, and spend less, since this cluster
* addition of clustering labels as attributes does not seem to improve the accuracy of the prediction
* factors that affects the company’s revenue are the customer’s income, Number of Catalog Purchases made, and the Number of Store Purchases made
* company can focus on providing a range of products that caters to both lower and higher income groups in order to raise expenditure on both ends
* regression shows that they can focus on their catalogue and in-store purchases to further boost sales since they affect total expenditure to a greater extent as compared to web purchases


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

## Contributors 
 1. @rachellimjh - Data Extraction, Data Visualisation, Linear Regression, Clustering
 2. @Rheanne8 - Data Extraction, Data Visualisation, Support Vector Machine
 3. @binhminh1 - Random Forest

## References
* https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis 
* https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html
* https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
* https://scikit-learn.org/stable/modules/svm.html#kernel-functions
 
