Heart Disease Dataset Analysis
👀🏠Overview

This project analyzes a heart disease dataset to explore relationships between patient characteristics and heart disease outcomes. The dataset contains information about various health indicators, including cholesterol, age, blood pressure, and heart rate, along with a target variable indicating the presence of heart disease.

🏁Dataset Details

Source: UCI Heart Disease Dataset 
File: heart_disease_uci.csv
Number of records: (920 rows)
Columns:
 -id – Patient identifier
-age – Age of the patient
-sex – Gender of the patient (0 = female, 1 = male)
 -cp – Chest pain type
 -trestbps – Resting blood pressure
 -chol – Serum cholesterol
 -fbs – Fasting blood sugar > 120 mg/dl
 -restecg – Resting electrocardiographic results
 -thalach – Maximum heart rate achieved
 -exang – Exercise-induced angina
 -oldpeak – ST depression induced by exercise
 -slope – Slope of the peak exercise ST segment
 -ca – Number of major vessels colored by fluoroscopy
 -thal – Thalassemia
 -num – Heart disease presence (0 = no disease, 1–4 = disease severity)

🎯Project Goals

1.Data Cleaning: Handle missing values and remove irrelevant columns.
2.Exploratory Data Analysis (EDA):
 -Understand distributions of numerical columns.
 -Explore relationships between features (e.g., age vs cholesterol).
 -Visualize trends using line plots, histograms, and scatter plots.
4.Statistical Analysis: Compute mean, median, and standard deviation of key features.
5.Feature Aggregation: Create age groups to analyze trends in cholesterol and heart rate across age.
6.Visualization: Generate clean and interpretable plots for insights.

🛠Key Analyses Performed

.Missing Value Handling: Replaced missing numerical values with median and categorical values with mode.
.Statistical Summary: Computed mean, median, and standard deviation for numerical columns (chol, thalach, trestbps, etc.).
.Grouped Analysis:
 -Average cholesterol and max heart rate by age groups.
 -Average cholesterol by sex.
.Visualizations:
 -Histograms to explore feature distributions.
 -Scatter plots to examine relationships (e.g., age vs cholesterol).
 -Line plots showing trends per age group.
 -Regression lines and correlation coefficients to quantify relationships.

📩Example Plots

 -Histogram of Cholesterol: Shows distribution across patients.
 -Line Plot by Age Group: Average cholesterol and max heart rate per age range.
-Scatter Plot: Age vs cholesterol for a sample of patients with regression line and correlation.
 -Bar Plot: Average cholesterol by sex.

🔗Tools & Libraries

1.Python 3.x
2.Pandas – Data loading, cleaning, and aggregation
3.Matplotlib – Plotting basic charts
4.Seaborn – Advanced visualizations (scatter plots with hue and regression)

💡Insights

1.Cholesterol and maximum heart rate show trends with age.
2.Heart disease prevalence differs by sex and age group.
3.Correlation analysis indicates moderate relationships between certain features and disease presence.
