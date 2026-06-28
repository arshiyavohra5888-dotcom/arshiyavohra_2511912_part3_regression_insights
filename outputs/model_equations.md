# Dummy Variable Creation

## Categorical Variable Used
Region

## Dummy Variables Created
- Region_East
- Region_North
- Region_South

## Reference Category
West

## Why West Was Used as the Reference Category
To avoid the dummy variable trap (perfect multicollinearity), one category must be excluded. West is used as the baseline category. The regression coefficients for the other region dummy variables will represent the difference in monthly sales compared to stores located in the West region.

## Dummy Variable Encoding
- Region_East = 1 if Region is East, otherwise 0
- Region_North = 1 if Region is North, otherwise 0
- Region_South = 1 if Region is South, otherwise 0
- West = Reference category (all dummy variables = 0)




# Simple Regression Equations

## Model 1
Monthly Sales = 560777.35 + (2.1296 × Marketing Spend)

## Model 2
Monthly Sales = Intercept + (Slope × Footfall)

## Dummy Variables
Region_East
Region_North
Region_South

Reference Category:
West

## Final Model Selected
Marketing Spend simple regression model.

## Reason for Selection
Marketing Spend showed a positive relationship with monthly sales and provided measurable explanatory power. A multiple regression model would normally be preferred, but it was not completed because a regression analysis tool was unavailable in the current software environment.