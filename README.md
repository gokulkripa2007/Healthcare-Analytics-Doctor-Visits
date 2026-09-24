#  Healthcare Analytics – Doctor Visits

##  Project Overview

**Healthcare Analytics – Doctor Visits** is a Python-based data analysis project that explores patterns in healthcare utilization by analyzing patient doctor-visit data.

The project examines how **gender, illness score, and age** are associated with the number of recorded doctor visits. Using data analysis and visualization techniques, the project identifies trends and patterns that can help provide a better understanding of patient healthcare utilization.

---

##  Objectives

The main objectives of this project are:

* Compare the average number of doctor visits between **male and female patients**.
* Analyze the relationship between **illness score and doctor visits**.
* Identify patterns in doctor visits across different **illness-score levels**.
* Examine doctor visits using multiple factors, including **illness score, gender, and age**.
* Present the findings through clear and informative **data visualizations**.

---

##  Technologies Used

| Technology       | Purpose                                      |
| ---------------- | -------------------------------------------- |
| **Python**       | Data analysis and programming                |
| **Pandas**       | Data cleaning, manipulation, and aggregation |
| **Matplotlib**   | Data visualization                           |
| **Seaborn**      | Statistical visualization                    |
| **Google Colab** | Development and execution environment        |
| **CSV**          | Healthcare dataset format                    |

---

##  Data Analysis & Visualizations

### 1. Average Doctor Visits by Gender

The dataset is grouped by gender to calculate statistics such as the number of records, mean doctor visits, and median doctor visits.

**Visualization:** Average Doctor Visits by Gender

| Gender | Mean Doctor Visits |
| ------ | -----------------: |
| Female |       **0.361954** |
| Male   |       **0.236334** |

The analysis shows a difference in the average number of recorded doctor visits between the two gender groups in this dataset.

---

### 2. Illness Score vs. Average Doctor Visits

The data is grouped according to **illness score** to determine the average number of recorded doctor visits at each illness level.

**Visualization:** Illness Score vs. Average Doctor Visits

| Illness Score | Mean Doctor Visits |
| ------------: | -----------------: |
|             0 |           0.078507 |
|             1 |           0.295482 |
|             2 |           0.403805 |
|             3 |           0.420664 |
|             4 |           0.576642 |
|             5 |           0.813559 |

The results show that the average recorded doctor visits generally increase as the illness score increases within the analyzed dataset.

---

### 3. Doctor Visits by Illness, Gender, and Age

A scatter plot is used to examine doctor visits across illness scores while incorporating gender and age.

**Plot Configuration:**

* **X-axis:** Illness Score
* **Y-axis:** Doctor Visits
* **Hue:** Gender
* **Point Size:** Age

This visualization allows multiple patient characteristics to be examined simultaneously and helps identify patterns that may not be visible when analyzing individual variables separately.

---

##  Key Insights

Based on the analysis:

* The average number of recorded doctor visits differs between **female and male patients**.
* Doctor visits generally increase with increasing **illness score**.
* Patients with higher illness scores show higher average recorded doctor visits in the analyzed dataset.
* **Gender and age** provide additional dimensions for understanding doctor-visit patterns.
* Combining multiple variables through visualization helps reveal relationships between patient characteristics and healthcare utilization.

> **Note:** These findings describe patterns in the analyzed dataset and should not be interpreted as evidence of causation or as general conclusions about all patients.

---

##  Potential End Users

The analysis can be useful for:

*  **Hospitals and Healthcare Organizations**
*  **Doctors and Medical Professionals**
*  **Healthcare Administrators**
*  **Healthcare Analysts and Researchers**
*  **Government and Health-Planning Agencies**

These stakeholders can use similar analytics approaches to explore healthcare utilization patterns and support data-driven planning.

---

##  How to Run the Project

### Step 1 – Open Google Colab

Open the project notebook in **Google Colab**.

### Step 2 – Upload the Dataset

Upload the following CSV file:

`healthcare_doctor_visits.csv`

### Step 3 – Load and Preprocess the Data

Run the data-loading and preprocessing cells in the notebook.

### Step 4 – Perform the Analysis

Execute the Python analysis cells to calculate:

* Gender-based doctor-visit statistics
* Illness-score averages
* Other relevant statistical measures

### Step 5 – Generate Visualizations

Run the visualization cells to generate the graphs and scatter plots.

### Step 6 – Analyze the Results

Review the generated tables and visualizations to understand the observed doctor-visit patterns.

---

##  Project Structure

```text
Healthcare-Analytics-Doctor-Visits/
│
├── README.md
├── Healthcare_Analytics_Doctor_Visits.ipynb
└── healthcare_doctor_visits.csv
```

---

##  File Description

### `README.md`

Contains the project overview, objectives, technologies, analysis, findings, and conclusion.

### `Healthcare_Analytics_Doctor_Visits.ipynb`

Contains the complete Python workflow, including:

* Data loading
* Data preprocessing
* Statistical analysis
* Data grouping
* Visualizations
* Interpretation of results

### `healthcare_doctor_visits.csv`

Contains the healthcare dataset used for the analysis.

---

##  Project Workflow

```text
Healthcare CSV Dataset
        ↓
Data Loading
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Statistical Analysis
        ↓
Data Visualization
        ↓
Identify Patterns
        ↓
Interpret Results
```

---

##  Conclusion

This project demonstrates how **Python-based healthcare analytics** can be used to explore doctor-visit patterns across different patient characteristics.

The analysis focuses on **gender, illness score, and age** to identify relationships within the recorded doctor-visit data. The results indicate differences in doctor visits between gender groups and a general increase in average doctor visits as illness score increases.

By combining **Pandas, Matplotlib, and Seaborn**, the project demonstrates a practical workflow for transforming raw healthcare data into meaningful tables and visualizations.

Overall, the project provides a foundation for further healthcare analytics, including more advanced statistical analysis, predictive modeling, and interactive dashboards.
