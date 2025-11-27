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
The analysis finds that Telecom Churn is not random — it is highly concentrated in three segments:
* Month-to-Month Customers (≈ 42% churn) - They contribute 55% of all churn losses.
* Fiber Internet Customers (≈ 30–35% churn) - Despite being the highest-paying segment, they churn the most.
* Customers with Zero Add-Ons (churn 2–4× higher) - Low stickiness → high exit risk.

**Reducing churn by 30% unlocks around $1.2M in incremental revenue (from $11.8M → $13.0M)**
The following sections will explore additional contributing factors and highlight key opportunity areas for improvement.
![Churn_Analysis_Dashboard](https://github.com/user-attachments/assets/55dece32-69c2-4c3f-819b-952461ba8973)
