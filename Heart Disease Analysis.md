Heart Disease Dashboard Analysis

<img width="1329" height="730" alt="image" src="https://github.com/user-attachments/assets/66890373-a4f4-41d5-9910-dda8a13fcda1" />

Heart Disease Analysis Dashboard
This repository features a comprehensive healthcare analytics dashboard built in Microsoft Power BI. It is designed to analyze patient data related to heart failure, providing crucial insights into survival rates, demographic factors, and the impact of various clinical risk factors.

📈 Project Overview
The dashboard serves as a powerful tool for healthcare professionals, researchers, and data analysts to explore the complex factors influencing patient outcomes in heart disease cases. By visualizing key metrics from a clinical dataset, it helps in identifying high-risk patient groups, understanding the correlation between clinical measurements and survival, and assessing the prevalence of comorbidities.

🖼️ Dashboard Showcase
The main dashboard provides a centralized view of all key analytics, from high-level KPIs to detailed breakdowns by age and risk factors.

✨ Key Features & Analysis
Executive KPIs: At-a-glance cards display the most critical metrics:

Survival Rate: The overall percentage of patients who survived.

Average Age: The average age of the patients in the dataset.

Total Survivors & Deaths: Absolute counts for a clear understanding of the cohort size and outcomes.

Clinical Marker Analysis: Interactive combination charts explore the relationship between key clinical readings and survival across different age groups:

Ejection Fraction: Visualizes the average ejection fraction alongside survival counts, a key measure of the heart's pumping efficiency.

Serum Creatinine: Tracks average serum creatinine levels (an indicator of kidney function) against survival counts.

Demographic Segmentation:

Age Group Analysis: Nearly all visuals are segmented by age group, allowing for a deep dive into how risk and survival evolve with age.

Gender Filter: The dashboard can be filtered to show data for Male or Female patients, enabling comparative analysis.

Survival Rate by Age: A dedicated line chart clearly illustrates the trend of survival rates across different age brackets, highlighting a significant decline in older patients.

Comorbidity Impact Analysis: A ribbon chart effectively displays the cumulative impact and prevalence of major risk factors—Smoking, High Blood Pressure, Anaemia, and Diabetes—across age groups.

📊 Data Source
This analysis is based on the publicly available "Heart Failure Prediction" dataset, commonly found on platforms like Kaggle and the UCI Machine Learning Repository. The dataset contains 299 patient records with 13 clinical features, including:

age

anaemia

diabetes

ejection_fraction

high_blood_pressure

serum_creatinine

smoking

DEATH_EVENT (the target variable for survival analysis)

🛠️ Tools and Techniques
Visualization & BI Tool: Microsoft Power BI

Data Analysis Expressions (DAX): Used for creating all calculated measures, such as Survival Rate, Average Age, Total Survivors, etc.

Data Modeling: A logical data model linking patient attributes to their outcomes.

UI/UX Design: A clean, intuitive layout with a thematic color scheme and custom icons for enhanced user experience.
