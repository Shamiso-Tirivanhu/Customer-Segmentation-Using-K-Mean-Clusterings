# Customer-Segmentation-Using-K-Mean-Clusterings

## Table of Contents

1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Data Description](#data-description)
4. [Methodology](#methodology):
   4.1.1. [Data Preprocessing](#data-preprocessing)
   4.1.2. [K-Means Clustering](#k-means-clusstering)
   4.1.2. [Evaluation Metrics](#evaluation-metrics)
6. [Results](#results)
7. [Conclusion](#conclusion)
8. [Recommendations](#recommendaation)
9. [Usage](#useage)
9.[Contribution](#contribution)

## 1. Introductiuon 

This project aims to segment customers into distinct groups (Clusters 1-5) based on their purchasing behavior using the K-Means clustering algorithm. Customer segmentation helps businesses tailor their marketing strategies to different customer groups, improving customer satisfaction and business performance.

## 2. Project Overview

The project involves the following steps:

- Data collection and preprocessing
- Applying the K-Means clustering algorithm
- Evaluating the clustering results
- Visualizing the clusters

## 3. Data Description

The dataset used in this project contains customer information such as age, gender, annual income, and spending score. Each record represents a unique customer.

## 4. Methodology

  ## 4.1. Data Preprocessing

  Data preprocessing involves cleaning the data, handling missing values, and normalizing the features to ensure the K-Means algorithm performs optimally. There total rows in this particular CSV file is 200 rows and 5 columns. The following columns were dropped : Customer ID, Age and Gender as it was apparent to that they were not going to make a significiant contribution in the overall accuracy or precision of the K-Means algorithm.

  ## 4.2. K-Means Clustering

  K-Means clustering is an unsupervised machine learning algorithm that partitions the data into K clusters, where each data point belongs to the cluster with the nearest mean. In this particular data set, data was divided into 5 clusters. 

  ## 4.3. Evaluation Metrics

  The clustering results are evaluated using metrics such as the silhouette score and the elbow method to determine the optimal number of clusters. The number of clusters were subdivided into 5 clusters which displayed insightful insights. These clusters represents the different groups of people and their spending habits in the mall. 

## 5. Results

The results section presents the identified customer segments, their characteristics, and visualizations of the clusters. Key insights and patterns observed in the data are also discussed.


![Image_Alt](https://github.com/Shamiso-Tirivanhu/Customer-Segmentation-Using-K-Mean-Clusterings/blob/f17670f48f142eef42fb3794fa56f9ed49f42e8d/CustomerSegmentationImage.png)







| Cluster  | Annual Income (USD) range | Spending Score range |
|-----------|---------------|----------------|
| Cluster 1 | 55-60 | 40-60 |
|Cluster 2 | 75-80 | 60-100 |
| Cluster 3 | 75-140 | 5-40|
| Cluster 4 | 10-40 | 10-40 |
| Cluster 5 | 15-40 | 40-100 |

- The table above is a representation of the insights in this dataset. We can infer that people who have a lower income have the procluvirty of spending less at the Mall. Understandably so, given most items are expensive and thereby further implying that particular demographic group cannot afford as represented by cluster 4. 

- To circumvent this, the mall could consider having specials or deals in the Mall that caters to cluster 4. Surprisingly, cluster 4 earns a miniscule amount of money, yet that group buys more at the mall.
  
- It can be inferred that particular group, despite earning less spends a hefty amouunt possibly because they do not understamd theimportance of living within their means, budgetting and then the overspending.
  
- Cluster 2 represents people who earn more and therefore spend more. This might make sense as they probably can affotrd. The mall could look for sudy these people's purchasing habits to find what it is they tend to spend more money on and recommend more or similiar products or services.
  
- Cluster 1, they earn more, however, they spend less- most probably because they are financially intelligent


## 6. Conclusion

| Cluster  | Annual Income (USD) range | Spending Score range |
|-----------|---------------|----------------|
| Cluster 1 | 55-60 | 40-60 |
|Cluster 2 | 75-80 | 60-100 |
| Cluster 3 | 75-140 | 5-40|
| Cluster 4 | 10-40 | 10-40 |
| Cluster 5 | 15-40 | 40-100 |


This section summarizes the findings of the project, highlighting the effectiveness of K-Means clustering in customer segmentation and its potential applications in business strategies.

- The table above is a representation of the insights in this dataset. We can infer that people who have a lower income have the procluvirty of spending less at the Mall. Understandably so, given most items are expensive and thereby further implying that particular demographic group cannot afford as represented by cluster 4. 

- To circumvent this, the mall could consider having specials or deals in the Mall that caters to cluster 4. Surprisingly, cluster 4 earns a miniscule amount of money, yet that group buys more at the mall.
  
- It can be inferred that particular group, despite earning less spends a hefty amouunt possibly because they do not understamd theimportance of living within their means, budgetting and then the overspending.
  
- Cluster 2 represents people who earn more and therefore spend more. This might make sense as they probably can affotrd. The mall could look for sudy these people's purchasing habits to find what it is they tend to spend more money on and recommend more or similiar products or services.
  
- Cluster 1, they earn more, however, they spend less- most probably because they are financially intelligent

## 7. Recommendation

Suggestions for future work include exploring other clustering algorithms, incorporating additional features, and applying the model to different datasets.

## 8. Usage

To use the project, run the following command:

python main.py

## 9. Contribution

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

Feel free to customize this README to better fit your project details and personal preferences! If you need any further adjustments, just let me know.

