# MechCar_Statistical_Analysis

## Overview of Project
The objective of this project was to review the production data of MechCar prototypes. This review will provide insight that could be helpul for the manufacturing team. 


##The deliverables for this project are:

*	Discover which variables predict the miles per gallon (MPG) for vehicle prototypes
* Collect summary statistics on the pounds per square inch (PSI) of suspension Coils.									
*	Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
*	Design a study to compare the MechaCar performance against vehicles from other manufacturers.

## Software
*	R Statistics
* Pandas Jupyter notebook									
* PostgreSQL

## Results 

### Linear regression to Predict MPG. 

A multiple liner regression model was executed to display if there is a significant relationship with the dependent variable. Vehicle length and ground clearance are the variables that provided a non-random amount of variance due to its low p-value. This means that these variables have a significant impact on MPG.


![image1](https://github.com/DannyJohnson-Hi/MechaCar_Statistical_Analysis/blob/main/Images/image1.PNG))


### Summary Statistics on Suspension Coils.

In this test, we are analysing the consistency of the manufacturing process across the production lots.  The results show that lots 1 (1.14) and 2 (10.13) present a small variance. 
Lot 3's manufacturing process does not deliver the same consistency when compared with lots one and two.

![image2](https://github.com/DannyJohnson-Hi/MechaCar_Statistical_Analysis/blob/main/Images/image2.PNG)

![image3](https://github.com/DannyJohnson-Hi/MechaCar_Statistical_Analysis/blob/main/Images/image3.PNG)


### T-Tests on Suspension Coil.

The analysis shows that p-value = 0.06 for the population of 1500 PSI.  It means that we fail to reject the null hypothesis for all lots grouped together considering that our significant value is 0.05.

The statistical hypotheses tested is below:

Null Hypothesis: There is no significant PSI mean difference between all manufacturing lot and individual lots. 
Alternative hypothesis: There is significant PSI mean difference between all manufacturing lot and individual lots.

###Combined lots test:


![image4](https://github.com/DannyJohnson-Hi/MechaCar_Statistical_Analysis/blob/main/Images/image4.PNG)

###Individual lot tests:

##Lot 1
![image5](https://github.com/DannyJohnson-Hi/MechaCar_Statistical_Analysis/blob/main/Images/image5.PNG)


##Lot 2
![image6](https://github.com/DannyJohnson-Hi/MechaCar_Statistical_Analysis/blob/main/Images/image6.PNG)


##Lot 3
![image7](https://github.com/DannyJohnson-Hi/MechaCar_Statistical_Analysis/blob/main/Images/image7.PNG)


### Study Design: MechCar vs Competion.

This study's design has the objective of comparing the performance of the MechCar against vehicles from other manufacturers. No statistical test will take place as this study is limited to addressing the following questions: 
1.	What metric or metrics are you going to test?
2.	What is the null hypothesis or alternative hypothesis?
3.	What statistical test would you use to test the hypothesis? And why?
4.	What data is needed to run the statistical test?

Answers:

1.	Fuel capability per class.

2.	Null Hypothesis: the fuel efficiency for cars in the same class are the same. 
Alternative Hypothesis: the fuel efficiency for cars in the same class are not the same.

3.	The two-sample T-test would be the used to compare the samples from different populations. I would also use a Boxplot to have a better visualization on the results.

4.	The data needed is fuel efficiency per car class from each competitor.
