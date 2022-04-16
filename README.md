# MechaCar_Statistical_Analysis
Module 15
## Deliverable 1
## Linear Regression to Predict MPG
In Deliverable 1, we read in the Mechacar_mpg file as a dataframe, which contains 50 different Mechacar prototypes and multiple different metrics. We then performed a linear regression, passing through all the different metrics and adding in our dataframe. Lastly, we used the summary function to calculate the 'p' and 'r' values for our model. 
![image](https://github.com/aisligrace/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-04-16%20at%2012.16.47%20PM.png)


![image](https://github.com/aisligrace/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-04-16%20at%2012.17.48%20PM.png)

* Vehicle_length and ground_clearance were the two metrics that would provide a non-random amount of variance to the mpg, as they had the highest P and T values. 

* The slope of the linear model would not be 0. Our p value is 5.35e-11, which is much smaller than .05%. This indicates strong evidence against the null hypothesis. 

* The r squared value of our linear model was 0.7149, or 71% accuracy. For the purposes of this analysis, we can say this model does predict mpg accurately. 


## Deliverable 2

## Summary Statistics on Suspension Coils
For Deliverable 2, we read in the Suspension_coil file as a table. We then used the summarize function to get the mean, median, variance, and standard deviation and created a total_summary dataframe. We then created a lot_summary dataframe using the subset, summarize and groupby functions so that we could analyze the same variables lot by lot. 

![image](https://github.com/aisligrace/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-04-16%20at%2012.38.58%20PM.png)

* The variance of the suspension coils is not to exceed 100 pounds per square inch. When looking at the total_summary dataframe, the variance is well under 100 at 62.3. However, when comparing lot by lot, we saw that while lot 1 and lot 2 both had variances well under 100, lot 3 had a much higher variance at 170.29. Lot 3 is disproportionately affecting the total variance of the group and should be remedied.

![image](https://github.com/aisligrace/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-04-16%20at%2012.38.36%20PM.png)


## Deliverable 3

![image](https://github.com/aisligrace/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-04-16%20at%2012.45.32%20PM.png)


![image](https://github.com/aisligrace/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-04-16%20at%2012.46.23%20PM.png)


## Deliverable 4
## Study Design: MechaCar vs Competition
