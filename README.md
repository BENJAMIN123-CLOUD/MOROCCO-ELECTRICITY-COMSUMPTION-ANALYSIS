# MOROCCO ELECTRICITY COMSUMPTION ANALYSIS

## Introduction

### Brief Overview of the Project's Objective
This project aims to analyze electricity consumption patterns in Morocco. By understanding these patterns, we can enhance energy management, optimize resource allocation, and contribute to the sustainability and efficiency of the electrical grid.

### Data Source
The data for this analysis was sourced from [Maven Analytic](https://app.mavenanalytics.io/datasets). A reputable provider of high-quality datasets for business intelligence and data analysis. The dataset includes detailed measurements that are critical for understanding the impact of environmental factors on electricity consumption. 

### Importance of Understanding Electricity Consumption Patterns in Morocco
Understanding electricity consumption patterns is critical for several reasons:
- **Resource Optimization**: Helps in planning and distributing energy resources more effectively.
- **Demand Forecasting**: Aids in predicting future energy needs, allowing for better preparedness.
- **Cost Efficiency**: Reduces costs associated with overproduction or underproduction of electricity.
- **Sustainability**: Supports efforts to minimize environmental impacts by aligning consumption with renewable energy production.

### Data Description
The data used in this analysis consists of electricity consumption measurements from Morocco, recorded at 10-minute intervals across three distinct zones. The dataset includes environmental factors such as temperature, humidity, and wind speed. The data spans a significant period, providing granular insights necessary for detailed analysis.

### Methodology Overview
The analysis was conducted using a combination of SQL, Excel, and Power BI. These tools facilitated data extraction, transformation, and visualization to uncover meaningful patterns and insights.
1. **SQL**: Used for data querying, cleaning, and aggregation.
2. **Excel**: Utilized for initial data exploration, statistical analysis, and creating preliminary visualizations.
3. **Power BI**: Employed for advanced data visualization, dashboard creation, and interactive reporting.

By leveraging these tools, we can effectively analyze and visualize the electricity consumption patterns in Morocco, providing valuable insights for energy management and planning.

### Data Preparation and Exploration
#### Data Cleaning and Preprocessing
The initial step in our analysis involves cleaning and preprocessing the data to ensure its quality and reliability. This process includes:
1. **Handling Missing Values**: Identifying and imputing or removing missing data points to maintain data integrity.
2. **Outlier Detection**: Identifying and addressing outliers that could skew the analysis.
3. **Inconsistencies Resolution**: Correcting any inconsistencies in the data, such as incorrect timestamps or erroneous readings.

#### Data Transformation
To facilitate the analysis, we created several derived variables:
1. **Time of Day**: Categorizing consumption data into specific hours to analyze diurnal patterns.
2. **Day of Week**: Segmenting data by the day of the week to capture weekly trends.
3. **Month**: Classifying data by month to identify seasonal variations.

#### Exploratory Data Analysis (EDA)
Exploratory Data Analysis was conducted to gain a preliminary understanding of the dataset. This included:

1. **Descriptive Statistics**: Calculating mean, median, standard deviation, and other summary statistics.
2. **Visualizations**: Creating histograms, box plots, and time series plots to visually inspect data distributions and trends.

### Seasonal Patterns in Electricity Consumption

#### Hourly Patterns
**Average Hourly Consumption by Season**: Analyzed to understand how consumption varies throughout the day in different seasons.

#### Weekly Patterns
1. **Average Daily Consumption by Day of Week and Season**: Investigated to reveal how daily consumption differs across weekdays and weekends, and how these patterns shift with the seasons.
2. **Load Profiles for Weekdays and Weekends**: Developed to compare consumption behaviors between weekdays and weekends.

#### Annual Patterns
1. **Monthly Consumption Patterns**: Explored to identify trends and anomalies in monthly energy use.
2. **Year-Over-Year Comparisons**: Conducted to detect long-term changes and trends in electricity consumption.

