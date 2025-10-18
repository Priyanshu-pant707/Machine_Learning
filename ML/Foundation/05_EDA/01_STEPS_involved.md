# EDA

- EDA stands for `Exploratory Data Analysis` - It's the step where you explore the data to :
1. Understand it.
2. Discover the patterns.
3. Spot Anomalies.(anomalies are those which can destroy your model calculation.)
4. Generate insights.
5. And decide what to do next.

---


# EDA steps:

1. `Viewing the Data`
 - head(),tail(),shape,info().
 - What columns do I have? What types of data?

2. `Summary Statistics`
 - mean,median,mode,std,min,max,quartiles
 - Helps understand spread and central Tendency.

3. `Value Counts`
 - How many unique values in a column?
 - Great for categorical columns.

4. `Missing Value Analysis`
 - Where are the gaps?What percent of the data is missing.

5. `Visualizations`
 - Histograms -> distribution of values.
 - Box plots -> outliers and spread.
 - Bar plots -> comparisons of categories.
 - Correlation Heatmaps -> Linear relationships between numerical features.
 - Scatter Plots -> Bivariate relationships

6. `Target Variable Exploration`
 - How does your output (;ike 'charges' in your dataset) related to other variables?
