# Unsupervised Machine Learning: Cryptocurrencies

## Purpose
The files in the `cryptocurrency_module` repository consist of the data files, starter code, and finished jupyter notebook code used to perform an unsupervised machine learning analysis over tradable cryptocurrencies.

## Analysis
The analysis performed used Pricipal Component Analysis (PCA) to reduce the dimensions of the data to three principal components. The K-Means algorithm was then applied to group the tradable currencies into four groups. Prior to performing the K-Means analysis, an elbow curve was utilized to find`n_clusters=4`. Finally, the data was visualized as a 3D scatter plot, 2D scatter plot, and as a data table.

###### Elbow Curve to Find `n_clusters`
<img src='elbow_curve.png'>

###### 3D Scatter Plot
<img src='scatter_3d.png'>

###### 2D Scatter Plot
<img src='scatter.png'>

###### Cryptocurrency Data Table
<img src='crypto_table.png'>