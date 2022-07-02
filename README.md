# 2nd_Hand_Car_Price_Prediction

## Algorithm: - 

### 1) Import the relevant libraries

### 2) Preprocess the Raw Data:- 
-   i.   Descriptive Stats [all variables]
-   ii.  Variables of Interest
-   iii. Missing Values
-   iv.  Checking for Outliers [PDF] and reset index
-   v.   OLS Assumptions [independent <- dependent]
-   vi.  Relax Assumptions [log independent <- dependent]
-   vii. Multi-Collinearity Check [independent (high is worst)]
-   viii.Rearrange the Data [dependent ——— independent]
-   ix.  Dummy Categorical [relax 1st variable]

### 3) Parallel Linear Regression Model:-
-   i.   Declare Targets and Inputs
-   ii.  Standardize Inputs
-   iii. Train_Test_Spilt
-   iv.  Create the regression
-   v.   Weights and Bias df [+Weight ~ +target]
-   vi.  Feature Selection (F-regression)
-   vii. Plot and Compare targets and its prediction IP [y_hat <- prediction]
-   viii.Plot and Compare using Residual [y_train - y_hat]

### 4) Testing the Data:-
-   i.   Reseting the testing index
-   ii.  Predicting the Inputs test-set
-   iii. Plot and Compare targets and its prediction IP [y_hat <- prediction]
-   iv.  Plot and Compare using Residual [y_test - y_hat]
-   v.   Prediction’s Dataset Performance


#### Note:- All models have been trained and tested on Mac M1
