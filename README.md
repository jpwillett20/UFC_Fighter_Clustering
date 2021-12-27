# UFC_Fighter_Clustering
Use K-means and hierarchical clustering to cluster fighters from a UFC dataset found on Kaggle.

This was a project I did in my senior year at UNC in a machine learning class. My team wanted to analyze a sport that did not have much prior statistical research done in the past. Hence, we found a unique dataset on Kaggle that had statistics for thousands of fights in Ultimate Fighting Championship (UFC). We performed a variety of machine learning techniques like logistic regression, k-nearest neighbors, and clustering. On the team, I was tasked with clustering the the fighters frp, tje dataset using R.

In this repository, you can find the files used, the commented R code, the knitted HTML code of the file, and the final report that my team wrote for all of our analysis.

1) Four CSV files
yfcupdated.csv was the csv used most througout my portion of the project.

2) Code
ufc_fighter_clustering.rmd and ufc_fighter_clustering.html are the files that include my commented code for posturing the data and performing k-means and hierarchical clustering. The code also includes some initial findings.

3) Report
STOR_565_Final_Report.pdf is the final report that my team wrote for the entire final project. The findings and analysis for my portion of the project can be found on page 3-6.

Brief Overview of Findings:
K-means was the optimal algorithm for clustering the fighters. The optimal amount of clusters was three. The clusters can best be labeled as the following: timid fighters, aggressice fighters, indecisive fighters. Being in one of these clusters has significant implications on your success in the UFC.
