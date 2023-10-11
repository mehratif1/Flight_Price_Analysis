# project1-team1
FLIGHT PRICE ANALYSIS

OBJECTIVES OF ANALYSIS:
 
 1. Does the ticket price depend on duration of the flight?
 2. Does the ticket price depend on the seasoning?
 3. Does the ticket price depend on the chosen airline?
 4. Does the ticket price depend on the chosen routes?
 5. Does the ticket price depend on the number of stops?
 
 DATA SOURCE:
 
In order to procced this analysis we gathered dataset from kaggel website https://www.kaggle.com/code/anshigupta01/flight-price-prediction/input

ANALYSIS WITH THE CHOSEN DATASET:
 
1. Use head, dtypes, size function for better understabding of the dataset.
2. Convet from excel format to csv in order to rich lightweight and as a result faster execution of code.
3. Cleaninng dataset, using isna function combine it with sum function to find out how much missing values in each column. Using dropna function with parameter how = any to delete all rows with missing values. Also delete column "Additional Info", becase there was no useful information for analysis.
4. Convert data in column "Date of Journey" from string to datetime type, sorting from begining, finding difference between start date and end date  - 337 days, exctacting months from "Date of Journey" in additional column in order to find out correlation between price and seasoning.
5. Convert data in column "Duration" from string to float type by using split and replace function.
6. Use value_counts function for better understanding the popular airline, routes, destinations.
7. Use groupby with aggregation
8. Creating pie charts, bar charts, scatterplots

   DATA VISUALISATION

<img width="587" alt="image" src="https://github.com/mehratif1/project1-team1/assets/142356334/32898ee0-fd62-4f1c-af6b-a33d01209457">
<img width="656" alt="image" src="https://github.com/mehratif1/project1-team1/assets/142356334/8a23ccc6-1d4b-4a8e-8ac4-d026621a3330">
<img width="635" alt="image" src="https://github.com/mehratif1/project1-team1/assets/142356334/f52a1531-5bb3-4e20-904a-c3483310313c">
<img width="665" alt="image" src="https://github.com/mehratif1/project1-team1/assets/142356334/f3fcc523-db59-4875-a632-94eead2e34e3">
<img width="441" alt="image" src="https://github.com/mehratif1/project1-team1/assets/142356334/f009bab1-ee09-4a8d-bb60-92feda657a32">
<img width="441" alt="image" src="https://github.com/mehratif1/project1-team1/assets/142356334/3dd6c3fb-0884-4daa-aae8-161fb6a20c89">



CONCLUSION:

Time Efficiency Matters: Shorter flights tend to correlate with lower ticket prices.

Stopovers Impact Cost: Flights with two or more stops often come with higher ticket prices. 

Seasonal Consistency: Seasonal fluctuations appear to have minimal influence on ticket prices.

Budget-Friendly Prevalence: Economical ticket options dominate the market, reflecting a strong preference for affordability among travelers.



