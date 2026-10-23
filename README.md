
# Telco Customer Churn Analysis

An end-to-end data analytics and business intelligence project focused on understanding customer churn, identifying high-risk customer segments, and developing actionable recommendations to improve customer retention in the telecommunications industry.

## Project Overview

Customer churn is a major challenge for subscription-based businesses because losing customers can affect recurring revenue and long-term customer relationships.

This project analyzes customer demographics, service preferences, contract types, tenure, and reported churn reasons to identify patterns associated with customer attrition. The findings are presented through interactive Power BI dashboards to support data-driven business decisions.

## Project Objectives

- Measure overall customer churn and retention performance.
- Identify customer segments with higher churn rates.
- Analyze the relationship between churn, contract type, and customer tenure.
- Explore customer profiles, service preferences, and payment methods.
- Examine the most frequently reported reasons for customer churn.
- Develop actionable recommendations to support customer retention.

## Dashboard Preview

### 1. Executive Overview — Customer Churn Analysis

Provides an overview of customer retention performance and highlights the customer segments most associated with churn.

![Executive Overview Dashboard](https://raw.githubusercontent.com/hafizhrifandi11/telco_customer_churn_analysis/main/dashboard1.png)

**Key components:**
- Total customers, churn rate, retention rate, and churned customers.
- Churn rate by contract type.
- Churn rate by monthly charge group.
- Churn rate by internet service type.
- Churn rate by customer tenure.
- Churn rate by payment method.
- Top five reported churn reasons.
- Churn analysis by contract type and tenure group.

### 2. Customer Profile Dashboard

Explores customer demographics, service preferences, and account characteristics to provide a broader understanding of the customer base.

![Customer Profile Dashboard](https://raw.githubusercontent.com/hafizhrifandi11/telco_customer_churn_analysis/main/d2.png)

**Key components:**
- Total customers, average age, average tenure, and customer satisfaction score.
- Customer distribution by age group.
- Customer status distribution.
- Contract type distribution.
- Internet service type distribution.
- Average monthly charges by contract type.
- Customer distribution by payment method.

## Dataset Overview

The project uses the IBM Telco Customer Churn sample dataset, which contains customer-level information about demographics, subscribed services, account details, and churn status.

| Dataset characteristic | Description |
|---|---|
| Customer records | 7,043 |
| Integrated columns | 51 |
| Source tables | 6 |
| Industry | Telecommunications |
| Analysis level | Customer churn and retention |

The integrated dataset combines customer information from multiple data tables to support a broader analysis of customer behavior and churn patterns.

**Dataset source:** [IBM Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Tools and Technologies

- **Python (Pandas):** Data processing, preparation, and analysis.
- **Power BI:** Interactive dashboard development and data visualization.
- **DAX:** Measures and calculated metrics for dashboard reporting.
- **GitHub:** Project documentation and portfolio publication.

## Analytical Approach

The project follows a structured analytics workflow:

1. **Data Preparation** — Load, inspect, and prepare the source datasets for analysis.
2. **Data Integration** — Combine relevant customer information from multiple tables.
3. **Exploratory Data Analysis (EDA)** — Examine customer distributions and churn patterns.
4. **Metric Development** — Calculate key performance indicators, including churn rate and retention rate.
5. **Dashboard Development** — Build two Power BI dashboards for executive overview and customer profiling.
6. **Insight Generation** — Interpret the findings and identify customer segments requiring attention.
7. **Business Recommendations** — Translate the analytical findings into practical retention initiatives.

## Key Business Findings

### 1. Overall Customer Churn

- Total customers: **7,043**
- Churned customers: **1,869**
- Overall churn rate: **26.54%**
- Retention rate: **73.46%**

Approximately one in four customers has churned, highlighting an opportunity to strengthen customer retention.

### 2. Contract Type and Churn

| Contract type | Churn rate |
|---|---:|
| Month-to-Month | 45.84% |
| One Year | 10.71% |
| Two Year | 2.55% |

Month-to-Month customers have the highest churn rate. Longer-term contracts are associated with substantially lower churn rates, making contract type an important dimension for further retention analysis.

### 3. Customer Tenure and Churn

| Tenure group | Churn rate |
|---|---:|
| 0–6 months | 52.94% |
| 7–12 months | 35.89% |
| 13–24 months | 28.71% |
| 25–48 months | 20.39% |
| 49–60 months | 14.42% |
| 61–72 months | 6.61% |

Churn rates decline as customer tenure increases. Customers in their first six months represent an important segment for early engagement and retention initiatives.

### 4. Reported Churn Reasons

The five most frequently reported reasons in the dashboard include:

- Price too high
- Product dissatisfaction
- Service dissatisfaction
- Poor expertise of online support
- Poor expertise of phone support

These findings highlight pricing, perceived product value, and service experience as areas for further investigation.

## Business Recommendations

### Strengthen Early Customer Engagement

Introduce onboarding check-ins, proactive communication, and timely support during the first six months of the customer lifecycle.

### Encourage Suitable Long-Term Contracts

Evaluate targeted incentives and contract options for Month-to-Month customers while ensuring that offers align with customer needs and affordability.

### Review Pricing and Product Value

Investigate pricing competitiveness and assess whether product offerings and service bundles meet customer expectations.

### Improve Customer Service Experience

Review service dissatisfaction and support feedback to identify recurring issues and prioritize service improvements.

### Monitor High-Risk Customer Segments

Use dashboard findings to monitor churn patterns by contract type, tenure, internet service, and payment method. Evaluate retention initiatives using measurable outcomes.

## Project Limitations

- The analysis identifies associations and patterns in the available dataset; it does not establish that a particular factor directly causes churn.
- Reported churn reasons reflect recorded customer feedback and may not capture every factor influencing a customer's decision.
- The dataset represents a snapshot of customer information and does not independently establish how customer behavior changes over time.
- Business recommendations should be evaluated through subsequent monitoring and, where feasible, controlled experiments.

## Skills Demonstrated

- Data preparation and integration
- Exploratory data analysis
- Customer churn and retention analysis
- KPI development and DAX measures
- Power BI dashboard design
- Data visualization and business storytelling
- Insight generation and actionable business recommendations
- GitHub project documentation

## Author

**Muhammad Hafizh Rifandi**

Aspiring Data Analyst | Business Intelligence | Python | Power BI

GitHub: [@hafizhrifandi11](https://github.com/hafizhrifandi11)

---

*This project was developed as a data analytics and business intelligence portfolio project to demonstrate how customer data can be transformed into actionable business insights.*
