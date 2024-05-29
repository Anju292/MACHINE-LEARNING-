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

### TASK 4

## REGRESSION

In your project, you applied five regression algorithms to model the price of cars based on various independent variables. These algorithms were Linear Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, and Support Vector Regressor.

Dataset = https://drive.google.com/file/d/1PnOCTPJMP4oaG_1T0iR3qu0DRguhsrWm/view?usp=drive_link

The goal was to identify significant factors influencing car prices in the American market and understand how well these variables describe price variations. By analyzing the dataset, you aimed to provide insights for the Chinese automobile company to make informed decisions regarding their entry into the US market.

- The objective was to determine the influential factors affecting car prices in the American market.
  
- The analysis aimed to understand the effectiveness of these variables in explaining price variations.

- Each algorithm underwent training and evaluation using metrics like Mean Squared Error and R^2 Score.

- Visualizations, including scatter plots of actual vs predicted prices, were utilized for performance assessment.

- The project aimed to furnish insights for a Chinese automobile company venturing into the US market.

- The ultimate goal was to equip the management with a predictive model to grasp pricing dynamics.

- This understanding would facilitate strategic adjustments in business operations and product strategies.

- The end objective was to enable the company to compete effectively with US and European counterparts.

In summary, the project involved applying regression algorithms to discern pricing factors in the American market, aiding the company's market entry strategy by providing actionable insights and predictive capabilities for pricing dynamics.

### TASK 5

## Classification and Clustering: Project Overview

In this project, I utilized the Iris flower dataset from sklearn.datasets to perform both classification and clustering tasks. The dataset contains 150 samples, each with four features: Sepal Length, Sepal Width, Petal Length, and Petal Width. The objective was to classify each flower into one of three categories: Setosa, Versicolour, or Virginica.

1. Classification:
   - **Model Training**: Utilized logistic regression to train a classification model on the Iris dataset. The model was trained using the four features to predict the class labels.
   - **Accuracy Evaluation**: Evaluated the accuracy of the trained model to assess its performance in predicting flower categories.
   - **Prediction**: Used the trained model to predict the class labels for different samples in the test dataset.

2. Clustering:
   - **Feature Selection**: Excluded the target variable (class labels) from the Iris dataset to prepare it for clustering algorithms.
   - **Clustering Algorithms**: Utilized various clustering algorithms such as K-means clustering, Hierarchical clustering, or DBSCAN to cluster the data points based on the four features.
   - **Evaluation**: Evaluated the clustering results to determine how well the algorithms grouped the data points into distinct clusters.

Overall, the project involved utilizing the Iris dataset for both classification and clustering tasks. Through classification, I trained a model to predict flower categories based on the provided features and evaluated its accuracy. In clustering, I applied different algorithms to group the data points into clusters based on similarities in the feature space.








