# Social_Netowrk_DA
EDA for my Social Network on Facebook 2022


The Task:

Use Network Science and Clustering Techniques to perform Friends Segmentation on my Facebook social network, .

The Solution Process:

- Data Gathering: use python and selenium to perform Automatic Web-scraping, the result is two dataset. [The First dataset](https://github.com/FaresGh1997/Social_Netowrk_DA/blob/main/Friends_Info.txt) represents the name, last_name and node_id for each node in my social-network. [The second dataset](https://github.com/FaresGh1997/Social_Netowrk_DA/blob/main/Edge_List.txt) represents the connnections among nodes in the network.
- Explarotory Data Analysis (EDA): using network science tools and Data Visulization techniques to extract Basic attributes and the network summary,
- Stastical Study: to find out if the network is randomly structured and the closest random graph to my social netowrk.
- centralities study: to identify key people in my social network and thier importance.
- AGGLOMERATIVE CLUSTERING : segmenting people in my social network using Machine Laerning Clustering techniques and find out if the clusters meet real-life senario.
  
The Findings:

customers were divided into 4 segments:

    segment 1 (yellow): low spenders, undergraduate students with no kids, the least number of customers, low income.
    segment 2 (blue): low spenders, postgraduates with either no kids or 2 kids, the largest number of customers, average income.
    segment 3 (black): max spenders, postgraduates with either no kids or 1 kid, high income.
    segment 4 (green): average spenders, undergraduates and postgraduates with 1 kid, average income.

segmentation based on spendings

Skills developed: pandas | scikit-learn | matplotlib | numpy | Clustering | Data Processing | Feature engineering | Dimensionality Reduction | Quality metrics | python | Orange | seaborn | Data Visualization.

This repo is part of the MMDA course, HSE, Moscow, Russia.
