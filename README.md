# project1-team1
 Flight Price Prediction
 Objectives of analysis:
 1. Does the ticket price depend on duration of the flight?
 2. Does the ticket price depend on the seasoning?
 3. Does the ticket price depend on the chosen airline?
 4. Does the ticket price depend on the chosen routes?
 5. Does the ticket price depend on the number of stops?
In order to procced this analysis was gathered dataset from kaggel website https://www.kaggle.com/code/anshigupta01/flight-price-prediction/input
Have been done next munipulations with the chosen dataset:
1. Use head, dtypes, size function for better understabding of the dataset.
2. Convet from excel format to csv in osder to rich lightweight and as a result faster execution of code.
3. Cleaninng dataset, using isna function combine it with sum function to find out how much missing values in each column. Using dropna function with parameter how = any to delete all rows with missing values. Also delete column "Additional Info", becase there was no useful information for analysis.
4. Convert data in column "Date of Journey" from string to datetime type, sorting from begining, finding difference between start date and end date  - 337 days, exctacting months from "Date of Journey" in additional column in order to find out correlation between price and seasoning.
5. Convert data in column "Duration" from string to float type by using split and replace function.
6. Use value_counts function for better understanding the popular airline.

