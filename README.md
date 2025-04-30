# Customer-Segmentation

## Project Summary

Customer segmentation analysis is the process of dividing a customer base into distinct groups based on shared characteristics or behaviors to understand their needs and tailor marketing efforts more effectively. This allows businesses to move beyond a "one-size-fits-all" approach and create personalized experiences and targeted campaigns. 

In this project, I have used a mall dataset to identify different customer clusters leveraging Univariate and Bivariate clustering. Firstly, we examine the data by Exploratory Data Analysis(EDA) where different charts(histograms, boxplot, line graphs etc) were employed to understand its characteristics, identify patterns, and uncover potential relationships. From EDA, we discover a clear relation between Gender and Annual Income, Annual Income and Spending score and also gender ratio. We also drop customerID column, because it's an identifier, not a feature that carries meaningful information for analysis or modeling.

Then we did Univariate and Bivariate clutering using the KMeans and selecting n_cluster variable by elbow method. Interpretation per cluster,
    Cluster 3 is ideal for premium targeting – they earn and spend a lot.
    Cluster 4 could be trend-driven youth, spending high despite low income.
    Cluster 2 might include budget-conscious professionals.
    Cluster 1 may be non-target customers with low income and spending.
    Cluster 0 is a moderate group, average in all aspects.
