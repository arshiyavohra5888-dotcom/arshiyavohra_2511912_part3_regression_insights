# Dataset Understanding

## 1. Dependent Variable

* monthly_sales

## 2. Potential Independent Variables

* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* holiday_flag
* customer_rating

## 3. Numerical Variables

* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* customer_rating
* monthly_sales
* monthly_profit

## 4. Categorical Variables

* region
* store_type
* month
* holiday_flag (binary)

## 5. Variables That May Need Cleaning or Transformation

* Missing values (if any)
* Encode categorical variables into dummy variables
* Verify percentage columns are stored as numeric values
* Check for outliers in marketing_spend, footfall, and monthly_sales

## 6. Variables That May Not Be Useful for Regression

* store_id (identifier only)
