# Uncovering-Customer-Segments-An-Analysis-of-Retail-Purchase-Data-using-Unsupervised-Learning
This project is an analysis of retail purchase data using unsupervised learning techniques. The goal of this project is to identify customer segments based on their purchasing behavior, in order to improve targeted marketing strategies and customer experiences.

Objectives
To perform exploratory data analysis on retail purchase data
To select and evaluate various unsupervised learning models for customer segmentation
To identify customer segments based on purchasing behavior
To draw conclusions and make recommendations based on the results
Methodology
Data collection: The data used for this project is publicly available and was obtained from the UCI Machine Learning Repository.
Data cleaning: The data was preprocessed to remove any missing or duplicate values and outliers.
Data preparation: New features were created to represent the total spending, purchasing frequency, unique items purchased, and time since last purchase.
Model selection: Several clustering algorithms were performed, including KMeans Clustering, Hierarchical Clustering, DBSCAN, Gaussian Mixture Model (GMM), and Spectral Clustering.
Model evaluation: The Silhouette Score, Calinski-Harabasz Index, and Davies-Bouldin Index were used to evaluate the performance of each model.
Customer segmentation: The clusters produced by the best performing models were visualized using violin plots to help identify customer segments.
Dataset Description
The retail purchase data contains information on transactions made by customers of a UK-based online retailer. The dataset consists of 541,909 rows and 8 columns, representing customer ID, product ID, quantity, price, transaction date, country, description, and stock code.

Exploratory Data Analysis (EDA)
The EDA involved creating a new dataframe that summarized each customer's total spending, purchasing frequency, unique items purchased, and time since last purchase. Histograms and barcharts were used to visualize the data and gain insights into the customers' behavior.

Model Selection and Evaluation
Several unsupervised learning models were trained on the retail purchase data, including KMeans Clustering, Hierarchical Clustering, DBSCAN, Gaussian Mixture Model (GMM), and Spectral Clustering. The Silhouette Score, Calinski-Harabasz Index, and Davies-Bouldin Index were used to evaluate the performance of each model.

Customer Segmentation
The best performing models were used to cluster the customers into different segments based on their purchasing behavior. Violin plots were used to visualize the clusters and identify key characteristics of each segment.

Conclusion
The KMeans Clustering and Hierarchical Clustering models performed the best in identifying customer segments based on purchasing behavior. The analysis revealed three distinct customer segments: high-spending and frequent buyers, low-spending and infrequent buyers, and a segment between the two. The findings of this project can be used to improve targeted marketing strategies and customer experiences.

References
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science. Available at: http://archive.ics.uci.edu/ml
C. Okoli, A. Nduka (2018) Clustering Techniques for Unsupervised Customer Segmentation, Journal of Computer Science and Its Application, 25(2), pp. 1-10.
