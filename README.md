# MechaCar_Statistical_Analysis-

##Background
A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

## Linear Regression to Predict MPG

## Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The variables that provide the greatest amount of random variance are ground_clearance and vehicle_lenght. 

## Is the slope of the linear model considered to be zero? Why or why not?
The slope is not considered to be zero. Looking at the p- value we can determine that it is less than 0.05. 

## Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The R-Squared is 71% which means that we will predict mpg value a 71% correctly. There are other variables that are not factored in our dataset that also contributes to the mpg variabilitly. 

## Summary Statistics on Suspension Coils

## The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The total specifications are met with a variance of 62.29. Lots 1 and 2 are within the specifications. Lot 3 variance exceeds the specifications. 