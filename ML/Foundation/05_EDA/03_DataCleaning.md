# Data Cleaning

1. `Handle Missing Values`
 - Check which columns have missing values(nulls).


 ### Strategies to handle : 
   -  Drop missing rows/column(only if very few).
       - Impute with : 
             - Mean/Median -> for numerical data.
             - Mode -> for categorical data.
             - Advanced : Linear Regression,KNN ,or interpolation(for future learning).

2. `Remove Duplicates`
    - Detect and drop exact duplicates rows 
     
3. `Fix Data Types`
  - convert wrong types (eg numbers stored as strings ,dates as text)

4. `handling inconsistent categories`
  - clean up categorical values like :
      - Male , MALE, nake ->  should all become male

5. `detecting and handle outliers`
   - use boxplots , iqr, or z-score
   - handle by : 
        - removing (if clearly wrong)
        -  capping (e.g to 95th percentile)
6.  `Fixing Logic or Domain errors`
     - age can't be -5


### summary :
  -  EDA tells you whats wrong . data cleaning fixes it. cleaning is not glamorous , but it's 80 percent of work in real-worl projects