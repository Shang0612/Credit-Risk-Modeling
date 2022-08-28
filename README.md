# Credit-Risk-Modeling

Welcome to my credit risk modeling practice. Please view the file from P1 to P4. 

P1: You can see my detailed process on preprocessing raw-data, use Machine Learning SVM model to train and test 80%/20% data, calculate WOE & IV and filter out relevant dependent/independent variables.

P2: You can see my detailed process on PD model estimation and validation with variables selected from train/test files generated from P1. Input logistic regression analysis, and calculate ROC curve to see how well our model fits the test data. When it comes to model performance evaluation, I used two approaches: Gini Coefficient and Kolmogorov-Smirnov Coefficient. I builted up LGD model fit, EAD model fit, and in the last few steps, I used the model to generate thresholds for bank to further determine 'Cut-Off' line. 

P3: You can see my detailed process on Cross Validation. I imported 2015 data, the 'new' data, to test whether our model built in P2 is solid enough to perform latest dataset. After going through same preprocessing as P1 for the 2015 data, we find out our current model definitely require further investigation, modification to fit latest dataset better. 

P4: You can see my detailed process on the final calculations -- Expected Loss -- by using LGD, EAD, and PD model. Used logsitic regression and linear regression to simulate recovery rate, Credit Conversion Factor, and calculated Expected Loss portion comparing to capital. It is still very immature model and require further construction works, but overall it is such a great training for me to gain exposure into credit risk modeling.


Thank you for reading.


Shang Yang  2022.08.27
