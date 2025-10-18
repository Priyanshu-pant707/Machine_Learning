# Data Preprocessing

- To prepare clean data so it can be analyzed or used in a machine learning model.
- if Data Cleaning is about fixing mistakes, Data preprocessing is about transforming valid data into a usable format


1. `Encoding catogorical variables `
 - convert text labels (like 'male','yes') into numbers

  ### Two common method for the encoding categorical  variables :
      1. Label Encoding (ordinal) :
          - good for ordered categories like "low" ,"medium","high".
      2. One-Hot Encoding (Nominal):
          - For non-ordered categories like region

2. `Feature Tranformation `
  - used to handle skewed data , like right-skewed or left-skewed data.


3. `Feature Scaling (Normalizaton or standardization)`
 - bring numerical values to the same scale - expecially useful for distance-based algorithm.
 - Normalization : 
       - min-max scaling
       - scales values between 0 and 1.
 - Standardization : 
    - Transforms data to have mean 0 and std 1.

4. ` `
