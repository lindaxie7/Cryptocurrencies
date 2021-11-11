# Cryptocurrencies

We have the cryptocurrency data, it is not ideal, so the data need to be processed to fit the machine learning models. Since there is no known output for what we are looking for, unsupervised learning is used. To group the cryptocurrencies, I use the clustering algorithm. Reduced the principal components using PCA to reduce the dataset dimensions. Also, 2D and 3D scatter plot data visualizations were created to share the findings.


## Results

- Clustering Crytocurrencies Using K-Means, Finding the Best Value for k Using the Elbow Curve:
![1](https://user-images.githubusercontent.com/38533045/141230791-da0174c8-424d-4029-a2d9-7faeeca621f9.png)


- 3D-Scatter with the PCA data and the cluster

![2](https://user-images.githubusercontent.com/38533045/141230904-5863b827-4938-449d-9ac1-7371caede251.png)




- hvplot.scatter plot using x="TotalCoinsMined" and y="TotalCoinSupply"

![3](https://user-images.githubusercontent.com/38533045/141231057-ad9e6d7a-6124-471c-8e52-662916083f6d.png)

