### MLR Variable Selection Using Ridge Regression and Stepwise Methods on Wine Quality Data
### Overview:
The project aimed to predict wine quality using the Wine Quality Dataset through Multiple Linear Regression (MLR). The focus was on performing ridge regression for regularization and applying forward, backward, and stepwise selection methods to identify the most relevant features.

### Steps:
1. Data Loading: Loaded and splitted the dataset for both the steps below.
2. Ridge Regression: Used Ridge Trace to visualize the impact of the ridge parameter (λ) on model coefficients.
3. Variable Selection:
Applied three methods:
Forward Stepwise: Added variables one at a time based on their significance.
Backward Stepwise: Removed less important variables starting with all features.
Stepwise: Combined forward and backward methods to optimize the model.

### Results:
1. Ridge Regression reduced multicollinearity and overfitting by selecting an optimal λ value.
2. Forward Stepwise Selection provided the best predictive performance, with a balanced set of variables for wine quality prediction.


