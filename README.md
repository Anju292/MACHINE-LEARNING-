# MACHINE-LEARNING

### TASK 1
 
## OUTLIER DETECTION AND CORRELATION ANALYSIS
Dataset = https://drive.google.com/file/d/137w_fwScAJtSbteo_HL0BxqhtJ9Gocsr/view?usp=sharing

This project analyzes Bangalore property prices, focusing on price per square foot. Steps include: data loading, outlier detection (mean, percentile, IQR, normal distribution, Z-score), visualization (box plots, histogram), correlation analysis (heatmap, scatter plots), yielding insights like strong correlations between square footage and price.
It includes:

- Data Loading: Load "house_price.csv" with features like square footage, bathrooms, bedrooms, and price.

- Outlier Detection: Use mean, percentile, IQR, normal distribution, and Z-score methods to identify and remove outliers.

- Data Visualization: Utilize box plots and histograms to visualize data spread and assess normality.

- Correlation Analysis: Calculate correlations between features, visualize with a heatmap, and examine scatter plots for linear relationships.

- Insights: Findings include strong correlations between square footage and bathrooms/price, weaker correlations with bedrooms, and moderate positive correlations with other features in price per square foot.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### TASK 2

## HYPOTHESIS TESTING

1. **Objective:**
   - Determine if a claim about a population parameter is supported by sample data.

2. **Null Hypothesis (\( H_0 \)):**
   - Assumption that there is no significant difference or effect.
   
3. **Alternative Hypothesis (\( H_1 \)):**
   - Contrary to the null hypothesis, stating there is a significant difference or effect.

4. **Test Statistic:**
   - A numerical value computed from sample data used to assess the truth of the null hypothesis.

5. **Significance Level (\( \alpha \)):**
   - Threshold for accepting or rejecting the null hypothesis, typically set at 0.05.

6. **Critical Value:**
   - Threshold value beyond which the null hypothesis is rejected.

7. **Decision Rule:**
   - Criteria used to decide whether to reject the null hypothesis based on the test statistic and critical value.

8. **Conclusion:**
   - Final determination based on the decision rule, indicating whether there is enough evidence to support the alternative hypothesis.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Task3 

## DATA PREPROCESSING

**Objective**:
The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning.

Dataset: https://drive.google.com/file/d/1C4Mc-gjGrYLIkKRzM1-VwXII3qU0kVHw/view?usp=drive_link   

### **Key Components**
**Data Exploration**:
Explore the data, list down the unique values in each feature and find its length. Perform the statistical analysis and renaming of the columns.
**Data Cleaning**: 
- Find the missing and inappropriate values, treat them appropriately. Remove all duplicate rows. Find the outliers.
- Replace the value 0 in age as NaN
 Treat the null values in all columns using any measures(removing/ replace the values with mean/median/mode)
**Data Analysis**:
- Filter the data with age >40 and salary<5000
- Plot the chart with age and salary
- Count the number of people from each place and represent it visually
**Data Encoding**:
- Convert categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms.
**Feature Scaling**: 
- After the process of encoding, perform the scaling of the features using standardscaler and minmaxscaler.
