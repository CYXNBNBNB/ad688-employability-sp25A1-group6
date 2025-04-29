# AD688-Employability-sp25A1-Group6
Website: https://cyxnbnbnb.github.io/ad688-employability-sp25A1-group6/



90fgwan43
We performed K-Means clustering on our cleaned job dataset to explore how roles naturally group based on salary, employment type, education level, job duration, remote status, and location.

We first converted numerical and categorical fields into a format the model could understand, then standardized everything to ensure fairness across variables. We tested different numbers of clusters and plotted the SSE for each—this gave us an Elbow chart. While k = 9 had the lowest error, we chose k = 3 for better interpretability. It gave us fewer, more meaningful groups without overcomplicating the analysis.

We then validated our clusters by comparing them with actual employment types using two metrics—Normalized Mutual Information (NMI) and Adjusted Rand Index (ARI). These scores confirmed that our clusters aligned reasonably well with real-world labels.

To better understand the clusters, we created a series of scatter plots. We looked at how job duration, education, employment type, remote work status, and state related to salary across each cluster.

For example, we found that jobs with shorter durations (under 60 months) tended to offer higher salaries, while very long tenures often led to lower or more stagnant pay. This suggests job seekers might benefit from changing roles every 3–5 years to maximize earnings.

In terms of education, Associate degrees surprisingly had strong returns in some clusters, especially Cluster 2. Cluster 0 favored advanced degrees like Master’s, while Cluster 1 seemed to value experience and skills over formal education.

When we looked at employment types, full-time jobs consistently offered the highest salary potential across all clusters. Part-time and hybrid roles paid less on average, though hybrid roles offered flexibility.

For remote work, on-site roles had the highest pay ceiling, especially in Cluster 0. But in Cluster 1, remote roles were nearly as competitive, showing that remote work can still be lucrative in the right industries.

We also found interesting patterns across states. High-paying jobs were concentrated in places like California, New York, and Texas—but several mid-cost states also offered strong salaries in the right clusters.

Lastly, we built a multiple linear regression model to predict salary using the same features. After training, the model had a very low R² of 0.0757, meaning it only explained about 7.6% of salary variation. The RMSE was over $43,000, so predictions were not very accurate. This tells us that salary is likely influenced by more complex, possibly nonlinear factors.

We performed K-Means clustering on our cleaned job dataset to explore how roles naturally group based on salary, employment type, education level, job duration, remote status, and location.

We first converted numerical and categorical fields into a format the model could understand, then standardized everything to ensure fairness across variables. We tested different numbers of clusters and plotted the SSE for each—this gave us an Elbow chart. While k = 9 had the lowest error, we chose k = 3 for better interpretability. It gave us fewer, more meaningful groups without overcomplicating the analysis.

We then validated our clusters by comparing them with actual employment types using two metrics—Normalized Mutual Information (NMI) and Adjusted Rand Index (ARI). These scores confirmed that our clusters aligned reasonably well with real-world labels.

To better understand the clusters, we created a series of scatter plots. We looked at how job duration, education, employment type, remote work status, and state related to salary across each cluster.

For example, we found that jobs with shorter durations (under 60 months) tended to offer higher salaries, while very long tenures often led to lower or more stagnant pay. This suggests job seekers might benefit from changing roles every 3–5 years to maximize earnings.

In terms of education, Associate degrees surprisingly had strong returns in some clusters, especially Cluster 2. Cluster 0 favored advanced degrees like Master’s, while Cluster 1 seemed to value experience and skills over formal education.

When we looked at employment types, full-time jobs consistently offered the highest salary potential across all clusters. Part-time and hybrid roles paid less on average, though hybrid roles offered flexibility.

For remote work, on-site roles had the highest pay ceiling, especially in Cluster 0. But in Cluster 1, remote roles were nearly as competitive, showing that remote work can still be lucrative in the right industries.

We also found interesting patterns across states. High-paying jobs were concentrated in places like California, New York, and Texas—but several mid-cost states also offered strong salaries in the right clusters.

Lastly, we built a multiple linear regression model to predict salary using the same features. After training, the model had a very low R² of 0.0757, meaning it only explained about 7.6% of salary variation. The RMSE was over $43,000, so predictions were not very accurate. This tells us that salary is likely influenced by more complex, possibly nonlinear factors.

We performed K-Means clustering on our cleaned job dataset to explore how roles naturally group based on salary, employment type, education level, job duration, remote status, and location.

We first converted numerical and categorical fields into a format the model could understand, then standardized everything to ensure fairness across variables. We tested different numbers of clusters and plotted the SSE for each—this gave us an Elbow chart. While k = 9 had the lowest error, we chose k = 3 for better interpretability. It gave us fewer, more meaningful groups without overcomplicating the analysis.

We then validated our clusters by comparing them with actual employment types using two metrics—Normalized Mutual Information (NMI) and Adjusted Rand Index (ARI). These scores confirmed that our clusters aligned reasonably well with real-world labels.

To better understand the clusters, we created a series of scatter plots. We looked at how job duration, education, employment type, remote work status, and state related to salary across each cluster.

For example, we found that jobs with shorter durations (under 60 months) tended to offer higher salaries, while very long tenures often led to lower or more stagnant pay. This suggests job seekers might benefit from changing roles every 3–5 years to maximize earnings.

In terms of education, Associate degrees surprisingly had strong returns in some clusters, especially Cluster 2. Clust
We performed K-Means clustering on our cleaned job dataset to explore how roles naturally group based on salary, employment type, education level, job duration, remote status, and location.

We first converted numerical and
51ry using the same features. After training, the model had a very low R² of 0.0757, meaning it only explained about 7.6% of salary variation. The RMSE was over $43,000, so predictions were not very accurate. This tells us that salary is likely influenced by more complex, possibly nonlinear factors.

