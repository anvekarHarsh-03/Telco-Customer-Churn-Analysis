# Project Background
Telecom companies face recurring revenue loss due to customer churn. With over 7,000+ customers, multiple service lines, and varied contract structures, understanding who churns, why they churn, and how much revenue is at risk is critical.

This project uses data-driven intelligence to:
* Diagnose churn behavior
* Identify high-risk customer microsegments
* Quantify revenue leakage
* Build a Power BI dashboard for executives
* Recommend high-ROI strategies for churn reduction

You can find the Interactive PowerBI dashboard [here](Churn_Analysis_Dashboard.pbix) and the PDF of the Jupyter notebook used to carry out the EDA and predictive revenue analysis [here](TelcoChurnAnalysisPDF.pdf)


# Data Structure Overview
The dataset consists of 7,043 customers and 21 features, grouped into four key categories:

*Customer Demographics*
  * Gender
  * Senior Citizen
  * Partner + Dependents

*Subscription Services*
  * Phone / Multiline
  * Internet Service: DSL, Fiber, No Internet
  * Add-ons (Security, Backup, Tech Support, Streaming, Device Protection)

*Account and Billing*
  * Payment method
  * Contract type
  * Monthly & Total charges
  * Paperless billing

# EXECUTIVE SUMMARY
### Overview of Findings 
The analysis finds that Telecom Churn is not random — it is highly concentrated in three segments:
* Month-to-Month Customers (≈ 42% churn) - They contribute 55% of all churn losses.
* Fiber Internet Customers (≈ 30–35% churn) - Despite being the highest-paying segment, they churn the most.
* Customers with Zero Add-Ons (churn 2–4× higher) - Low stickiness → high exit risk.

**Reducing churn by 30% unlocks around $1.2M in incremental revenue (from $11.8M → $13.0M)**
The following sections will explore additional contributing factors and highlight key opportunity areas for improvement.
![Churn_Analysis_Dashboard](https://github.com/user-attachments/assets/55dece32-69c2-4c3f-819b-952461ba8973)

### Month-2-Month Customers Churn Analysis
Cutomers with month-2-month subsription plan have a churn Rate of 42.7%. Thier total churn volume contribution is 55% of all churn events. **Churn is 7x higher in M-2-M customers than in 2-year subscription customers**. Month-to-month contracts offer flexibility but result in poor loyalty. Historically, M2M customers are price-sensitive and switch quickly.

### Fiber Internet Customers Analysis
Fiber Internet Customers churn at the highest churn rates (30% - 35%). This segament of churned customers represents 40% of Total Revenue Leakages. **Fiber customers have higher monthly charges, amplifying impact**. Fiber users expect premium service. Connection issues cause sharp dissatisfaction translating into the highest churn across service lines.

### Add-On Adoption Dramatically Reduces Churn
Customers with NO add-ons churn at around 25% whereas Customers with add-ons churn at 10–15%. Therefore, Add-ons improve retention 2–4× times. Add-ons (security, backup, support) anchor customers across multiple touchpoints. Historically, multi-service users show higher loyalty in telecom.

<img width="460" height="602" alt="Customers with add-ons and without add-ons sensitivity with churn" src="https://github.com/user-attachments/assets/ca843a63-9c6d-446e-b297-3267958707b8" />

### How Payment Method Impacts Churn
Customers who pay with electronic Check churn at around 40% Whereas those with Other methods Vhurn at less than 15%. Thefore, **Electronic check users churn 3× more**. Electronic check customers tend to have higher billing friction and default rates. The payment method acts as a proxy for customer riskiness.

<img width="923" height="353" alt="Payment method churn analysis" src="https://github.com/user-attachments/assets/b2a3be47-a26e-459a-a799-1c8544e2c504" />


# Reducing Churn Yields Large, Immediate Revenue Uplift
* Current annual revenue: ₹11.8M
* Post-churn revenue: ₹11.06M
* With 30% churn reduction → ₹13.0M

**₹1.2M uplift (almost 10% revenue increase). Churn reduction is the highest-ROI commercial lever in telecom. Small improvements will lead to large compounding gains.**

# Recommendations
* Introduce Soft Lock-In Contracts (6–12 months) for M2M Customers
  * Combine with small discounts
  * Targets the largest churn segment
* Improve Fiber Customer Experience via Proactive Issue Resolution
  * Priority support
  * Automatic outage detection
  * Reduces churn in highest-revenue group
* Bundle Add-Ons for Fiber and New Users
  * Offer discounted packs: Security + Backup + TechSupport
  * Converts low-stickiness users into sticky subscribers

# Included Files
* [Jupyter Notebook PDF](TelcoChurnAnalysisPDF.pdf)
* [Power BI Dashboard](Churn_Analysis_Dashboard.pbix)
* [Data Sample](customers.csv)  

