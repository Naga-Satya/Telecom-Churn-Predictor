# Telecom-Churn-Predictor
A classic Machine Learning Algorithm for classifying the customers who are going to churn. The data used in the process is provided by a telecom company for educational 
predictive modelling purpose. 

## Analysis performed:
- Imputed missing values in continuous features by mean/median detection using boxplot analysis
### Imputed categorical missing values as follows: 
- Meaningful missing imputation 
- Frequent value imputation
- Normalised the target variable to gaussian ditribution
- Dropped highly Imbalanced features: 
- Highly skewed/imbalanced columns 
- Highly missing valued columns
- Binning of less frequent categorical values of a respective column

### Technique used for feature importance
PCA Dimensionality reduction technique

### Model Built: 
#### High Performance models:
- Decision Tree
- Random Forest 
- Logistic Regression 

#### Interpretable Model:
- Logistic Regression Model

#### Methods used to find important features for interpretable model
- p value significance
- Eliminating features by checking multi-collinearity
- Recursive Feature Elimination
 
#### Cross Validation Technique used
- GridSearchCV
- RandomisedSearchCV

#### Performace Metric focussed on:
Recall of the model.
Reason: The main aspect of the predictive models is to identify the customers about to churn properly. 
