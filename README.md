# 🏥 Healthcare Analytics for Doctor Visits

## 📌 Project Overview

**Healthcare Analytics for Doctor Visits** is a data analytics project that explores patient healthcare and doctor-visit data using Python. The project focuses on understanding patterns related to **doctor visits, illness, gender, income, reduced activity, and health insurance coverage**.

The dataset is analyzed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. Different statistical analyses and visualizations are used to identify trends and relationships within the healthcare data.

---

## 🎯 Problem Statement

Healthcare datasets contain valuable information about patients, their health conditions, socioeconomic status, insurance coverage, and healthcare utilization. However, raw data can be difficult to understand without proper analysis.

The objective of this project is to:

* Analyze patient healthcare data.
* Understand the distribution of illness among patients.
* Compare healthcare-related activity between male and female patients.
* Study the relationship between income and doctor visits.
* Analyze government and private health insurance coverage.
* Identify patterns in reduced activity among different genders.
* Visualize relationships between numerical healthcare variables.
* Check the dataset for missing values and understand its structure.

---

## 📝 Project Description

This project performs **Exploratory Data Analysis (EDA)** on a healthcare dataset related to doctor visits.

The analysis starts by loading and inspecting the dataset, followed by checking data types, categorical distributions, and missing values.

Different analytical techniques and visualizations are then used to study the dataset, including:

1. **Dataset Exploration**

   * Displaying sample records.
   * Checking dataset information and data types.
   * Examining illness and gender distributions.

2. **Income Analysis**

   * Using a box plot to understand income distribution.
   * Examining the relationship between income and number of doctor visits.

3. **Gender-Based Analysis**

   * Comparing reduced activity between male and female patients.
   * Analyzing gender-wise healthcare-related patterns.

4. **Insurance Analysis**

   * Analyzing government health insurance received due to low income.
   * Analyzing private health insurance coverage.
   * Analyzing government insurance related to old age, disability, or veteran status.

5. **Correlation Analysis**

   * Creating a correlation heatmap to understand relationships between numerical variables.

6. **Data Quality Check**

   * Identifying missing values using a heatmap.

The project presents the findings through different charts such as **box plots, scatter plots, histograms, pie charts, bar charts, and correlation heatmaps**.

---

## 🛠️ Technologies Used

| Technology                          | Purpose                                       |
| ----------------------------------- | --------------------------------------------- |
| **Python**                          | Main programming language                     |
| **Pandas**                          | Data loading, cleaning, grouping and analysis |
| **NumPy**                           | Numerical operations                          |
| **Matplotlib**                      | Data visualization                            |
| **Seaborn**                         | Statistical visualization                     |
| **Google Colab / Jupyter Notebook** | Development environment                       |
| **GitHub**                          | Project hosting and version control           |

---

## 📊 Analysis Performed

### 1. Dataset Exploration

The dataset is loaded using Pandas and basic information such as rows, columns, data types, and sample records is examined.

### 2. Illness Distribution

The `illness` column is analyzed to understand the distribution of patients based on illness-related categories.

### 3. Gender Distribution

The number of male and female patients is analyzed using categorical data visualization.

### 4. Income Analysis

A box plot is used to visualize the distribution of patient income and identify the spread of income values.

### 5. Income vs Doctor Visits

A scatter plot is created to examine the relationship between patient income and the number of doctor visits.

### 6. Insurance Coverage

The project analyzes three major insurance-related variables:

* Government health insurance due to low income (`freepoor`)
* Private health insurance (`private`)
* Government insurance due to old age, disability, or veteran status (`freerepat`)

### 7. Reduced Activity by Gender

The `reduced` variable is grouped by gender to compare the total reduced activity between male and female patients.

### 8. Correlation Analysis

A correlation heatmap is generated for numerical variables to identify relationships between different healthcare and socioeconomic factors.

### 9. Missing Value Analysis

A heatmap is used to visually identify missing values in the dataset.

---

## 📈 Visualizations

The project includes:

* 📦 Income Box Plot
* 🔵 Income vs Doctor Visits Scatter Plot
* 📊 Gender Distribution Histogram
* 🥧 Government Health Insurance Pie Chart
* 🥧 Private Health Insurance Pie Chart
* 🥧 Government Insurance Eligibility Pie Chart
* 📊 Reduced Activity by Gender Bar Chart
* 🔥 Numerical Correlation Heatmap
* 🟪 Missing Values Heatmap

---

## 🔍 Key Insights

The analysis helps identify:

* Distribution of patients across illness categories.
* Differences in healthcare-related activity between genders.
* The distribution of patient income.
* The relationship between income and doctor visits.
* The proportion of patients receiving different types of health insurance.
* Relationships between numerical variables in the dataset.
* Presence of missing values in the healthcare dataset.

> **Note:** The project focuses on exploratory data analysis and visualization. It does not provide medical diagnosis, treatment recommendations, or machine-learning-based predictions.

---

## 📁 Project Structure

```text
Healthcare-Analytics-for-Doctor-Visits/
│
├── Healthcare Analytics for Doctor Visits.csv
├── Healthcare_Analytics_for_Doctor_Visits.ipynb
├── README.md
└── images/
    ├── income_boxplot.png
    ├── correlation_heatmap.png
    ├── income_vs_visits.png
    ├── insurance_analysis.png
    └── reduced_activity_gender.png
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Prathmg/Healthcare-Analytics-for-Doctor-Visits.git
```

### 2. Open the notebook

Open:

```text
Healthcare_Analytics_for_Doctor_Visits.ipynb
```

using **Jupyter Notebook** or **Google Colab**.

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 4. Run the notebook

Make sure the CSV dataset is available in the same directory as the notebook and run the cells sequentially.

---

## 🎯 End User / Intended Users

This project can be useful for:

* **Students** learning Python and data analytics
* **Data analytics beginners** practicing Exploratory Data Analysis
* **Healthcare researchers** exploring patient and healthcare utilization data
* **Educators** demonstrating data visualization techniques
* **Analysts** interested in socioeconomic and healthcare-related patterns

---

## 📌 Project Outcome

The project demonstrates how raw healthcare data can be transformed into meaningful visual insights using Python. It provides a practical example of **data cleaning, exploratory analysis, statistical grouping, correlation analysis, and visualization**.

---

## 👨‍💻 Author

**Prathmesh Raghunath Gangode**

M.E. Electrical Engineering | Data Analytics & AI Enthusiast

---

## ⭐ Conclusion

This project demonstrates the application of Python-based data analytics techniques to understand healthcare and doctor-visit data. Through exploratory analysis and visualization, different patterns related to **income, illness, gender, doctor visits, reduced activity, and insurance coverage** can be examined.
