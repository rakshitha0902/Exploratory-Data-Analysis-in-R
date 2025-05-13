📊 Exploratory Data Analysis in R: Diet & Exercise Trends
This repository contains an R-based exploratory data analysis (EDA) project that investigates the relationships between diet types, exercise habits, and health metrics such as BMI, weight, height, and age. The project was conducted in RStudio and includes the R Markdown report, cleaning and visualization code, and the dataset used.

📁 Repository Contents
DemographicHealthDataset.csv – The cleaned dataset containing information on individuals’ diet types, exercise frequency, gender, age, height, and weight.

EDA_Diet_Exercise.Rmd – The R Markdown file used to generate the report.

EDA_Diet_Exercise_Report.docx – A rendered report summarizing key insights, visualizations, and conclusions.

README.md – This file.

📌 Project Overview
The goal of this analysis is to understand how different diets (e.g., Vegan, Keto, Paleo) and exercise types (e.g., Cardio, Yoga, Strength training) impact health indicators like BMI, and how these factors vary across age groups and gender.

🛠️ Key Steps Performed
Data Cleaning: Standardization of diet_type, exercise_type, gender, and imputation of missing values.

Feature Engineering: Creation of BMI and categorization into Low/Medium/High percentiles; grouping age into categories.

Visualizations: Bar charts, pie charts, boxplots, heatmaps, and correlation matrices to explore trends and patterns.

📈 Main Insights
Yoga and Cardio were the most common forms of exercise.

Adults had the highest BMI on average, especially those following non-plant-based diets.

Plant-based diets were more associated with moderate BMI levels.

Gender and age influence exercise frequency and BMI trends significantly.

🧰 Tools Used
R (Tidyverse, ggplot2, dplyr, psych, skimr)

RStudio for report generation and visualization

Markdown for documentation and reproducibility

📑 How to Run
Open the EDA_Diet_Exercise.Rmd file in RStudio.

Knit the document to generate the report.

View the interactive charts and statistical summaries.

