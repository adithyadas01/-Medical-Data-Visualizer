# Medical-Data-Visualizer
This project is part of the freeCodeCamp Data Analysis with Python certification. You will visualize and analyze medical examination data using Pandas, Matplotlib, and Seaborn to explore relationships between various health indicators and cardiovascular disease.

The dataset (medical_examination.csv) contains information about patients’ body measurements, blood test results, and lifestyle choices.

📊 Features & Analysis

Added “overweight” column

Calculated BMI = weight(kg) / (height(m))²

Marked as overweight if BMI > 25

Normalized data

Cholesterol & glucose:

0 = good (normal)

1 = bad (above normal or well above normal)

Categorical Plot

Shows distribution of health indicators (cholesterol, gluc, smoke, alco, active, overweight)

Split by cardiovascular disease (cardio = 0 or 1)

Heatmap

Cleaned dataset to remove outliers and incorrect data

Displayed correlation matrix of medical features

📈 Visualizations
Categorical Plot

Displays the counts of good/bad outcomes for lifestyle and medical features, grouped by cardiovascular condition.

Heatmap

Shows correlations between features after data cleaning, highlighting how body measurements and health indicators relate to heart disease.

Tools & Libraries

Python 🐍

Pandas

Matplotlib

Seaborn

NumPy
