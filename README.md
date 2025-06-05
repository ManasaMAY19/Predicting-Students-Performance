# Predicting-Students-Performance

## Analysis Description

This analysis investigates factors affecting student performance and builds a model to predict math scores:

### Data Exploration
- The dataset contains student demographic information and test scores in math, reading, and writing
- We check for missing values and basic statistics to understand the data distribution

### Key Findings
1. **Score Distributions**: Visualizing the distribution of math, reading, and writing scores helps identify patterns and outliers
2. **Gender Differences**: Analysis of scores by gender reveals potential performance gaps
3. **Parental Education Impact**: Examining how parental education level correlates with student performance
4. **Test Preparation**: Comparing scores between students who completed test preparation and those who didn't
5. **Socioeconomic Factors**: Analyzing how lunch type (standard vs. free/reduced) relates to academic performance
6. **Ethnic/Racial Differences**: Investigating performance variations across different racial/ethnic groups

### Predictive Modeling
- We built two models to predict math scores:
  1. **Linear Regression**: A baseline model that captures linear relationships
  2. **Random Forest Regressor**: A more complex model that can capture non-linear relationships

- The models are evaluated using:
  - Mean Squared Error (MSE): Measures prediction accuracy
  - R² Score: Indicates how much variance in math scores is explained by the model

- Feature importance analysis from the Random Forest model reveals which factors most strongly predict math scores

This comprehensive analysis provides insights into educational performance factors and delivers a predictive model that could help identify students who might need additional support in mathematics.

#OUTPUT
