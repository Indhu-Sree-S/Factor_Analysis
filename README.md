# Factor_Analysis

Problem Statement:

Analysis the factors and eliminate the unnecessary features and records for the given dataset.

Problem analysis:

Preprocess the given data and then the scaled data are passed through various tests such as the Bartlett’s test of sphericity and the KMO test to determine whether the dimensionality reduction techniques such as the Factor Analysis can be applied on this dataset. With the help of Scree plot, the optimal number of factors are determined. Then the Factor Analysis is implemented using the Factor Analysis Module.

Inference:

	The Bartlett test show that the hypothesis of the correlation present among the features. For our dataset the p_value is 0.0 with 95% confidence. The KMO test can be used to determine the sampling adequacy. The KMO score of 0.841 indicates that the dataset satisfies the sampling adequacy. 

  From the above plot, the eigen values below 1 when factors are more than 6. So the optimal number of factors are 6. 

  Factor loading shows the weight of the variables. Here the eigen value shows that the amount of variance observed in each variable by the factor. It can be seen that the 14% of the common variance is explained by the factor 1. The 6 factors cumulatively explain about 55% of the variance due to the correlation among the observed variables. Uniqueness shows the amount of contradiction or independence. 
  
Conclusion:
  
Overall the factor analysis was able to do the dimensionality reduction which will play a key role in accuracy and computational cost. Thus the factor analysis is done for the given dataset.
