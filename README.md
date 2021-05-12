# KNN (K-nearest neighbour)
## Supervised Machine Learning Algorithm


__KNN:__ K-nearest neighbour is a simple, supervised machine learning algorithm that is used for both classification and regression tasks. It performs these tasks by identifying the neighbours that are the nearest to a data point. For classification tasks, it takes the majority vote, and for regression tasks, it takes the average value from the neighbours. 

 

The k in KNN specifies the number of neighbours that the algorithm should focus on. For example, if k = 3, then, for a particular test data, the algorithm observes the three nearest neighbours and takes the majority vote from them. Depending on the majority of the classes from the three nearby points, the algorithm classifies the test data.

The k value should be an odd number because you have to take the majority vote from the nearest neighbours by breaking the ties. 


What should the ideal k value be? And what happens if you change it? Let's understand this with the help of the following diagrams that show the separation boundary between two classes for different values of 'k'.


![KNN](https://user-images.githubusercontent.com/8578949/117966334-698c9880-b341-11eb-8c19-8a2e50bf9330.png)


