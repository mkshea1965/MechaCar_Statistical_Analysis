# MechaCar_Statistical_Analysis
This analytical review of AutoRUs' new MechaCar is to troubleshoot production troubles using R..
## Deliverable 1: Linear Regression to Predict MPG
![d1_1](https://user-images.githubusercontent.com/88520929/143722773-e99ce901-257c-4c68-865f-e44c2eb9a0a4.PNG)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vehicle length, and ground clearance both showed non-random amount of variance.

### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero because the correlation coefficient is 0.7149, which signifies moderately high correlation between the variables and mpg.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The model can show the prototypes with moderatley high effectiveness because of the correlation coefficient's tending towards 1.

## Deliverable 2: Summary Statistics on Suspension Coils
![d2](https://user-images.githubusercontent.com/88520929/143722776-4fcaa973-ce71-4a67-af3d-6c18046db244.PNG)
![d2_2](https://user-images.githubusercontent.com/88520929/143722788-b1466ece-1e9b-41fd-b7ce-d371a0a6adfa.PNG)

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not? 
For the total lots, the current manufacturing data's variance is below the threshold of 100 psi, and therefore meets the design specifications. Individually, however, lot 3's variance is 70 psi above the threshold and does not meet design specifications. Lots 1 and 2 are within the design threshold.

## Deliverable 3: T-Test on Suspension Coils
### In your README, create a subheading ## T-Tests on Suspension Coils, then briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
![d3_1](https://user-images.githubusercontent.com/88520929/143722828-82ae8015-c8ea-45c9-998d-dd6600b72cfa.PNG)
![d3_2](https://user-images.githubusercontent.com/88520929/143722829-44456f17-a655-46b9-aae6-5668cd46fb7e.PNG)
For the total lots' t-test, the p-value is greater than the alpha value of 0.05. Therefore, we fail to reject the null hypothesis being the true mean is equal to 1500. For the lot 1's t-test, the p-value is greater than the alpha value of 0.05. Therefore, we fail to reject the null hypothesis being the true mean is equal to 1500. For the lot 2's t-test, the p-value is greater than the alpha value of 0.05. Therefore, we fail to reject the null hypothesis being the true mean is equal to 1500. For the lot 3's t-test, the p-value is less than the alpha value of 0.05. Therefore, we reject the null hypothesis being the true mean is equal to 1500.

## Deliverable 4: Study Design: Comparing the MechaCar to the Competition
### What metric or metrics are you going to test?
In our study, we will test highway fuel efficiency as environmental concerns are growing among vehicle consumers.
### What is the null hypothesis or alternative hypothesis?
Null Hypothesis: MechaCar's prototypes average fuel efficiency equals the competitor's prototypes fuel efficiency.
Alternate Hypothesis: MechaCar's prototypes average fuel efficiency does not equal the competitor's prototypes fuel efficiency.
### What statistical test would you use to test the hypothesis? And why?
Two-sample t-test.
### What data is needed to run the statistical test?
We would need to collect average fuel efficiencies of prototypes for both MechCar and its competitor.
