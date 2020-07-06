## MACHINE-LEARNING-MODELS-AND-LIBRARIES
In this project I have worked with wine dataset and have tried to explore libraries like Numpy,Pandas,Scikit,Matplotlib pyplots etc.

### OVERVIEW
#### DATA PREPOCESSING AND NORMALIZATION
In any Machine Learning process, Data Preprocessing is that step in which the data gets transformed, or Encoded, to bring it to such a state that now the machine can easily parse it. In other words, the features of the data can now be easily interpreted by the algorithm.
Normalization is a technique often applied as part of data preparation for machine learning. The goal of normalization is to change the values of numeric columns in the dataset to use a common scale, without distorting differences in the ranges of values or losing information. Normalization is also required for some algorithms to model the data correctly.
#### EXPLORATORY DATA ANALYSIS
Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.
#### CLASSIFICATION
I have used knn classifier function for normalized and unnormalized data with different distance metrics such as uniform,euclidean,manhattan distances etc.
#### FEATURE EXTRACTION
Feature extraction is a process of dimensionality reduction by which an initial set of raw data is reduced to more manageable groups for processing.The process of feature extraction is useful when you need to reduce the number of resources needed for processing without losing important or relevant information. Feature extraction can also reduce the amount of redundant data for a given analysis. Also, the reduction of the data and the machine’s efforts in building variable combinations (features) facilitate the speed of learning and generalization steps in the machine learning process.

I have implemented and PCA & LDA and compared their performance
#### LINEAR DIMENSIONALITY REDUCTION
Linear dimensionality reduction methods are used for analyzing high dimensional data, due to their simple geometric interpretations and typically attractive computational properties. These methods capture many data features of interest, such as covariance, dynamical structure, correlation between data sets, input-output relationships, and margin between data classes

I have implemented PCA,DUAL PCA and FDA and compared their performance.
#### NON LINEAR DIMENSIONALITY REDUCTION
High dimensional data is difficult to interpret and one of the approach to simply is to assume that the data lies in a non linear embedded manifold of lower dimension where visualization is easier.
The non linear dimensionality reduction techniques I have implemented are :<br>
-- ISOMAP <br>
-- LLE(Locally Linear Embedding)<br>
-- Kernel PCA<br>
-- Laplacian eigenmap<br>
-- T-sne<br>

Performance comparision of the above techniques is also done.
