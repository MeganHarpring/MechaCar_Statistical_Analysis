# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="700" alt="Deliverable 1 code" src="https://user-images.githubusercontent.com/100392991/174133567-31a5a599-d5dd-4248-aae4-1a8a8ccad451.PNG">


1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  - The vehicle length and ground clearance both have a non-random amount of variance to the mpg values in the dataset as seen from calcculating the p-values.

2. Is the slope of the linear model considered to be zero? Why or why not?
  -  The slope is not equal to zero as shown by the p-value of 5.35e-11 which is quite smaller than the normal level of .05.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  - Yes, this linear model does do a good job at predicting mpg of MechaCar prototypes. We can see this by looking at the r-squared value of .7149 which tells us that about 71% of all predictions can be considered fairly accurate. 
 
 
 ## Summary Statistics on Suspension Coils
 
 <img width="300" alt="Total Summary" src="https://user-images.githubusercontent.com/100392991/174137061-4735d689-c9be-4113-a3d1-fa6670f33a1d.PNG">
 
 <img width="350" alt="Lot Summary" src="https://user-images.githubusercontent.com/100392991/174137150-5d6b98f1-6f3a-44ad-a3a5-169cae3f3d83.PNG">


 
 
 1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  - Lot 1 and Lot 2 meet the variance requirements, they do not exceed 100 lbs per square inch. 
  - Lot 3 does not meet that requirement, the variance for lot 3 is 170.3 which is a lot higher than the 100 pounds per square inch specification.
  - We can see that the manufacturing lots summary all together does meet the specifications, it shows that the average variance between the 3 lots is 62.29 which is well below the 100 pound specicification. This is because the variance for lots 1 and 2 are so low so it is important to look at all 3 lots separately because lot 3 is an outlier and probably needs to be inspected to see why there is such a high variance. 

