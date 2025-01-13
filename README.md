## Happiness Index 2024: Exploratory Data Analysis (EDA)

**Project Overview**

This project explores the 2024 Happiness Index dataset to uncover insights into the factors contributing to the happiness levels of countries worldwide. The analysis provides a structured and comprehensive approach to understand the key factors affecting happiness and their relationships using statistical methods, data visualizations, and hypothesis testing.

**Dataset Description**

The dataset used for this project is the 2024 Happiness Index dataset, sourced from Kaggle. It contains country-wise happiness scores and various contributing factors.

**Dataset Features:**
	•	Happiness Score: Target variable, representing the overall happiness level of a country.
	•	Log GDP per capita: Economic performance of the country.
	•	Social Support: Extent of social connections and relationships.
	•	Healthy Life Expectancy: Health and longevity in each country.
	•	Freedom to Make Life Choices: Freedom to live as individuals choose.
	•	Generosity: The tendency to give and help others.
	•	Perceptions of Corruption: Level of corruption perceived by citizens.
	•	Dystopia + Residual: A baseline value that adjusts all scores.

**Steps Followed in the Analysis**

1. Project Introduction and Objectives
	•	Goal: To analyze the dataset, uncover patterns, and identify key factors influencing the happiness score.
	•	Objectives:
	•	Understand the contribution of different features to happiness.
	•	Perform statistical and exploratory analysis.
	•	Provide actionable insights based on the analysis.

2. Data Cleaning
	•	Handled Missing Values:
	•	Identified and imputed missing values using appropriate techniques.
	•	Outlier Detection:
	•	Used box plots and z-scores to identify outliers and either removed or transformed them.
	•	Data Transformation and Normalization:
	•	Applied scaling to ensure uniformity across features with varying scales.

3. Exploratory Data Analysis (EDA)
	•	Summary Statistics:
	•	Calculated measures of central tendency (mean, median, mode) and dispersion (range, variance, standard deviation).
	•	Visualizations:
	•	Created histograms, scatter plots, and box plots to analyze distributions and relationships.
	•	Patterns and Insights:
	•	Discovered correlations between features like Log GDP per capita, Social Support, and Healthy Life Expectancy with the happiness score.
	•	Correlation and Covariance Analysis:
	•	Explored relationships between features using a heatmap and covariance matrix.
	•	Feature Selection:
	•	Identified key features influencing happiness score:
	•	Log GDP per capita
	•	Social Support
	•	Healthy Life Expectancy

4. Statistical Analysis
	•	Descriptive Statistics:
	•	Summarized feature distributions using mean, variance, and standard deviation.
	•	Inferential Statistics:
	•	T-Test: Conducted a t-test to evaluate the difference in happiness scores between developed and developing countries.
	•	Chi-Square Test: Tested the relationship between categorical variables like regions and happiness score.
	•	ANOVA: Performed ANOVA to analyze the variance of happiness scores across groups of countries with different corruption levels.

5. Key Insights
	•	Countries with higher GDP per capita, better social support systems, and higher life expectancy tend to have higher happiness scores.
	•	Perceptions of corruption negatively impact happiness, with high corruption levels correlating to lower scores.
	•	Freedom to make life choices significantly impacts overall happiness, indicating the importance of personal autonomy.

6. Conclusion

The 2024 Happiness Index dataset reveals that economic, social, and health-related factors are the most critical in determining happiness. The findings emphasize the importance of sustainable development, governance, and healthcare systems in improving global happiness levels.

Technologies Used
	•	Python Libraries:
	•	Pandas, NumPy: Data manipulation and cleaning.
	•	Matplotlib, Seaborn: Data visualization.
	•	Scipy, Statsmodels: Statistical analysis.

