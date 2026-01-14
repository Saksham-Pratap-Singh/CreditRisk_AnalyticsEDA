# 🎯 Credit Risk Analytics - Exploratory Data Analysis

Comprehensive EDA project analyzing credit risk patterns to predict loan default probability using real-world financial data. This project demonstrates advanced data analysis techniques, feature engineering, and statistical insights for credit risk assessment.

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Problem Statement](#-problem-statement)
- [Dataset Information](#-dataset-information)
- [Key Features](#-key-features)
- [EDA Workflow](#-eda-workflow)
- [Tech Stack](#-tech-stack)
- [Installation & Usage](#-installation--usage)
- [Project Structure](#-project-structure)
- [Key Insights](#-key-insights)
- [Skills Demonstrated](#-skills-demonstrated)
- [Author](#-author)

---

## 🎯 Project Overview

Credit risk analysis is crucial for financial institutions to minimize loan defaults and optimize lending decisions. This project performs extensive exploratory data analysis on loan application data to identify risk patterns, understand customer behavior, and derive actionable insights for credit decisioning.
The analysis focuses on identifying clients with payment difficulties (TARGET = 1) versus those who repay on time (TARGET = 0) using 120+ features including demographic, financial, credit bureau, and housing information.

---

## 🔍 Problem Statement

**Objective**: Analyze loan application data to uncover patterns and factors that distinguish defaulters from non-defaulters, enabling data-driven credit risk assessment.

**Business Goal**: Help lending institutions:
- Identify high-risk applicants before loan approval
- Optimize lending criteria based on data insights
- Reduce default rates while maximizing loan approvals for creditworthy customers
- Understand demographic and financial patterns influencing repayment behavior

---

## 📊 Dataset Information

### Dataset Statistics
- **Total Features**: 122 columns
- **Target Variable**: Binary classification (0 = No payment difficulty, 1 = Payment difficulty)
- **Data Types**: Numerical, Categorical, and Binary features
- **Key Feature Categories**:
  - Demographic information (age, gender, family status, education)
  - Financial data (income, credit amount, annuity, goods price)
  - Employment details (occupation, employment duration, organization type)
  - Credit bureau inquiries (hour/day/week/month/quarter/year)
  - Housing information (building attributes with AVG/MODE/MEDI aggregations)
  - External credit scores (EXT_SOURCE_1, EXT_SOURCE_2, EXT_SOURCE_3)
  - Document submission flags (21 different documents)
  - Contact information flags (mobile, work phone, email)

### Sample Features
| Feature | Description |
|---------|-------------|
| `TARGET` | Payment difficulty indicator (0=No, 1=Yes) |
| `AMT_INCOME_TOTAL` | Client's total income |
| `AMT_CREDIT` | Credit amount of the loan |
| `AMT_ANNUITY` | Loan annuity payment |
| `DAYS_BIRTH` | Client's age in days (negative value) |
| `DAYS_EMPLOYED` | Employment duration in days (negative value) |
| `CODE_GENDER` | Gender (M/F) |
| `NAME_EDUCATION_TYPE` | Highest education level |
| `NAME_INCOME_TYPE` | Income source type |
| `EXT_SOURCE_1/2/3` | Normalized external credit scores |

---

## ✨ Key Features

### Data Analysis Techniques
- **Univariate Analysis**: Distribution analysis of individual features
- **Bivariate Analysis**: Relationship between features and target variable
- **Multivariate Analysis**: Correlation analysis and feature interactions
- **Missing Value Analysis**: Comprehensive null value detection and handling strategies
- **Outlier Detection**: Statistical identification of anomalies
- **Feature Engineering**: Derived features for enhanced insights

### Visualizations
- Distribution plots (Histograms, KDE plots)
- Box plots for outlier detection
- Correlation heatmaps
- Count plots for categorical analysis
- Scatter plots for feature relationships
- Bar charts for comparative analysis

---

## 🔄 EDA Workflow

```
1. Data Loading & Initial Exploration
   ↓
2. Data Quality Assessment
   ↓
3. Missing Value Analysis & Treatment
   ↓
4. Univariate Analysis (Individual Feature Distributions)
   ↓
5. Bivariate Analysis (Feature vs Target)
   ↓
6. Multivariate Analysis (Feature Correlations)
   ↓
7. Outlier Detection & Analysis
   ↓
8. Feature Engineering & Transformation
   ↓
9. Statistical Testing & Hypothesis Validation
   ↓
10. Business Insights & Recommendations
```

---

## 🛠️ Tech Stack

**Language**: Python 3.x  
**Libraries**:
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Statistical Analysis**: SciPy, Statsmodels
- **Environment**: Jupyter Notebook

---

### Setup Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/Saksham-Pratap-Singh/CreditRisk_AnalyticsEDA.git
cd CreditRisk_AnalyticsEDA
```

2. **Install Dependencies**
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook Credit_Risk_EDA.ipynb
```


## 📁 Project Structure

```
CreditRisk_AnalyticsEDA/
│
├── Credit_Risk_EDA.ipynb              # Main analysis notebook with complete EDA
├── Dataset_Preview.csv                # Sample dataset for preview
├── columns_description.csv            # Feature definitions and descriptions
├── Insights and Conclusion.pdf        # Executive summary of findings
└── README.md                          # Project documentation
```

---

## 💡 Key Insights

### Demographic Patterns
- Age distribution analysis reveals risk patterns across age groups
- Gender-based credit behavior differences
- Education level correlation with repayment capability
- Family status impact on loan default rates

### Financial Indicators
- Income-to-credit ratio as a strong predictor
- Annuity payment patterns across defaulters vs non-defaulters
- External credit scores (EXT_SOURCE) show significant predictive power
- Credit bureau inquiry frequency patterns

### Employment Insights
- Occupation types with higher/lower default rates
- Employment duration correlation with creditworthiness
- Organization type influence on repayment behavior

### Risk Factors Identified
- High credit-to-income ratios
- Frequent credit bureau inquiries
- Certain occupation and income type combinations
- Low external credit scores
- Specific demographic segments

---

## 🎓 Skills Demonstrated

### Technical Skills
✅ **Python Programming**: Advanced data manipulation with Pandas  
✅ **Data Visualization**: Professional charts using Matplotlib/Seaborn  
✅ **Statistical Analysis**: Hypothesis testing, correlation analysis  
✅ **Feature Engineering**: Creating derived features for better insights  
✅ **Data Cleaning**: Handling missing values, outliers, duplicates  

### Domain Knowledge
✅ **Credit Risk Assessment**: Understanding lending risk factors  
✅ **Financial Metrics**: Interpreting income, credit, and annuity data  
✅ **Customer Segmentation**: Demographic and behavioral profiling  

---
---
## 👨‍💻 Author

**Saksham Pratap Singh**  
Final Year ECE Student | Data Analytics & ML Enthusiast  
📧 sakshamraghav14@gmail.com | 📍 Agra, India

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Dataset inspired by real-world credit risk scenarios
- Python data science community for excellent libraries
