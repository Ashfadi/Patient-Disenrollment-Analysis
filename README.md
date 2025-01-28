# 📊 Patient Disenrollment Analysis

This repository contains an analysis of **patient disenrollment** from healthcare services. The goal of the project is to identify key factors driving disenrollment and provide actionable insights to improve member retention.

---

## 📌 Features
- **Exploratory Data Analysis (EDA)** to understand patterns in membership duration, health plans, and care interactions.
- **Chi-Square and Correlation Analysis** to identify statistically significant factors.
- **Logistic Regression** (single and multivariate) and **Random Forest** for predictive modeling.
- **Actionable Insights** and recommendations for reducing disenrollment rates.

---

## 📊 Key Analyses
### 1️⃣ Membership Duration
- **Finding**: Members with shorter durations are more likely to disenroll.
- **Recommendation**: Target newer members with engagement strategies in the first 3 years.

### 2️⃣ Health Plan Analysis
- **Finding**: Certain plans (e.g., "Humana") have higher disenrollment rates.
- **Recommendation**: Gather feedback and address plan-specific dissatisfaction.

### 3️⃣ Primary Care Provider (PCP) Changes
- **Finding**: Frequent PCP changes correlate with disenrollment.
- **Recommendation**: Improve continuity of care by minimizing unnecessary PCP changes.

### 4️⃣ Authorization Denials
- **Finding**: Members experiencing prior authorization denials are more likely to leave.
- **Recommendation**: Streamline authorization processes and educate members.

---

## 🛠 Methodology
1. **Data Preprocessing**
   - Handled missing values and scaled numerical variables.
   - Encoded categorical features like health plans.
2. **Statistical Analysis**
   - Used **Chi-Square** tests for categorical variables (e.g., health plans).
   - **Correlation Analysis** for numerical variables (e.g., membership duration).
3. **Predictive Modeling**
   - Applied **Logistic Regression** and **Random Forest** to predict disenrollment likelihood.
   - Evaluated models using **ROC AUC**, **accuracy**, and **coefficients**.

---

## 📈 Results
### Model Performance
- **Logistic Regression (Multivariate)**:
  - Accuracy: **74%**
  - ROC AUC: **0.78**
- **Key Features**:
  - Membership Duration (`memberMonthsCount`): Strong positive impact on retention.
  - PCP Changes: Frequent changes negatively impact retention.
  - Authorization Denials: Higher denial rates increase disenrollment likelihood.

---

## 📝 Reports
The following reports provide detailed insights:
- **Disenrollment Analysis Report**: Overview of key findings and recommendations.
- **Enhanced Analysis Report**: Focus on Random Forest feature importance.
- **Patient Disenrollment Methodology**: Step-by-step statistical and predictive modeling methodology.

---

## 🔥 Recommendations
1. **Engage New Members**: Prioritize members in their first 3 years with personalized outreach.
2. **Focus on PCP Stability**: Reduce unnecessary PCP changes to maintain care continuity.
3. **Optimize Authorization Processes**: Simplify prior authorizations to minimize dissatisfaction.
4. **Plan-Specific Improvements**: Gather feedback from members of high-disenrollment plans to address concerns.
