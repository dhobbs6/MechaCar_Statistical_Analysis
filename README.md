# MechaCar_Statistical_Analysis
## Objective
- This analysis requires erforming multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes, collecting summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots, running t-tests to determine if the manufacturing lots are statistically different from the mean population, and finally designing a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. This is all to aid Jeremy and the data analytics team in reviewing the production data for insights that may help the manufacturing team solve their production troubles that are blocking the manufacturing team’s progress.

# Linear Regression to Predict MPG
## Summary
- The variables that provided a non-random amount of variance to the MPG values would be the vehicle length and ground clearance variables. The P-value for vehicle length is 2.60e-12. The P-value for Ground clearance is 5.21e-08. These two variables would be statistically unlikely to provide random amounts of variance to our linear model. In other words, vehicle length and ground clearance have significant impact on our model. 
- The slope of the linear model is not zero, given significant impact of the variables. 
- The R-squared for this model is 0.7149. Given this, we can conclude that statistically the data is a good fit for the model. The model does predict MPG of MechaCar prototypes effectively

![lm 1](https://user-images.githubusercontent.com/112899813/211084366-d2ab3052-1d73-441b-8411-fc573f8e4400.png)

## Summary Statistics & Suspension Coils



![lm 2](https://user-images.githubusercontent.com/112899813/211093017-a9638f12-b739-4bd7-96b2-cb34b6975b3b.png)

- **The above image shows the summary statistics for the total_summary dataframe** 

![lm 3](https://user-images.githubusercontent.com/112899813/211093426-55f31998-8ea6-4a12-8934-e5640a753d18.png)

- **The above image shows the summary statistics for the lot_summary dataframe**

## Summary 
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Given this, Lot 3 would not meet design specification. Lot 3 has a variance of 170, which is well above the design specifications indicating that suspension coils must not exceed 100 pounds per square inch. 




# T-Tests on Suspension Coils


![lm 4](https://user-images.githubusercontent.com/112899813/211095379-691a6bcd-046e-4ee1-af7a-9c373f2e2f58.png)

- **The above image is a simple t-test on all lots. Given the data, we can conclude that the total manufacturing lot is not significantly significant due to the p-value (0.06) being above our 0.05 threshold**

# T-tests for lots 1-3


![lm 5](https://user-images.githubusercontent.com/112899813/211096599-4bd5eca0-a567-495c-9d0c-6cbbdb123f66.png)

- **The above image would be the t-test for lot 1**


![lm 6](https://user-images.githubusercontent.com/112899813/211096939-90f6e2f9-5e86-4d11-9d91-eab5a4088e3d.png)

- **The above image would be the t-test for lot 2**


![lm 7](https://user-images.githubusercontent.com/112899813/211097045-c1e22e28-0d88-44ac-8e88-9d5bf1d8c16b.png)

- **The above image would be the t-test for lot 3**

## Summary 
- For lots 1 & 2, when looking at the data, we can determine that both lots are not statistically significant given that both lots have a p-value above our 0.05 threshold. Both lot 1 & 2 have a measn of 1500, meaning that they falls in the 95% confidence interval. On the other hand, lot 3 has a p-value of 0.04 which would prove statistically significant with respect to our 0.05 threshold. Lot 3 also has a mean of 1496. 

# Study Design: MechaCar vs Competition 
**Write a short description of a statistical study that can quantify how the MechaCar performs against the competition**

-**What metric or metrics are you going to test?**

The metrics that I would test would be maintenance cost and fuel efficiency 

-**What is the null hypothesis or alternative hypothesis?**

The null hypothesis is that the MechaCar is no different from the competition in terms of maintenance cost and fuel efficiency

-**What statistical test would you use to test the hypothesis? And why?**

I would use a multiple linear regression given that I am testing how strong the relationship is among multiple variables. 

-**What data is needed to run the statistical test?**

In order to run the statistical test, I would need sample data on maintenance costs and fuel efficiancy with respect to MechaCar products and their competition. 













