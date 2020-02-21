# Statistics & Data
Learning the mathematics behind the predictions!

## Project Background

### Motivation:
Financial measures of a company can provide valuable information about the company’s future. 
The current financial measures can help predict the bankruptcy of a company in the near future. 
However, many complex econometric measure play role in the bankruptcy of a company, 
therefore, statistical learning based prediction model could be useful for bankruptcy prediction. 

### Method Analysis:
Classification models for bankruptcy prediction of a company using its econometric 
measures are explored using multivariate supervised learning approaches. This study addresses the 
handling of missing financial attributes, dimensionality reduction, and predictive model 
development with unbalanced data.As simply omitting the missing values increases the imbalance 
in the data, imputation of missing values is performed using the method of Principal Component 
Analysis. 

### Results:
Additionally, dimensionally reduction from 64 financial attributes to 21 features is 
performed using the principal component analysis.  Predictive models using various approaches 
including regression tree, support vector machine (SVM), logistic regression, neural network, and 
k-nearest neighbors (KNN) is studied.  The apparent error associated with the regression tree 
model is 3.08%, SMV model is 3.5%, logistic regression model is 4.31%, neural network model 
is 3.13%, and KNN model is 0.28%. Many models show high accuracy of prediction of non
bankruptcy status but show poor performance on bankruptcy status due to unbalanced data.  The 
KNN model with 7 neighbors is the best predictive model with all the statistical criteria of 
maximum accuracy, high specificity, and high sensitivity. 
