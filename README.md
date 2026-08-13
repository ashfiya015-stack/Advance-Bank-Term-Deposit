# 📊 Advance Bank Term Deposit — Data Analysis Project

## 📌 Project Overview

This project analyzes bank marketing campaign data to understand **customer behavior and factors influencing term deposit subscription**.

The project uses Python-based **Exploratory Data Analysis (EDA), data visualization, predictive analysis, and interactive dashboard development** to transform raw customer data into meaningful business insights.

The goal is to identify customer patterns and campaign factors that can help improve customer targeting and marketing effectiveness.

---

## 🎯 Business Objective

The main objectives of this project are to:

* Understand customer demographics and subscription behavior.
* Analyze factors associated with term deposit subscription.
* Evaluate different communication methods.
* Study campaign contact frequency and call duration.
* Identify relationships between numerical variables.
* Use predictive analysis to support customer targeting.
* Provide data-driven recommendations for improving marketing campaigns.

---

## 📂 Dataset

The dataset contains customer information and details about interactions during a bank marketing campaign.

### Key Features

| Category          | Features                              |
| ----------------- | ------------------------------------- |
| Customer          | Age, Job, Marital Status, Education   |
| Contact           | Contact Method, Month, Day            |
| Campaign          | Duration, Campaign, Previous Contacts |
| Previous Campaign | Previous Outcome                      |
| Target            | Term Deposit Subscription             |

The target variable indicates whether a customer subscribed to a term deposit:

* `yes` → Subscribed
* `no` → Did not subscribe

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Plotly**
* **Jupyter Notebook**

---

## 🔍 Project Workflow

Dataset
   ↓
Data Loading & Inspection
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Customer Demographics Analysis
   ↓
Balance & Subscription Analysis
   ↓
Campaign Effectiveness Analysis
   ↓
Correlation Analysis
   ↓
Predictive Analysis
   ↓
Model Evaluation
   ↓
Interactive Dashboard
   ↓
Business Insights & Recommendations


## 📊 Exploratory Data Analysis

### 👥 Customer Demographics

The project analyzes:

* Age distribution
* Job distribution
* Customer characteristics
* Subscription behavior across customer groups

### 📊 Subscription Analysis

The analysis examines customer characteristics and subscription behavior to identify patterns associated with term deposit subscription.

### 📞 Campaign Effectiveness

The campaign analysis focuses on:

* Contact method
* Number of contacts
* Call duration
* Previous campaign outcome
* Subscription behavior

### 🔥 Correlation Analysis

A correlation heatmap was created to examine relationships between numerical variables and identify potentially important patterns.

---

## 🤖 Predictive Analysis

Logistic Regression was implemented as a supporting predictive-analysis technique.

### Model Performance

| Metric    |      Score |
| --------- | ---------: |
| Accuracy  | **91.64%** |
| Precision | **71.00%** |
| Recall    | **43.53%** |
| F1 Score  | **53.97%** |
| ROC-AUC   | **94.24%** |

### Interpretation

The model achieved strong overall performance with an ROC-AUC of **94.24%**.

However, the recall of **43.53%** indicates that a significant number of potential subscribers were not identified by the model. Therefore, accuracy alone should not be used to evaluate the model.

Predictive analysis is used as a **supporting component of the Data Analysis project**, rather than as the primary objective.

---

## 📈 Interactive Dashboard

A Plotly-based interactive dashboard was developed to present the major findings in an easy-to-understand format.

### Dashboard KPIs

* **Total Customers:** 41,188
* **Subscribed Customers:** 4,640
* **Subscription Rate:** 11.27%
* **Average Call Duration:** 258.29 seconds

### Dashboard Visualizations

* Subscription rate by job
* Subscription rate by contact method
* Customer age distribution
* Campaign contacts vs subscription
* Key campaign performance indicators

---

## 💡 Key Insights

* Customer demographics show different patterns in term deposit subscription.
* Job categories demonstrate different subscription rates.
* Contact methods can influence campaign effectiveness.
* Campaign contact frequency provides useful information about customer response.
* Call duration can be used as an indicator of customer engagement.
* Predictive analysis can support the identification and prioritization of potential subscribers.

---

## 💼 Business Recommendations

Based on the analysis, the bank can:

1. **Target high-potential customer segments** based on demographic and behavioral patterns.
2. **Prioritize effective communication channels** when planning marketing campaigns.
3. **Optimize contact frequency** to reduce unnecessary customer interactions.
4. **Use customer engagement indicators** such as call duration to improve targeting.
5. **Use predictive scores as a supporting tool** when prioritizing potential customers.
6. Continuously monitor campaign results and refine marketing strategies using data.

---

## 📁 Project Structure


Advance-Bank-Term-Deposit/
│
├── Advance_Bank_Term_Deposit.ipynb
│
├── data/
│   └── data.csv
│
├── dashboard/
│   └── Advance_Bank_Term_Deposit_Dashboard.html
│
├── presentation/
│   └── Advance_Bank_Term_Deposit_Internship_Presentation.pptx
│
├── screenshots/
│   ├── age_distribution.png
│   ├── job_analysis.png
│   ├── contact_analysis.png
│   ├── correlation_heatmap.png
│   ├── model_performance.png
│   └── dashboard.png
│
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

```bash
cd Advance-Bank-Term-Deposit
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Advance_Bank_Term_Deposit.ipynb
```

### 4. View the Dashboard

Open the HTML dashboard located inside:

```text
dashboard/
```

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Customer Analysis
* Campaign Analysis
* Correlation Analysis
* Business Insight Generation
* Python Data Analysis
* Predictive Analysis
* Model Evaluation
* Interactive Dashboard Development
* Business Recommendations
* Data Storytelling

---

## 📌 Project Outcome

This project demonstrates an end-to-end **Data Analysis workflow**, from exploring raw banking data to generating business insights and presenting them through an interactive dashboard.

The combination of **EDA, visualization, predictive analysis, and business recommendations** provides a practical example of how data can support better marketing and customer-targeting decisions.

---

## 👩‍💻 Author

**Ashfiya**

**Data Analytics Enthusiast**

**Skills:** Python • Pandas • SQL • Data Visualization • Exploratory Data Analysis • Machine Learning

---

⭐ If you find this project useful, consider giving the repository a star!
