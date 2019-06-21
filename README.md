# predicting_alcohol_content

Our model is to predict the alcohol content in a Wine Quality Dataset.In this model we are implementing PCA on the data set and maintaining 90% pca scores,Applying hierarchical clustering and k mean clustering and group them into 6 clusters
then select all the records of cluster 4 and then combine upto with PCs

package: Pandas, Numpy, Matplotlib, Seaborn,
Input variables (based on physicochemical tests):

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

Output variable (based on sensory data):

12 - quality (score between 0 and 10)


Description of data

Name of the data: Wine data from UCI Machine learning repository

Number of data points: 4898

Number of features: 11

Target attribute: Quality of wine

Range of target attribute: 3 to 9
