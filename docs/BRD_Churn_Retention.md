\# Business Requirements Document (BRD) - Churn \& Retention Analytics



\## 1. Executive Summary

This document outlines the analytical findings and business requirements for mitigating customer turnover within our telecom services. Utilizing historical subscriber data, a predictive analytics engine was developed to profile customer behavioral patterns and identify primary drivers of churn. Our objective is to transition high-risk segments to stable accounts, protecting annualized revenue structures.



\## 2. Project Objective

\* Develop an optimized predictive classification pipeline targeting high-probability churn indicators.

\* Identify critical service and contractual metrics impacting customer lifecycles.

\* Provide an actionable strategic map to guide targeted marketing and client-retention workflows.



\## 3. System Architecture \& Performance

Our finalized predictive engine utilizes a standardized, feature-scaled Logistic Regression framework optimized for tabular data vectors:

\* \*\*Model Baseline Accuracy:\*\* 80.55%

\* \*\*Model ROC-AUC Score:\*\* 0.8423



!\[Model ROC Curve](../images/08\_roc\_curve.png)



\## 4. Key Business Insights \& Churn Drivers

An evaluation of our customer base shows a baseline \*\*Overall Churn Rate of 26.54%\*\*. The machine learning pipeline isolated four critical operational drivers influencing subscriber termination:



\### A. Contract Terms (Strongest Churn Driver)

Month-to-month subscribers represent the highest concentration of churn. Securing long-term fixed commitments serves as the single strongest preventative measure against revenue degradation.

\* \*\*Month-to-Month Churn Risk Coefficient:\*\* Base tier indicator

\* \*\*Two-Year Contract Protection Coefficient:\*\* -1.3253



!\[Churn by Contract](../images/02\_churn\_by\_contract.png)



\### B. Subscriber Onboarding Tenure Lifecycle

Customer churn is highly concentrated within early relationship milestones. Risk drops off exponentially once a subscriber crosses initial tenure windows, highlighting a critical need for early-stage customer success programs.

\* \*\*Tenure Protection Coefficient:\*\* -1.2649

\* \*\*Risk Window:\*\* Highest volume of cancellations observed between months 0–10.



!\[Tenure Distribution Chart](../images/06\_tenure\_distribution.png)



\### C. Infrastructure Service Delivery (Fiber Optic Exposure)

Subscribers on Fiber Optic lines show highly elevated churn rates compared to standard DSL installations. This anomaly suggests an issue with competitive price structures, onboarding expectations, or service delivery friction.

\* \*\*Fiber Optic Churn Risk Coefficient:\*\* +1.1302



\### D. Billing Methods \& Technical Assistance

Subscribers processing invoices manually via electronic checks display an increased likelihood of departure compared to automated banking methods. Additionally, customers lacking structural Tech Support show high vulnerability.

\* \*\*Electronic Check Churn Risk Coefficient:\*\* +0.3847

\* \*\*Tech Support Protection Coefficient:\*\* -0.3591



\## 5. Risk Segment Profiling Matrix

By parsing customer profiles through our predictive engine, the subscriber base is divided into three distinct risk classification categories:



| Churn Risk Segment | Total Customer Base | Observed Churn Rate | Monthly Billing Revenue At Risk |

| :--- | :---: | :---: | :--- |

| \*\*Low Risk\*\* | 4,372 | 9.81% | \\$250,445.45 |

| \*\*Medium Risk\*\* | 1,633 | 42.50% | \\$120,198.95 |

| \*\*High Risk\*\* | 1,038 | 71.87% | \\$85,472.20 |



!\[Actual Churn by Risk Segment](../images/14\_risk\_segments.png)



\## 6. Financial Impact Analysis

Customer churn creates an immediate and severe drain on corporate cash flow structures:

\* \*\*Monthly Revenue Lost to Active Churn:\*\* \\$139,130.85

\* \*\*Annualized Revenue Lost to Active Churn:\*\* \\$1,669,570.20



\## 7. Strategic Recommendations

1\. \*\*Contractual Incentive Matrix:\*\* Launch an automated campaign targeting Month-to-Month users, offering bill credits to transition them to 1-year or 2-year terms.

2\. \*\*Onboarding Safeguard Protocols:\*\* Implement proactive customer success checkpoints for all new sign-ups within their first 90 days.

3\. \*\*Billing Automation Drive:\*\* Provide a one-time invoice credit for customers switching from manual electronic checks to automated paperless bank transfers.

