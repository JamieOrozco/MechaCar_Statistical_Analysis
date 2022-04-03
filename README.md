# MechaCar_Statistical_Analysis

## Overview of Project
The purpose of this analysis is to analyze AutosRUs’ newest prototype, the MechaCar. It is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.The following was conducted:

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.

## Deliverable 1: Linear Regression to Predict MPG

Below is a linear model that predicts the MPG of the prototypes using the data set provided from MechaCar_mpg file. 

<img width="299" alt="MechaCar" src="https://user-images.githubusercontent.com/95591222/161445548-e21ba30e-7e0b-4252-8d8b-e0d1fe69b8eb.png">
<img width="256" alt="Summary " src="https://user-images.githubusercontent.com/95591222/161445577-99d06206-e8fc-4f61-aceb-36c28c26b466.png">

According to our results, vehicle length and ground clearence have a significant impact on the prototype. The linear regression model resulted in p-values of 2.6x10-12 and 5.21x10-8. The intercept was also statistically significant, indicating that there are likely other factors, not included in our dataset, that have a strong impact on the MPG. This model predicts an accuracy of 71% according to Multiple R-Squared. This model has room for improvement but is still predicting a large portion of variablity. 

## Deliverable 2: Summary Statistics on Suspension Coils

<img width="178" alt="Total_Summary" src="https://user-images.githubusercontent.com/95591222/161452316-e1a96d4b-e4db-4b1b-a515-47acac18da93.png">
<img width="268" alt="Lot_Summary" src="https://user-images.githubusercontent.com/95591222/161452318-42e95a68-71e4-400e-a127-3dc3c5f2845b.png">

An RScript is written to create a total summary dataframe that has the mean, median, variance, and standard deviation for each lot. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Lot 1 and Lot 2 are both within design specifications they have similar mean and median. Lot 3 shows the most variance and exceeds the manufacturers specs because it is over 100 poinds per square inch.


## Deliverable 3: 3 T-Test on Suspension Coils

<img width="236" alt="Sample_Suspension" src="https://user-images.githubusercontent.com/95591222/161445662-485b5b03-309f-4d60-806c-851959a383fa.png">
<img width="233" alt="Sample_1" src="https://user-images.githubusercontent.com/95591222/161445888-60dcc7a1-4da3-406d-bf49-f514a9036f3f.png">
<img width="226" alt="Sample_2" src="https://user-images.githubusercontent.com/95591222/161445891-3c297f93-f247-4ea4-ab03-d5b8462856e6.png">
<img width="223" alt="Sample_3" src="https://user-images.githubusercontent.com/95591222/161445893-edcbbb14-2ac0-4f5a-9956-601d60ef0b95.png">

* The T-test for the suspension coils across all manufacturing lots shows that they are not statistically different from the population mean, and the p-value is not low enough (0.06028) for us to reject the null hypothesis.
* Sample 1 shows it's not statistically different from the population mean, and the p-value is not low enough (1) for us to reject the NULL hypothesis.
* Sample 2 shows it's not statistically different from the population mean, and the p-value is not low enough (0.6072) for us to reject the NULL hypothesis.
* Sample 3 shows it's slightly statistically different from the population mean, and the p-value is just low enough (0.04168) for us to REJECT the NULL hypothesis. 


## Summary

