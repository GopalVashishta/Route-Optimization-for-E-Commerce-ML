# Route Optimization for E-Commerce Delivery

Problem Statement: Build an ML-enabled system to optimize e-commerce delivery routes for last-mile logistics.
Problem Description: Last-mile delivery is often inefficient. An ML model using clustering and optimization algorithms can analyze delivery locations, traffic patterns, and package priorities to recommend cost-effective routes, ensuring timely deliveries.

Data Collection:
1) Amazon Delivery DataSet: https://www.kaggle.com/datasets/sujalsuthar/amazon-delivery-dataset
2) Delhivery Dataset: https://www.kaggle.com/datasets/devarajv88/delhivery-logistics-dataset

Data Pre-Processing:
1) Removed a few columns and used encoding to convert categorical data into numerical data.
2) Filled the missing values of all the columns which either or Mean, Median, Mode.

Model Selection:
1) K-means Clustering: Cluster Orders based on geographical data.
2) (Tentative) VRP : To conjure a route which is efficient/optimal for delivery.
3) XGBoost: To estimate delivery time and route accurately.
