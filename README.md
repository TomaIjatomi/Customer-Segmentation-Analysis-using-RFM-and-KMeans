# Customer-Segmentation-Analysis-using-RFM-and-KMeans
In this project, I categorized customers using the RFM technique and created clusters using KMeans algorithm for unsupervised learning.

## Resources
* Data Source: Data of an Online Retail store containing 541,909 records and 8 features. 
* Python Version: 3.9.12
* Packages: pandas, scipy, sklearn, matplotlib, seaborn

## Data cleaning 
* Dropped rows with invalid CustomerIDs (Assumed Guest Checkout)
* Created SaleValue column by multiplying Quantity and UnitPrice 
* Set appropraite datatype of some features for data manipulation

## Clustering
* Calculated Recency, Frequency and Monetary Value for each customer
* Created clusters using KMeans
* Calculated Overall RFM Score
* Assigned Customer segments based on Overall score
* Calculated the Optimal Number of Clusters to use for segmentation using Elbow method and Silhouette Method

## Some Insights

Distribution of RFM Metrics to Overall RFM Score

![2023-01-10 (1)](https://user-images.githubusercontent.com/117505903/211432805-0af2129f-acf3-4099-abea-72af938994e2.png)


Distribution of Customers to Overall RFM Score

![2023-01-10](https://user-images.githubusercontent.com/117505903/211432838-6a5f42d0-e488-4f36-b3a5-74f157f3a05d.png)
