# MechaCar_Statistical_Analysis
## Objective
- 

# Linear Regression to Predict MPG
## Summary
- The variables that provided a non-random amount of variance to the MPG values would be the vehicle length and ground clearance variables. The P-value for vehicle length is 2.60e-12. The P-value for Ground clearance is 5.21e-08. These two variables would be statistically unlikely to provide random amounts of variance to our linear model. In other words, vehicle length and ground clearance have significant impact on our model. 
- The slope of the linear model is not zero, given significant impact of the variables. 
- The R-squared for this model is 0.7149. Given this, we can conclude that statistically the data is a good fit for the model. The model does predict MPG of MechaCar prototypes effectively

![lm 1](https://user-images.githubusercontent.com/112899813/211084366-d2ab3052-1d73-441b-8411-fc573f8e4400.png)

## Summary Statistics & Suspension Coils



![lm 2](https://user-images.githubusercontent.com/112899813/211093017-a9638f12-b739-4bd7-96b2-cb34b6975b3b.png)

- The above image shows the summary statistics for the total_summary dataframe 

![lm 3](https://user-images.githubusercontent.com/112899813/211093426-55f31998-8ea6-4a12-8934-e5640a753d18.png)

- The above image shows the summary statistics for the lot_summary dataframe 

## Summary 
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Given this, Lot 3 would not meet design specification. Lot 3 has a variance of 170, which is well above the design specifications indicating that suspension coils must not exceed 100 pounds per square inch. 


# T-Tests on Suspension Coils


![lm 4](https://user-images.githubusercontent.com/112899813/211095379-691a6bcd-046e-4ee1-af7a-9c373f2e2f58.png)

- The above image is a simple t-test on all lots. Given the data, we can conclude that the total manufacturing lot is not significantly significant due to the p-value (0.06) being above our 0.05 threshold. 


















