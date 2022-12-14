# MechaCar_Statistical_Analysis

Purpose: Perform statistical analysis on AutosRUs’ newest prototype, the MechaCar, and determine possible trouble causes in the production that are blocking the manufacturing team’s progress. 

Resources: R, R-Studio 

## Deliverable 1: Linear Regression to Predict MPG

Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes

*Image 1. Using lm ( ) function  to fit linear models*

![This is an Image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%201.PNG)
 
*Image 2. Linear Regression Summary*

![This is an Image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%202.PNG)
 
#### Written Summary

•	Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset? Vehicle_length estimated coefficient of 6.267 and ground_clearance estimated coefficient of 3.546  

•	Is the slope of the linear model considered to be zero? Why or why not? No, the slope (the p-value) equates to 5.35e-11


•	Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not? Yes, but only 71.49%. The r-square value equates to 0.7149


## Deliverable 2: Summary Statistics on Suspension Coils

Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots

*Image 3. Summary Stats on Suspension Coils* 

![This is an image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%203.PNG)
 

*Image 4. Lot Summary Stats based on Suspension Coils*

![This is an image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%204.PNG)
 
#### Written Summary 

•	The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not? When looking at the total_summary our variance calculates to 62.29 which is well below the 100 but if we look at each individual lot we see lot3 well above the limit of 170.29.

## Deliverable 3: T-Test on Suspension Coils

Run t-tests to determine if the manufacturing lots are statistically different from the mean population

*Image 5. Overall T-test on Suspension Coils*

![This is an image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%205.0.PNG)
 
![This is an image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%205.PNG)
 
*Image 5.3. T-test Subset Parameter*

![This is an image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%205.3.PNG)

Using the subset parameter of the T-test we were able to      for each individual lot.   
 
*Image 6. T-Test on Lot 1*

![This is an image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%206.PNG)
 
*Image 7. T-Test on Lot 2*

![This is an image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%207.PNG)

 
*Image 8. T-Test on Lot 3*

![This is an image](https://github.com/IIrazoque/MechaCar_Statistical_Analysis/blob/f999181bfd57c38fb09a3a38f10bc30e2de11cc9/Images/Image%208.PNG)

 
#### Written Summary 


## Deliverable 4: Design a Study Comparing the MechaCar to the Competition 

Purpose: Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For statiscally studies we'll need look into Data, Variability, and statiscally questions. In this example, we can compare city & highway fuel efficiency of MechaCar vehicles versus those of the competitor.

Hypothesis: Are compact MechaCar vehicles more city & highway efficient when comparing them to the competitor. 

•	What metric or metrics are you going to test? In this example our metric/variable is city & highway fuel efficiency, mile per hour and distance at (ex 1,000 miles)

•	What is the null hypothesis or alternative hypothesis? compact MechCar vehicles are not efficient vehicles when comparing them to the competitor

•	What statistical test would you use to test the hypothesis? And why? comparison test such as ANOVA testing. What is the difference between the two vehicles

•	What data is needed to run the statistical test? Large data set with car type (compact, trucks, vans etc.), miles per gallon, miles per hours, city or highway driving, distance at 1,000 miles.
