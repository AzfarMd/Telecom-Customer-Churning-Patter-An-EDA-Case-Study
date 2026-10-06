# Telecom Customer Churn Analysis - EDA Case Study

An in-depth Exploratory Data Analysis (EDA) on customer churn dynamics in the telecommunications sector. This project investigates demographic factors, service usage patterns, account configurations, and pricing structures to uncover key drivers behind churn and identify actionable retention strategies.

---

## Repository Structure

```text
├── Customer_Churn.csv          # Primary telecom customer dataset
├── EDA.ipynb                   # Step-by-step exploratory analysis and visualizations
├── Decoding-Telecom-Churn.pdf  # Summary presentation deck of insights
└── README.md                   # Project overview and setup documentation
```

---

## Objectives

- **Identify Churn Indicators:** Pinpoint behavioral, contractual, and demographic features strongly correlated with churn.
- **Service Dependency:** Evaluate churn rates across internet service types (DSL vs. Fiber Optic) and add-on services (Tech Support, Online Security, Streaming).
- **Contract & Billing Dynamics:** Analyze churn probability across contract durations (Month-to-month vs. Multi-year) and payment methods.
- **Customer Lifetime Value:** Examine the distribution of Monthly Charges and Total Charges across churned vs. active segments.

---

## Key EDA Insights

1. **Contract Structure:** Customers on month-to-month contracts exhibit significantly higher churn rates compared to those on one- or two-year commitments.
2. **Tenure Trends:** Highest churn occurs within the first 6–12 months; retention improves substantially as customer tenure increases.
3. **Service Profiles:** Fiber optic users display higher churn rates relative to DSL subscribers, often correlating with pricing sensitivity and support accessibility.
4. **Support Add-ons:** Customers without supplementary services like Tech Support and Online Backup are substantially more likely to churn.

---

## Setup & Running the Notebook

### 1. Prerequisites
- Python 3.8+
- Jupyter Notebook / JupyterLab

### 2. Environment Setup

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch Analysis

```bash
jupyter notebook EDA.ipynb
```
