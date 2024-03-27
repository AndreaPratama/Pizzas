# Pizzas Order Analyze

![](pizza_hero.jpg)

## Introduction
This project involves the analysis of pizza orders to derive valuable insights into order patterns, peak hours, pizza popularity, revenue distribution, and pricing trends.

## Problem Statement
Understanding customer behavior, order trends, and revenue distribution can help optimize business strategies, improve customer satisfaction, and enhance overall operational efficiency.

## Skill Demonstrated
The following Python skills were demonstrated in this project:
- Data Cleaning and Transformation using Pandas
- Exploratory Data Analysis (EDA) with Pandas, and Matplotlib
- Data Visualization using Matplotlib and Seaborn
- Time Series Analysis and Date/Time Manipulation
- Statistical Analysis for Descriptive Insights
- Utilized Python for end-to-end project development

## Data Sourcing
This dataset was obtained from Refocus.

The dataset used in this project includes three main tables:
1. **Orders**: Contains information about order dates, times, and IDs.
2. **Order Details**: Includes order details such as pizza types, quantities, and associated order IDs.
3. **Pizzas**: Provides information on pizza types, sizes, and prices.

## Data Transformation
- Converted date and time columns to datetime format.
- Created additional columns for month, day, and hour.
- Calculated the duration of each order.
- Grouped data for meaningful insights.

## Modeling
No specific machine learning models were utilized in this project. The analysis focused on descriptive statistics and visualizations.

## Analyze & Visualization
### Import Libraries & Read Data

| Code in Python                                                                 | Result                                                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ![](libraries_read_data.png)                 | ![](read_data_py.png)                                                               |

### Order Analysis by Month
- Explored the number of orders received each month.
- Identified the month with the highest sales.

| Code in Python                                                                 | Result                                                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ![](order_month.png)                 | ![](result_1.png)                                                               |

### Peak Hours Analysis
- Analyzed the busiest hours (peak hours) for order placements.

| Code in Python                                                                 | Result                                                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ![](peak_hours.png)                 | ![](result_2.png)                                                               |

### Pizza Popularity Analysis
- Determined the most frequently ordered pizzas.
- Visualized the order quantity for each pizza type using a bar plot.

| Code in Python                                                                 | Result                                                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ![](qty_pizza.png)                 | ![](result_3.png)                                                               |

### Percentage Contribution of Each Pizza Size
- Analyzed the contribution percentage of each pizza size to the overall revenue.
- Illustrated the findings using a pie chart.

| Code in Python                                                                 | Result                                                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ![](percent_contribution.png)                 | ![](result_4.png)                                                               |

### Percentage Revenue Contribution Analysis
- Investigated the revenue contribution for each pizza size.
- Examined the revenue contribution for each pizza type.
- Presented the findings using bar plots.


| Code in Python                                                                 | Result                                                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ![](revenue_percentage.png)                 | ![](result_5.png)                                                               |

### Daily Trend Analysis
- Analyzed the trend in daily order quantities over time.

| Code in Python                                                                 | Result                                                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ![](daily_weekend_trend.png)                 | ![](result_6.png)                                                               |

### Weekly Trend Analysis
- Examined any weekly patterns or trends.

| Code in Python                                                                 | Result                                                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ![](daily_weekend_trend.png)                 | ![](result_7.png)                                                               |

### Pizza Price Variation Analysis
- Explored the variation in pizza prices.
- Assessed the average price for each pizza type.

| Code in Python                                                                 | Result                                                                                                      |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ![](price.png)                 | ![](result_8.png)                                                               |


![](PizzaPy.png) 

### You can interact with Report Here _[Google Colab](https://colab.research.google.com/drive/1ra4nMiDXqgIbYuVeQd2kDSXR8dIDR2CF?usp=sharing)_

## Conclusion & Recommendation
The analysis provides valuable insights into order patterns, peak hours, popular pizzas, revenue distribution, and pricing trends. Recommendations for business optimization can be derived from these findings.
