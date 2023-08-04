# Social_Netowrk_DA
EDA for my Social Network on Facebook 2022


The Task:

Use Network Science and Clustering Techniques to perform Friends Segmentation on my Facebook social network, .

The Solution Process:

- Data Gathering: use python and selenium to perform Automatic Web-scraping, the result is two dataset. The First dataset

    Data Cleaning and Preprocessing: includes removing unnecessary columns, feature Engineering, Data Manipulation and using Visualization to perform EDA.
    Dimensionality Reduction: using PCA "Principal Component Analysis".
    Clustering: using K-Means Clustering, Hierarchal Clustering and using calinski_harabasz_score, silhouette_score to determine the optimal number of clusters.
    Data Visualization: used to evaluate the characteristics of the customers in the different clusters found the group.

The Findings:

customers were divided into 4 segments:

    segment 1 (yellow): low spenders, undergraduate students with no kids, the least number of customers, low income.
    segment 2 (blue): low spenders, postgraduates with either no kids or 2 kids, the largest number of customers, average income.
    segment 3 (black): max spenders, postgraduates with either no kids or 1 kid, high income.
    segment 4 (green): average spenders, undergraduates and postgraduates with 1 kid, average income.

segmentation based on spendings

Skills developed: pandas | scikit-learn | matplotlib | numpy | Clustering | Data Processing | Feature engineering | Dimensionality Reduction | Quality metrics | python | Orange | seaborn | Data Visualization.

This repo is part of the MMDA course, HSE, Moscow, Russia.
