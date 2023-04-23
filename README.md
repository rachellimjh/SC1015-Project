# SC1015: Intro to Data Science and AI Mini Project

## Description
This project focuses on using consumer's attributes to study their behaviour and how it affects a company's revenue and performance. This repository contains the Customer Personality Analysis dataset, our [finalised code](https://github.com/rachellimjh/SC1015-Project/blob/dev-Rheanne/SC1015%20Mini%20Project.ipynb), [our video presentation](https://youtu.be/ZT0SrzIjTkc) and [presentation slides](https://docs.google.com/presentation/d/1V_O93jwCH7PgBfjQjZVZRz-8-6U-Xy1T1Y123nR3gIc/edit?usp=sharing)


![SC1015 Slides (1)](https://user-images.githubusercontent.com/125848730/233756231-5fa24fbc-6215-44e8-9724-d1af482e2d55.png)



### Problem Statement: 
Utilising the chosen dataset, Customer Personality Analysis, coupled with various machine learning models, predict the likelihood of Customers responding to marketing campaigns.

On top of that, we analysed which factors influence the company’s revenue through studying the relationship between consumer traits and total expenditure. This allows companies to fine tune marketing strategies and increase revenue. 

### Our dataset: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis 
 
## Models used
1. Support Vector Machine
2. Linear Regression
3. Clustering
4. Random Forest Model

## Conclusion 

### The likelihood of customers responding to marketing campaigns can be predicted by our machine learning models K-means clustering, random forest classifier, and support vector machine. 
* Based on the K-means clustering model, companies should use marketing techniques that are able to better target groups of customers that have a family, earn lower than average, and spend less
* Addition of clustering labels as attributes does not seem to improve the accuracy of the prediction
* From the random forest classifier, the company should prioritise Income first from these characteristics as it has an extremely higher importance score. Moreover, with regard to the products feature, the company should focus more on marketing and advertising Wines, Meat Products and Gold Products, since they have higher importance scores in influencing a customer's participation in a campaign.
* Furthermore, features AcceptedCmp3, AcceptedCmp5, AcceptedCmp1 have the highest importance score out of all 5 features. This suggests that the strategies used in first, third and fifth campaigns were decisive in getting Response 0 or 1 from the customers. Hence, the company should review these strategies and elaborate on them for future use and revise the strategies applied for the second and fourth campaigns.
* From using support vector machines, since the attributes of Places give us the highest classification accuracy, a recommended approach for the company to take is to focus their marketing and publicity on trying to attract customers from different platforms and sources, in order to boost their response in these campaigns.
* However, from using Support Vector Machines, the relatively higher classification accuracy of the polynomial kernel suggests that the relationships between predictor and variable may not be so straightforward(complex, non-linear relationship)

### The most important factors influencing the company's overall revenue are the customer’s income, Number of Catalog Purchases made, and the Number of Store Purchases made, based on our machine learning model: Multivariate Linear Regression.
* Factors that affects the company’s revenue are the customer’s income, Number of Catalog Purchases made, and the Number of Store Purchases made
* The company can focus on providing a range of products that caters to both lower and higher income groups in order to raise expenditure on both ends
* Regression shows that they can focus on their catalogue and in-store purchases to further boost sales since they affect total expenditure to a greater extent as compared to web purchases
* From our random forest classifier, the catalogue should be boosted first due to its importance score being highest. 

## What we learnt
* Collaboration on GitHub
* Peforming feature engineering to improve usability of data
* Using stacked bar charts to analyse influence of predictors on response variables
* Support Vector Machine: 
     - Uses kernel trick to transform data to a higher dimension to find the optimal hyperplane which separates the datapoints
     - The classification accuracy of each kernel trick can also indicate the kind of relationship between attributes and response(linear, complex, non-linear)
     - Extreme data points of one attribute can dominate others, it is thus important to scale data before using SVM
* K-means Clustering
     - Having too many features for clustering could become too difficult for clustering as the distance between the data points increases
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
 
