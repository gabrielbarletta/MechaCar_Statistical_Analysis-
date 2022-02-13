# MechaCar_Statistical_Analysis-

## Background
A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

## Linear Regression to Predict MPG
<img width="525" alt="D1" src="https://user-images.githubusercontent.com/92552837/153774018-d56d81a0-d4b4-4f1b-8064-b9d5aa006929.png">

## Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The variables that provide the greatest amount of random variance are ground_clearance and vehicle_lenght. 

## Is the slope of the linear model considered to be zero? Why or why not?
The slope is not considered to be zero. Looking at the p- value we can determine that it is less than 0.05. 

## Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The R-Squared is 71% which means that we will predict mpg value a 71% correctly. There are other variables that are not factored in our dataset that also contributes to the mpg variabilitly. 

## Summary Statistics on Suspension Coils
<img width="511" alt="Screen Shot 2022-02-13 at 3 25 50 PM" src="https://user-images.githubusercontent.com/92552837/153774046-b308db90-35e2-47c6-921d-bad70a174b4d.png">

## The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The total specifications are met with a variance of 62.29. Lots 1 and 2 are within the specifications. Lot 3 variance exceeds the specifications. 

<img width="498" alt="D3 LOT 1" src="https://user-images.githubusercontent.com/92552837/153774077-b59b2f8c-c65f-4181-9c3a-e9c86a9a0ec6.png">
Lot 1 is not significantly different from the population mean. 

<img width="528" alt="D3 LOT 2" src="https://user-images.githubusercontent.com/92552837/153774128-67db5123-c2d1-4c97-b7eb-398791a3f219.png">
Lot 2 is not significantly different from the population mean. 

<img width="522" alt="D3 LOT 3" src="https://user-images.githubusercontent.com/92552837/153774171-1382546c-6100-4a1f-b625-98d53c535228.png">
Log 3 is significantly different from the population mean. 

