# Fuel-Consumption-Dataset-EDA
 
The dataset is downloaded from Kaggle.com. It comprises the following 15 columns:
1 - Year
2 - Make
3 - Model 
4 - Vehicle Class
5 - Engine Size (L)
6 - Cylinders
7 - Transmission
8 - Fuel Type
9 - Fuel Consumption (L/100Km)
10 - Hwy (L/100 km)
11 - Comb (L/100 km)
12 - Comb (mpg)
13 - CO2 Emissions (g/km)
14 - CO2 Rating
15 - Smog Rating

Firstly, the focus is on two areas:
1 - Outliers
2 - Missing or null values

There were no visible outliers in the data.
The values of the dataframe series' are not extra less or extra large, therefore, no technique was applied to remove any outliers. 
Next, there were a lot of null values in each dataframe series. Either mean() or the maximum of all was used to replace the missing or null cells.

After removing the null values for all the columns, following five analysis were made:
1 - A Pairplot with hue attribute as 'Fuel Type' and selected columns as 'Engine Size (L)','Cylinders','Fuel Consumption (L/100Km)','Hwy (L/100 km)','Comb (L/100 km)','Comb (mpg)','CO2 Emissions (g/km)','CO2 Rating','Smog Rating'.
2 - Another Pairplot with hue attribute as 'Transmission' and selected columns as 'Engine Size (L)','Cylinders','Fuel Consumption (L/100Km)','Hwy (L/100 km)','Comb (L/100 km)','Comb (mpg)','CO2 Emissions (g/km)','CO2 Rating','Smog Rating'.
3 - A line graph showing how 'Cylinders' is related with 'CO2 Emissions'.
4 - A bar graph showing how 'Cylinders' is related with 'CO2 Rating'.
5 - A horizontal bar graph showing how 'Cylinders' is related with 'Smog Rating'.

