# Employee Churn Prediction – Pilot Program

This project focuses on building a **churn prediction model** to identify employees at risk of leaving the organization. By leveraging **Python (Jupyter Notebook)** for data analysis and modeling, along with **Google Looker Studio** for visualization, the project provides actionable insights to improve **employee retention strategies**.

---

## 📌 Project Overview

Employee churn can significantly affect business continuity and culture. The goal of this pilot program was to:

* **Identify at-risk employees** using predictive modeling.
* **Understand key drivers** behind churn such as satisfaction, tenure, projects, and workload.
* **Support HR decision-making** with data-driven insights.
* **Enhance retention strategies** by addressing systemic issues like job satisfaction and career development.

---

## ⚙️ How the Model Works

A **Random Forest classifier** was trained to predict whether an employee is likely to leave.

Key findings:

* **Job satisfaction** is the most important predictor of churn.
* **Tenure, number of projects, evaluation scores, and working hours** all influence churn likelihood.
* **Work accidents** were found to have minimal impact on retention decisions.

This allows HR teams to **prioritize interventions** such as increasing engagement, balancing workloads, and supporting career growth.

---

## 📊 Supporting Metrics

The model analyzed several features, including:

* `satisfaction_level`
* `time_spend_company`
* `number_project`
* `average_montly_hours`
* `last_evaluation`
* `work_accident`
* `salary`

The output highlights the **relative importance** of each factor in predicting churn.

---

## 🔎 Insights by Department

Visualization dashboards (via Looker Studio) break down **where churn is most prevalent** across departments such as:

* Support
* Technical
* Sales
* Product Management
* Marketing, HR, IT, Accounting, R\&D

👉 **Explore the Interactive Dashboard here:**
[Employee Churn Dashboard – Looker Studio](https://lookerstudio.google.com/reporting/ccd1a1d0-0082-4ebe-b0e5-f26e3d55207e)

---

## 🛠️ Tech Stack

* **Python** (Jupyter Notebook `.ipynb`) – data preprocessing, modeling, and analysis
* **Pandas, NumPy, Scikit-learn** – for data manipulation and machine learning
* **Matplotlib/Seaborn** – exploratory data visualization
* **Google Looker Studio** – interactive dashboards and reporting

---

## 🚀 Getting Started

### Prerequisites

* Python 3.8+
* Jupyter Notebook
* Required libraries:

  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

### Running the Notebook

1. Clone this repository.
2. Open `Pilot_Analysis_Employee_Churn.ipynb` in Jupyter Notebook.
3. Run all cells to reproduce the analysis and churn predictions.

---

## 📈 Results

* Employees with **low satisfaction** are most at risk.
* Moderate workload and tenure correlate with **higher retention**.
* Churn varies across **departments**, requiring tailored HR interventions.

These insights can guide **targeted retention strategies**, reducing turnover and improving employee experience.

---