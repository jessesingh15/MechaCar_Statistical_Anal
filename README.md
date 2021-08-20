#MechaCar_Statistical_Anal
## Linear Regression to Predict MPG
<img width="344" alt="linear_regression_mpg" src="https://user-images.githubusercontent.com/79877531/130293358-fe485ec9-2542-47c0-bd99-146f8ffbfb57.png">
- Vehicle_length and Ground Cleanace are statistically unlikely to provide random amounts of variance to the the mpg values in the dataset.
- Slope is not considered zero. P-value = 5.35e-11 is lower than our significance level. Therefore, there is significance evidence to reject the null hypothesis.
- R-squared value is 0.71, this means 71% of predictions would be accurate.

## Summary Statistics on Suspension Coils
<img width="161" alt="total_summary" src="https://user-images.githubusercontent.com/79877531/130294985-49e1640d-41fa-411d-9fe6-adc7e9790c2c.png">
<img width="208" alt="lot_summary" src="https://user-images.githubusercontent.com/79877531/130294998-71d00786-091b-4de0-83c0-bd8307b1b23a.png">
- The variance of the suspension coil in lot 3 is more than 100 pounds per square inch, therefor design specifications have not been met.
- Lot 1 and 2 are both within design specifications with a nearly identical mean and median.

## T-Tests on Suspension Coils

### All Lots
![Total_T_Test](https://user-images.githubusercontent.com/79877531/130295672-54a3bb8c-ebf5-4db5-8873-0fcac14ceadb.png)
The T-test for suspension coils across all lots shows that they are not statistically different from the population mean, and the p-value is not low enough for us to reject the null hypothesis.

### Lot 1
<img width="227" alt="T_Test_Lot1" src="https://user-images.githubusercontent.com/79877531/130295993-63badc3f-6631-44fb-980f-424b3a3bce61.png">
The T-test for suspension coils for Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough for us to reject the null hypothesis.

### Lot 2
![T_Test_Lot2](https://user-images.githubusercontent.com/79877531/130296446-ca8db5ba-1667-4e45-9725-5c5ccaf6524a.png)
The T-test for suspension coils for Lot 2 shows that they are not statistically different from the population mean, and the p-value is not low enough for us to reject the null hypothesis.

### Lot 3
![T_Test_Lot2](https://user-images.githubusercontent.com/79877531/130296625-78f9dfd2-8423-4c3e-8bbd-e35561db87b2.png)
The T-test for suspension coils for Lot 3 shows that they are statistically different from the population mean, and the p-value is low enough for us to reject the null hypothesis.
