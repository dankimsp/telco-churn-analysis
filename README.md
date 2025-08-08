# Telco Customer Churn Analysis

## Business Objective
This project analyzes customer churn patterns for a telecommunications company with the goal of identifying at-risk customers and informing data-driven retention strategies. Reducing churn even marginally can lead to substantial revenue gains and improved customer lifetime value.

## Key Business Questions
- What are the main drivers of customer churn?
- Which customer segments are most at risk?
- What is the projected revenue impact of reducing churn by 10%?
- What retention strategies should be prioritized?

## Dataset
- **Source:** IBM Telco Customer Churn Dataset (via Kaggle)
- **Size:** 7,043 customers
- **Features:** 21 attributes including demographics, service subscriptions, contract details, and churn status

## Methodology
1. **Exploratory Data Analysis (EDA):** Identified behavior patterns and churn drivers
2. **Feature Engineering:** Binned, encoded, and transformed data for model readiness
3. **Churn Prediction:** Built classification models using XGBoost
4. **Insights & Recommendations:** Translated model output into actionable business strategies

## Technology Stack
- **Python:** pandas, numpy, scikit-learn, XGBoost
- **Visualization:** seaborn, matplotlib
- **ML Modeling:** XGBoost, logistic regression
- **Tools:** Jupyter Notebook, Git/GitHub

## Project Structure
```
├── data/                    # Raw and processed data
├── notebooks/              # Jupyter notebooks for EDA & modeling
│   ├── 01_EDA_DC_FE.ipynb  # EDA, Data Cleaning, Feature Engineering
│   └── 02_Modeling.ipynb
├── src/                    # Helper functions and utilities
├── reports/                # Executive summary and presentations
└── README.md              # Project documentation
```

## Key Findings
- **Early churn risk is highest** among customers with:
  - **Month-to-month contracts**
  - **Short tenure (under 12 months)** — possibly due to onboarding issues
- **Customers likely to stay** tend to have:
  - **Long-term contracts (1- or 2-year)**
  - **Additional services** (Streaming, TechSupport, etc.)
  - **Stable payment methods** (Bank transfer, Credit card)
- **Factors with minimal impact:**
  - Gender, having a phone line, paperless billing

## Business Impact
- Reducing churn by just **10%** could preserve over **$700K in annual revenue** based on average customer lifetime value (CLV)
- Retention strategies should focus on:
  - Incentivizing long-term contracts
  - Improving onboarding experience for new customers
  - Targeting month-to-month customers with bundled service offers

## Contact
**Daniel Kim**  
Data Analyst | Aspiring Applied Machine Learning Engineer 
📧 danielcyk123@gmail.com  
💼 [LinkedIn Profile](your-linkedin-url)

---
*This project demonstrates expertise in customer analytics, machine learning, and business strategy for data-driven decision making.*
