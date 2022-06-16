# MechaCar_Statistical_Analysis

## Analysis Overview
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management needs us to review the production data for insights that may help the manufacturing team. We need to perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes, collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots, run t-tests to determine if the manufacturing lots are statistically different from the mean population, and design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.


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


## T-Tests on Suspension Coils

<img width="350" alt="All Lots PSI" src="https://user-images.githubusercontent.com/100392991/174160183-921a1e2f-c9b6-45ff-bcb7-a6eaa0cd0c6d.PNG">


1. The results of all three manufacturing lots are: Mean-1498.78 and P-Value-0.06028. This tells us that we fail to reject the null hypothesis and the evidence shows that the average of these three lots is very similar to the population average. 

<img width="500" alt="Individual Lots PSI" src="https://user-images.githubusercontent.com/100392991/174160234-526a1e1a-9c5e-4134-8a54-a6825675dc38.PNG">


2. Lot 1: Mean-1500 and P-Value-1. This tells us that we fail to reject the null hypothesis since this mean matches the mean of the poplutaion and the P-Value is above .05.

3. Lot 2: Mean-1500.2 and P-Value-.6072. This tells us that we fail to reject the null hypothesis of this lot also, since this mean is close to the population mean and the P-Value is above .05.

4. Lost 3: Mean-1496.14 and P-Value- .04168. This tells us that we can reject the null hypothesis because the P-Value is below the .05 level and there doesn't seem to be a statistical difference between this lots mean and the population mean. 

## Study Design: MechaCar vs Competition

1. What metric or metrics are you going to test?
  - Fuel Efficiency (with the rising costs of fuel currently)
  - Price
  - Safety Rating
 
2. What is the null hypothesis or alternative hypothesis?
  - Null Hypothesis: MechaCar meets the same mean of all vehicles in regards to fuel efficiency, price, and safety ratings.
  - Alternative Hypothesis: MechaCar does not meet (or is less than) all other vehicles mean(s) in regards to fuel efficiency, price, and safety ratings. 
 
3. What statistical test would you use to test the hypothesis? And why?
  - I think the best statistical test to yse to test this hypothesis would be the same one we performed above (mulitple linear regression) so that we can compare all of the data at once and make a fairly quick decision by comparing the means of MechaCar with all other vehicle types. 
 
4. What data is needed to run the statistical test?
  - I would need to know the fuel efficiency data which would be the average city mileage and the average highway milage for MechaCar Prototype and all similar vehicles. I would also need to know the MechaCar prices and all other similar vehicle prices. Lastly, I would need to know the safety ratings for the MechaCar and all other similar vehicles to compare data. 
 
 


