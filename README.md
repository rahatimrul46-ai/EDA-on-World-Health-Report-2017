📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the World Happiness Report 2017 dataset.
The objective is to understand the factors that influence happiness across different countries and regions.
This project demonstrates data cleaning, indexing, grouping, statistical analysis, and visualization techniques used by data scientists.

🔎 Exploratory Data Analysis Workflow

**A. Understand your data:**

1.Import the database as pandas dataframe
2.How does the data look like?
3.How big the data is?
4.What is the data type of columns?
5.How does the data look like mathematically?
6.Are there any missing values?
7.Are there any duplicated values?
8.List the top 10 happiest country
9.List the 10 least happiest country

10.Find rows with null values and delete those rows.
**B.Indexing and grouping:**

1. Use the column 'Region' to create a separate DataFrame containing the data points from each of the six regions: North America, Latin America, Western Europe, Eastern Europe, Asia Pacific, Africa.
2. Compute the mean happiness score for each region and rank the regions from most happy to least happy.
3. Compute the number of countries in each region that have a happiness score above 6.0.
**C. Happiness Score Analysis:**

1.Which country has the highest happiness score?
2.Which country has the lowest happiness score?
3.What is the average happiness score of all countries?
**D.Region-Based Analysis:**

1.What is the average happiness score for each region?
2.What is the highest happiness score of each region?
3.Which region has the highest average happiness score?
4.How many countries belong to each region?
**E.Feature-Based Analysis:**

1.Which country has the highest GDP per capita?
2.Which country has the highest social support?
3.Which country has the highest life expectancy?
4.Which country has the lowest freedom?
**F.Correlation & Relationship:**

1.What is the correlation between happiness score and GDP per capita?
2.Which variable has correlation greater than 0.7 with happiness score?
3.All correlations.
4.Which variable has negative correlation with happiness score?
5.Which two variables has the highest correlation with each other?
**G.Bar plot of the Happiness Score**
1. Obtain a horizontal bar plot of the Happiness Score of the top 10 countries. Your bar chart should have the names of the countries are listed vertically along the
y-axis and the x-axis should have labels for each number from 0 to 8. Ensure that the chart has an appropriate title and labels.
2. You will now modify the bar chart you obtained in step 1 to turn into a stacked bar chart where the overall happiness score is divided into the seven parts corresponding to the columns:
  * Economy
  * Family
  * Health
  * Freedom
  * Generosity
  * Corruption
  * Dystopia
  Choose a distinct color for each category and include an appropriate legend with your chart.
3. Obtain the same stacked horizontal bar chart as in step 2 but this time instead of the top 10 countries consider all countries from the region Africa.
**H.Histogram of Job Satisfaction**
**I.Pairwise Scatter plots:**
Obtain scatter plots of the Happiness Score versus each of the other variables.
**J.Heatmap:**


