# CSC108_SleepAnalysis

A data science project analyzing factors that affect sleep duration and quality using lifestyle, health, and behavioral data. Includes exploratory data analysis, visualization, and statistical modeling to identify key factors influencing sleep.

---

## Sleep Duration and Quality Analysis

### Overview
This project explores how different factors affect sleep duration and quality. Using data analysis and statistical techniques, we identify key patterns and determine which variables have the strongest impact on sleep.

---

## Dataset
The dataset includes variables related to:

- Demographics (e.g., gender, age, occupation)
- Lifestyle factors (e.g., physical activity level)
- Health factors (e.g., stress level, sleep disorders)
- Sleep metrics (e.g., sleep duration, quality of sleep)

---

## Target Variable
- **Sleep Duration**
  - Measured in hours

---

## Exploratory Data Analysis
Several visualizations were used to understand relationships between variables:

- Boxplots comparing sleep duration across gender and stress levels
- Scatter plots analyzing relationships between numerical variables
- Count plots examining sleep quality across sleep disorders
- Heatmap to identify correlations between variables

---

## Key Findings
- Gender has little to no significant impact on sleep duration
- Stress level has a strong negative relationship with both sleep duration and sleep quality
- Sleep disorders have a moderate impact on sleep quality
- Physical activity has a small positive effect on sleep duration

---

## Model
A **Linear Regression model** was used to analyze relationships between variables.

### Features Used:
- Stress Level
- Physical Activity Level
- Quality of Sleep
- Age
- Daily Steps

---

## Approach
- Data cleaning (removed duplicates and handled missing values)
- Regression analysis to quantify relationships
- Correlation heatmap to identify strong relationships

---

## Results
- Stress level shows the strongest negative relationship with sleep duration
- Regression confirms that higher stress leads to less sleep
- Physical activity has a smaller positive effect
- Gender is not a strong predictor of sleep duration

---

## Feature Importance
The most influential factors affecting sleep duration were:

- Stress Level (strongest impact)
- Quality of Sleep
- Physical Activity Level

Demographic variables such as gender had minimal influence compared to lifestyle factors.

---

## Conclusion
Sleep is influenced more by lifestyle and health-related factors than by demographic variables. Stress plays the most significant role in determining sleep duration and quality, while other factors such as physical activity and sleep disorders also contribute to overall sleep patterns.

---

## Technologies Used
- Python
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

## Future Improvements
- Analyze interactions between multiple variables simultaneously
- Improve modeling techniques for better prediction
- Explore additional factors such as environmental and behavioral influences
