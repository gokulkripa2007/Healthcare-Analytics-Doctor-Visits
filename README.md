Healthcare Analytics – Doctor Visits

📌 Project Overview

This project analyzes healthcare data to understand patient doctor-visit patterns. The analysis focuses on gender, illness score, age, and doctor visits using Python-based data analysis and visualization.

🎯 Objectives

Compare doctor visits between male and female patients.

Analyze the relationship between illness score and average doctor visits.

Identify patterns in doctor visits across different illness levels.

Examine doctor visits based on illness, gender, and age.


🛠️ Technologies Used

Python

Pandas – Data analysis and manipulation

Matplotlib – Data visualization

Seaborn – Statistical visualization

Google Colab – Development environment

CSV Dataset – Healthcare data source


📊 Analysis & Visualizations

1. Average Doctor Visits by Gender

The data is grouped by gender to calculate the count, mean, and median of recorded doctor visits.

Graph Title: Average Doctor Visits by Gender

Female – Mean: 0.361954

Male – Mean: 0.236334


2. Illness Score vs. Average Doctor Visits

The data is grouped according to illness score to analyze the average number of recorded doctor visits.

Graph Title: Illness Score vs. Average Doctor Visits

Illness Score	Mean Doctor Visits

0	0.078507
1	0.295482
2	0.403805
3	0.420664
4	0.576642
5	0.813559


3. Doctor Visits by Illness, Gender and Age

A scatter plot is used to visualize doctor visits based on illness score while including gender and age.

X-axis: Illness Score

Y-axis: Doctor Visits

Hue: Gender

Point Size: Age


📈 Key Insights

The average recorded doctor visits differ between female and male groups.

Average doctor visits generally increase with illness score in the analyzed data.

Gender and age provide additional information for understanding doctor-visit patterns.


👥 End Users

Hospitals and Healthcare Organizations

Doctors and Medical Professionals

Healthcare Administrators

Healthcare Analysts and Researchers

Government and Health-Planning Agencies


🚀 How to Run

1. Open the project notebook in Google Colab.


2. Upload the healthcare CSV dataset.


3. Run the data-loading and preprocessing cells.


4. Execute the analysis and visualization cells.


5. View the generated tables and graphs.



📁 Project Structure

Healthcare-Analytics-Doctor-Visits/
│
├── README.md
├── Healthcare_Analytics_Doctor_Visits.ipynb
└── healthcare_doctor_visits.csv

📄 File Description

README.md – Contains the project overview, objectives, technologies, analysis, insights, and conclusion.

Healthcare_Analytics_Doctor_Visits.ipynb – Contains the Python code, data analysis, and visualizations.

healthcare_doctor_visits.csv – Contains the healthcare dataset used for the analysis.


📌 Conclusion

This project demonstrates how healthcare data can be analyzed to understand doctor-visit patterns based on gender, illness score, and age. The analysis uses data processing and visualization techniques to identify relationships and trends in recorded doctor visits, providing meaningful insights into healthcare utilization.
