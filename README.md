# MechaCar_Statistical_Analysis

# Project Overview:
An analysis of car data using RStudio and R Console.

## Resources:

* Data Sources:

* Software: RStudios, R Console


## Results:
1. Linear Regression to Predict MPG:

As shown by the summary statistics below, we can address the following:

- The Intercept, vehicle_length, and ground_clearance provided non-random variance to the MPG values in the dataset.

- The slope of the linear model is not zero (m =! 0) because the Intercept, vehicle_length, and ground_clearance are significant and therefore not determined by random chance and error.

- The linear model does predict mpg of MechaCar prototypes effectively because of the r-squared (r^2 = 0.7149) value or coefficient of determination is > 0.7 and the P-value is < 0.05.

<img width="740" alt="Screen Shot 2022-03-30 at 2 36 39 PM" src="https://user-images.githubusercontent.com/93015602/160935236-2b6c798a-d55c-4ff1-821f-be462011eb8f.png">

<img width="736" alt="Screen Shot 2022-03-30 at 2 36 06 PM" src="https://user-images.githubusercontent.com/93015602/160935244-a30f4562-e99d-4af2-8b78-6d586e00b670.png">



2. Summary Statistics on Suspension Coils

- total_summary

<img width="704" alt="Screen Shot 2022-03-30 at 3 17 34 PM" src="https://user-images.githubusercontent.com/93015602/160940511-7d09334c-ed48-4815-b1d4-4e39a6e7a9aa.png">

<img width="697" alt="Screen Shot 2022-03-30 at 3 17 46 PM" src="https://user-images.githubusercontent.com/93015602/160940514-08122e08-6371-415f-8994-1cd92aeb75c5.png">

- lot_summary

<img width="657" alt="Screen Shot 2022-03-30 at 3 34 34 PM" src="https://user-images.githubusercontent.com/93015602/160942164-c0b1e633-cfc2-41ad-90fa-f30c4c981edc.png">

<img width="666" alt="Screen Shot 2022-03-30 at 3 34 23 PM" src="https://user-images.githubusercontent.com/93015602/160942169-72be219d-ad15-42ce-a976-dd6bbabf044b.png">

- According the the lot_summary as shown above, LOT 1 and 2 does meet specificiations, however, LOT 3 does NOT meet design specifications. The total summary, on the otherhand, DOES meet specifications as a whole. 


3. T-Tests on Suspension Coils

<img width="740" alt="Screen Shot 2022-03-30 at 6 52 58 PM" src="https://user-images.githubusercontent.com/93015602/160960448-270092a0-f442-4227-a6fe-d0fae15fbc1b.png">

- Assuming our significance level was the common 0.05 percent, our p-value is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar.

<img width="687" alt="Screen Shot 2022-03-30 at 7 21 07 PM" src="https://user-images.githubusercontent.com/93015602/160963327-61d33b70-69c1-4464-8ee5-4479b6f3f2bc.png">

Lot 1: Assuming our significance level was the common 0.05 percent, our p-value is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar.

<img width="693" alt="Screen Shot 2022-03-30 at 7 21 29 PM" src="https://user-images.githubusercontent.com/93015602/160963348-c76625d8-5b41-451c-a513-25388f2e8516.png">

Lot 2: Assuming our significance level was the common 0.05 percent, our p-value is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar.

<img width="706" alt="Screen Shot 2022-03-30 at 7 21 19 PM" src="https://user-images.githubusercontent.com/93015602/160963352-7566619c-fd75-46be-b920-f303c02b42a4.png">

Lot 3: Assuming our significance level was the common 0.05 percent, our p-value is BELOW our significance level. Therefore, we do have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically DIFFERENT.

<img width="740" alt="Screen Shot 2022-03-30 at 6 52 58 PM" src="https://user-images.githubusercontent.com/93015602/160963355-7a256765-6dfd-4835-8802-68bb7b2b5bf8.png">


## Study Design: MechaCar vs Competition


## Summary:

Additional Study Design Description: 
