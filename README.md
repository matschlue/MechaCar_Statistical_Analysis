# MechaCar_Statistical_Analysis

Review the production data for insights that may help the manufacturing team.
- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.

## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  - vehicle length
  - ground clearance
- Is the slope of the linear model considered to be zero? Why or why not?
  - The slope of the linear model is not considred to be zero because the p-value (5.35e-11) is smaller than the significance level (0.05).  
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  - This linear model predicts mpg of MechCar prototypes effectively due to the R-squared value of 0.7149. 

## Summary Statistics on Suspension Coils
The mean PSI of the suspension coils is 1498.78 and has a variance of 62.29. Since the variance is less than 100, the current manufacturing data meet this design specification for all manufacturing lots in total.
Only LOT 3 has a variance of around 170 and therefore does not meet the requirements. 

## T-Tests on Suspension Coils

## Study Design: MechaCar vs Competition
