# 🏥 Healthcare Performance Analytics

## Project Overview

Healthcare Performance Analytics is an end-to-end data analytics project built using **SQL Server and Power BI** to analyse hospital operational performance and healthcare outcomes.

The project uses a large **synthetic healthcare dataset** and demonstrates the complete analytics workflow — from data generation, cleaning and modelling in SQL Server to KPI development, interactive dashboarding and statistical analysis in Power BI.

The analysis focuses on key healthcare indicators including:

- Infection Rate
- Readmission Rate
- Mortality Rate
- Hospital Occupancy
- Average Length of Stay
- Department and infection-level performance

> **Note:** This project uses synthetic healthcare data created for portfolio and analytical demonstration purposes. It does not contain real patient information.

---

## 🎯 Project Objectives

The project was designed to answer several healthcare performance questions:

- How does hospital performance vary across key clinical KPIs?
- Which hospitals have comparatively higher infection rates?
- How do infection rates change over time?
- Which departments experience higher infection rates?
- What types of infections are represented in the dataset?
- Is hospital occupancy associated with infection rates?
- Is average length of stay associated with readmission rates?

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| SQL Server | Data storage, transformation and statistical analysis |
| SSMS | Database development and SQL querying |
| Power BI | Data modelling, DAX, visualisation and dashboard development |
| DAX | KPI and analytical measure creation |
| Power Query | Data preparation and transformation |
| Git & GitHub | Version control and project documentation |

---

## 🗄️ Data Preparation & Modelling

The healthcare dataset was prepared and analysed in **SQL Server** before being connected to Power BI.

The project includes:

- Data generation and preparation
- Data quality and validation checks
- Data profiling
- Dimension and fact table modelling
- Healthcare KPI calculations
- Monthly and hospital-level aggregations
- Statistical correlation analysis

The Power BI model uses dimension tables for entities such as hospitals, departments and infection types alongside the clinical fact data.

---

## 📊 Dashboard Structure

### 1. Hospital Overview

Provides an executive-level view of hospital performance through key KPIs:

- **Mortality Rate:** 0.80%
- **Average Occupancy Rate:** 78.42%
- **Readmission Rate:** 3.11%
- **Infection Rate:** 1.13%

The page also compares infection rates across hospitals and examines monthly infection-rate trends.

### 2. Analytical Insights

Provides deeper analysis of hospital performance, including:

- Infection Rate by Department
- Infection distribution by category
- Department-level performance patterns
- Key operational insights

### 3. Occupancy & Infection Analysis

Examines whether higher hospital occupancy is associated with increased infection rates.

**Statistical Results**

- Pearson correlation (r): **0.908**
- Sample size (n): **840**
- p-value: **< 0.001**
- Interpretation: **Very strong positive correlation**

Higher monthly hospital occupancy was strongly associated with higher infection rates in the synthetic dataset.

### 4. Length of Stay & Readmission Analysis

Examines whether average length of stay is associated with hospital readmission rates.

**Statistical Results**

- Pearson correlation (r): **0.008**
- Sample size (n): **840**
- p-value: **0.811**
- Interpretation: **No meaningful linear correlation**

Average length of stay showed virtually no linear association with readmission rates in the dataset.

---

## 📈 Key Analytical Findings

### Hospital Occupancy & Infection Risk

A very strong positive association was observed between average monthly hospital occupancy and infection rate (**r = 0.908, p < 0.001**).

This suggests that periods of higher hospital utilisation are also associated with higher infection rates in the synthetic dataset.

### Length of Stay & Readmissions

Average length of stay showed almost no linear relationship with readmission rate (**r = 0.008, p = 0.811**).

This indicates that length of stay alone does not appear to be a useful indicator of readmission performance in this dataset.

### Department-Level Infection Performance

Infection rates varied across departments. **Surgery recorded the highest infection rate at approximately 1.29%**, while Neurology and General Medicine recorded comparatively lower rates at approximately **1.05%**.

This highlights the value of examining hospital performance below the organisation level rather than relying only on overall KPIs.

---

## 📐 Statistical Methodology

Pearson correlation analysis was used to evaluate linear relationships between selected hospital performance indicators.

Two relationships were investigated:

| Analysis | Pearson r | p-value | Interpretation |
|---|---:|---:|---|
| Occupancy Rate vs Infection Rate | 0.908 | < 0.001 | Very strong positive correlation |
| Average Length of Stay vs Readmission Rate | 0.008 | 0.811 | No meaningful linear correlation |

Correlation represents **association rather than causation**.

---

## 💡 Business Implications

The analysis demonstrates that different operational measures provide different levels of insight into healthcare outcomes.

Higher occupancy was strongly associated with infection rates, suggesting that infection performance deserves particular attention during periods of high hospital utilisation.

In contrast, average length of stay alone did not explain differences in readmission rates, indicating that additional clinical and operational factors would need to be considered when investigating readmission performance.

---

## 🖼️ Dashboard Preview

Add screenshots of the Power BI dashboard here.

Suggested screenshots:

1. Hospital Overview
2. Analytical Insights
3. Occupancy vs Infection Analysis
4. Length of Stay vs Readmission Analysis

---

## 🚀 Skills Demonstrated

- SQL querying and data transformation
- Data profiling and validation
- Dimensional data modelling
- Power BI dashboard development
- DAX measure development
- KPI design
- Data visualisation
- Statistical analysis
- Pearson correlation analysis
- Healthcare data interpretation
- Business insight generation
- Git and GitHub version control

---

## ⚠️ Disclaimer

This project uses **synthetically generated healthcare data** for educational and portfolio purposes.

The findings should therefore be interpreted as demonstrations of analytical techniques and should not be used to make real-world clinical or healthcare decisions.

---

## 👤 Author

**Khushveer Singh**

Master of Data Science, Monash University

Data Analytics | Data Engineering | Power BI | SQL | Python
