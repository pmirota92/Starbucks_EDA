# Exploratory Data Analysis (EDA)-in Starbucks (Python)

The purpose of this project is to master the exploratory data analysis (EDA) for Starbucks menu items with Pandas framework.
## Data Source 
https://www.kaggle.com/datasets/henryshan/starbucks

Context:
Starbucks is an American coffee chain founded in Seattle. It serves both beverages and food.

Content:
This dataset includes the nutritional information for Starbucks’ drink menu items. All nutritional information for drinks.
  
## Goals of the Project:

1. Explore a Starbucks’ drink dataset with Pandas framework.
2. Detecting and Removing Missing Values.
3. Investigating and Converting data types.
4. Calculate basic Statistics like mean, median, mode. 
5. Visualize Distributions for the dataset.
6. Checking Outliers with a Boxplot.
7. Calculating the IQR.
8. Investigating Relationships between variables.
9. Drink Composition and Nutritional Analysis.
10. Clustering: KMeans, DBSCAN.

## Results

The analysis of sugar, cholesterol, calories, and caffeine content highlights:
![Starbucks_EDA](Details/chart.PNG)

1. Caffeine Content: Coffees like 'Brewed Coffee' with the highest caffeine are identified, useful for those needing
   an energy boost but should be consumed in moderation by individuals sensitive to caffeine.

2. Diet Considerations: Coffees low in calories like 'Brewed Coffee' or 'Espresso' are recommended for those on a diet,
   while high-calorie options should be avoided.

3. Diabetes Management: Coffees with low sugar content - 'Brewed Coffee' or 'Espresso', and 'Caffee Americano'
   are suitable for people with diabetes, while high-sugar coffees should be avoided to prevent blood sugar spikes.

Clustering:

Unfortunately, both algorithms (DBSCAN and K-Means) did not allow us to effectively classify the coffee types. 
This could be due to the high number of variables used in the classification process. After dimensionality reduction, 
it appears that all points in the reduced two-dimensional space are clustered very close to one another, 
making it difficult for the algorithms to identify distinct groupings.

## USED LIBRARIES:
1. pandas
2. matplotlib
3. seaborn
4. numpy
5. plotly
6. sklearn
