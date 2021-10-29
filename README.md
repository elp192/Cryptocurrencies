In Progress
## Overview of the Project
In this project, the following steps are applied to cryptocurrency [data](https://github.com/elp192/Cryptocurrencies/blob/0a22dc6ccfffbd24db1afbf95daf5b608196cc20/data/crypto_data.csv) to provide investors with valuable information about the cryptocurrency market.<br>
1) Preprocessed the data,<br>
2) Reduced the dimension of data by principal component analysis (PCA),<br>
3) Clustered data by K-means (unsupervised learning) algorithm (the number of K is determined using the elbow curve),<br>
4) Visualized results using Plotly.<br>

The tools utilized in the project are:<br>
- Languages: Python- codes are written in Jupyter Notebook.
- Dependencies: Scikit-learn, Plotly, and Pandas.

## Results
Figure 1 represents tradable cryptocurrencies. In this table, the list of information about name, algorithm, type of proof, total number of coins supplied, total number of coins mined, and classes related to 532 coins is provided. 
<p img align="center" width="100%">
<img width="400" alt="tradable_cryptocurrencies " src="https://user-images.githubusercontent.com/85843401/139328535-fdde31fd-e9a9-45a4-9193-13ed7c4283b9.png">
<figcaption>Figure 1: Information about tradable cryptocurrencies.</figcaption></figure/> 
<p align="center">

The result of K-means clustering based on PCA is demonstrated in Figure 2. As can be seen in this figure, cryptocurrencies are classified into four groups. From this figure, information of each point (i.e., algorithm, values of principal components, and type of algorithm) in each group is obtained by hovering over the data points.
Figure 3 represents a 2D scatter plot for total coins mined versus total coins supplied. This figure shows that class 2 has only one member with high values among four classes, which can be an outlier. Similar to figure 2, information about each data point (i.e., class, total coins mined and supplied, and coin name) can be shown in this figure by hovering over the data points.
  
<p img align="center" width="100%">
<img width="400" alt="3D" src="https://user-images.githubusercontent.com/85843401/139346394-88a9749a-9f3d-4e9a-9047-caa4ff6d9d37.png">
<figcaption>Figure 2: 3D scatter plot, K-means clustering of cryptocurrencies based on PCA.</figcaption></figure/> 
<p align="center">
<img width="460" alt="2D" src="https://user-images.githubusercontent.com/85843401/139440004-efdcdefc-25c1-4614-88b9-a6614ca96991.png">
<figcaption>Figure 3: 2D scatter plot, total coins mined versus total coins supplied.</figcaption></figure/> 
<p align="center">
