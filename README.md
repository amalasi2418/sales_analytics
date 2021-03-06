# Sales analytics

*Sales analytics is used in identifying, modeling, understanding and predicting sales trends and outcomes while aiding sales management in understanding where salespeople can improve. ~ Gartner.com*

## Motivation

The idea of working on this project is to getting familiar with how sales data looks like and what key insights can be deduced from simple analysis.

The project is inspired from the YouTube tutorial by Keith Galli conducted using Python.

## Objectives

The data is for 12 months of sales for an electronic shop.

Analyze the monthly sales data for an year and identify:

1. The month with most sales
2. The best selling product - overall and monthly
3. Time (month of the year, day of the week, hour of the day) when sales peaked and the corresponding products
4. State that contributed to the maximum revenue
5. Contributions of the different cities
6. Number of unique invoices
7. Possible time frames for promotions
8. Explore customer buying patterns

## Key learnings

After conducting the EDA, one gets familiar with the following topics:

1. Reading and concatenating csv files
2. Working with dates
3. Augmenting data
4. Text analysis
5. Filtering data
6. Visualizing data with ggplot2

## Key conclusions

1. Monthly sales are maximum during the month of December.
2. The average spending pattern of the customer during the month is constant and the spending amount starts to decrease at the end of the month.
3. The average spending patter during the week is constant.
4. During the day, the maximum sales occur either between 10 am to 2 pm or 5 to 9 pm.
5. The ideal time for promotion during the day is when the sales are maximum (refer point 4).
6. The overall best selling product is Macbook Pro. Also it is the best seller in each month.
7. California was the leading revenue generator with San Francisco topping in the cities.
8. Further analysis showed interesting insights on customer behavior pattern. More than 1000 customers who bought iPhone also bought lightening charging cable.

## Data

The sales data is from this [Github repo](https://github.com/KeithGalli/Pandas-Data-Science-Tasks).

## References

1. https://www.youtube.com/watch?v=eMOA1pPVUc4
2. https://www.tidyverse.org/
