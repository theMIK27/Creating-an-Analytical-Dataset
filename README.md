# Creating-an-Analytical-Dataset
Project-3 Predictive Analytics Nanodegree by Udacity

# Scenario
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.

The manager has given the following information to work with:
1. The monthly sales data for all of the Pawdacity stores for the year 2010.
2. NAICS data on the most current sales of all competitor stores where total sales is equal to 12 months of sales.
3. A partially parsed data file that can be used for population numbers.
4. Demographic data (Households with individuals under 18, Land Area, Population Density, and Total Families) for each city and county in    the state of Wyoming. For people who are unfamiliar with the US city system, a state contains counties and counties contains one or more cities.

# Steps to Success
Step 1: Business and Data Understanding
Your project should include a description of the key business decisions that need to be made.

Step 2: Building the Training Set
To properly build the model, and select predictor variables, create a dataset with the given data:
1. City
2. 2010 census population
3. Total pawdacity sales
4. Household with under 18
5. Land area
6. Population density
7. Total families

Step 3: Dealing with Outliers
Once you have created the dataset, look for outliers and figure out how deal with your outliers. Use the IQR method to determine if there are outlier cities for each of the variables and then justify which city that has at least one outlier value should be removed.
