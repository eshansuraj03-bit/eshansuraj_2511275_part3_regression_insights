Understand the Dataset
1. Dependent Variable
The variable we want to predict is monthly_sales. This is your dependent (Y) variable.

2. Independent Variables
Possible independent variable	are marketing_spend, footfall, avg_discount_pct, staff_count, inventory_availability_pct, competitor_distance_km, holiday_flag and customer_rating. 

3. Numerical Variables
Possible independent variable	are marketing_spend, footfall, avg_discount_pct, staff_count, inventory_availability_pct, competitor_distance_km, customer_rating, monthly_sales and monthly_profit.

5. Categorical Variables
The variable Categories are region, store_type and month.

7. Variables needing transformation
The dummy variables are region and store_type.

6. Variables not useful
The store_id (only an identifier) may not help regression.

Regression Analysis of Store Performance
Business Problem Summary
The aim of this project is to identify the factors that affect monthly sales and determine which variables are most useful for predicting sales. The results help management make better business decisions.

Dataset Description
The dataset contains information about store performance, including monthly sales, marketing spend, footfall, discounts, inventory availability, customer ratings, and region. It includes 320 store records.

Dependent and Independent Variables
Dependent Variable (Monthly Sales)
Independent Variables (Marketing Spend, Footfall, Average Discount Percentage, Inventory, Availability Percentage, Customer Rating, Region (Dummy Variable))

Regression Approach
The analysis included:
* Five Simple Linear Regression models (one independent variable at a time).
* One Multiple Linear Regression model using Marketing Spend, Footfall, Average Discount Percentage, and Region (West Dummy).

Dummy Variable Approach
The categorical variable **Region** was converted into a dummy variable.
* **North** was used as the reference category.
* **West Dummy = 1** if the store is in the West region.
* **West Dummy = 0** otherwise.

Model Comparison Summary
Among the simple regression models, Footfall had the highest R² value (73.63%) and was the strongest individual predictor.
The Multiple Regression Model achieved the highest R² value of 78.73%, making it the best-performing model.

Final Model Selected
The Multiple Linear Regression Model was selected because it explains 78.73% of the variation in monthly sales and includes multiple important business factors.

Business Recommendation
The company should focus on increasing footfall and investing in marketing, while maintaining an effective discount strategy. These factors have the greatest impact on monthly sales.

Assumptions and Limitations
Assumptions
* Linear relationship exists between variables.
* Data is accurate and complete.
* Regression assumptions are reasonably satisfied.

Limitations
* The model does not include factors such as competition, seasonality, customer preferences, or economic conditions.
* Regression shows association between variables but does not prove cause and effect.

Screenshots Included
simple_regression_output.png
multiple_regression_output.png
model_comparison_preview.png
residuals_preview.png

