#  PhonePe Financial Analytics Dashboard (Power BI)

## Project Overview
<img width="299" height="89" alt="image" src="https://github.com/user-attachments/assets/da278b32-131e-4c0e-8778-88f1fc4845fd" />

This project presents a comprehensive end-to-end analytics dashboard built on PhonePe-style transactional data using Power BI.
The dashboard analyzes Payments, Insurance, Loans, Money Transfers, and Bill Payments, covering transaction volume, success rates, failure reasons, service-wise contribution, and daily trends.

## The goal is to:

•Monitor financial performance

•Identify failure bottlenecks

•Understand user behavior patterns

•Enable data-driven decision-making

##  Global Filters & KPIs (Applicable to All Pages)

## Date Range Filter: 01-01-2024 to 30-12-2024

## Key KPIs across dashboards:

•Total Amount

•Total Transactions

•Successful Transactions

•Failed Transactions

This ensures time-based comparative analysis across all services.

#  1. Home Dashboard (Overall Performance)

##  What this dashboard shows:
<img width="1440" height="805" alt="Screenshot 2025-12-25 110227" src="https://github.com/user-attachments/assets/901b2207-6adc-4b43-a1e0-0ca245640275" />


A high-level summary of all PhonePe services combined.

##  Visual Breakdown:

## 1️ KPI Cards

**Total Amount:** 3,474M

**Total Transactions:** 300K

**Successful Transactions:** 288K

**Failed Transactions:** 12K

##  Insight:

Success rate is ~96%, indicating strong system reliability but still room to reduce failures at scale.

## 2️ Total Amount by Service (Bar Chart)

•Loans dominate transaction value

•Insurance and Money Transfer follow

•Recharge Bills contribute the least

##  Business Insight:

Loan products are the primary revenue driver, requiring higher reliability and fraud control.

## 3️ Failed Payment by Reason (Pie Chart)

•Server Error (highest)

•Wrong PIN

•Insufficient Amount

•Wrong Info

•Bank Denied

##  Actionable Insight:

Most failures are system or UX-driven, not user intent—highlighting scope for backend and UI optimization.

## 4️ Sum of Amount by Day (Line Chart)

•Daily fluctuations between 4M–5.6M

•Sharp drop on last day (likely incomplete data)

##  Observation:

Consistent usage pattern with end-of-month volatility, common in financial platforms.

##  2. Insurance Dashboard

##  Purpose:
<img width="1443" height="812" alt="Screenshot 2025-12-25 110256" src="https://github.com/user-attachments/assets/d4ab1068-82d6-43ad-b10b-8da2aa43f194" />

Analyze insurance transactions by type, status, and failures.

## 1️ KPI Summary

**Total Amount:** 513M

**Total Transactions:** 300K

**Successful:** 288K

**Failed:** 12K

## 2️ Failed Payment Reason (Donut Chart)

•Wrong PIN

•Server Error

•Insufficient Amount

##  Key Insight:

Failures are almost evenly distributed, meaning no single failure point dominates.

## 3️ Payment Status (Pie Chart)

**Successful:** 47.88K

**Failed:** 2.12K

##  Performance:

Insurance transactions show very high reliability.

## 4️ Insurance Type-wise Amount

•Bike

•Car

•Term Life

•Health

##  Insight:

Vehicle insurance leads, reflecting higher frequency renewals vs long-term health policies.

## 5️ Total Amount by Day

•Stable trend around 0.6M–0.9M

•Sharp fall at month end

##  3. Loans Dashboard

##  Purpose:
<img width="1440" height="804" alt="Screenshot 2025-12-25 110326" src="https://github.com/user-attachments/assets/c5a6edf8-82b9-44a3-a982-b69900866337" />

## Understand loan disbursement patterns and failures.

## 1️ KPI Summary

**Total Loan Amount:** 2,533M

**Total Transactions:** 50K

**Successful:** 48K

**Failed:** 2K

##  High value, low volume nature of loan products is evident.

## 2️ Failed Payment Reasons

•Wrong Info

•Server Error

•Bank Denied

##  Critical Insight:

Loan failures are mostly verification and bank-side issues, not user errors.

## 3️ Payment Status

**Successful:** 47.97K

**Failed:** 2.03K

## 4️ Loan Type-wise Amount

•Gold Loan (Highest)

•Auto Loan

•Mutual Fund

•Credit Score-related services

##  Observation:

Gold loans dominate due to lower risk and faster approval cycles.

## 5️ Loan Amount by Day

•Strong volatility (2.3M–4.2M)

•Reflects approval batch processing

##  4. Money Transfer Dashboard

##  Purpose:
<img width="1440" height="805" alt="Screenshot 2025-12-25 110353" src="https://github.com/user-attachments/assets/4320b30a-df07-416c-9efe-a83ec087fe1f" />

•Analyze peer-to-peer transfer behavior.

##1️ KPI Summary

**Total Amount:** 378M

**Total Transactions:** 150K

**Successful:** 144K

**Failed:** 6K

## 2️ Failed Payment Reason

•Insufficient Amount

•Server Error

•Wrong PIN

##  Insight:

User balance awareness and PIN handling are key UX improvement areas.

## 3️ Payment Status

**Successful:** 362.95M

**Failed:** 15.24M

## 4️ Transfer Type-wise Amount

•To UPI ID

•To QR Code

•To Self Account

•To Mobile Number

##  Trend:

UPI-based transfers dominate, showing strong ecosystem adoption.

## 5️ Transfer Amount by Day

•Stable usage between 0.45M–0.55M

•Month-end dip observed

##  5. Bill Payment Dashboard

##  Purpose:
<img width="1438" height="807" alt="Screenshot 2025-12-25 110416" src="https://github.com/user-attachments/assets/d949676b-79da-4549-b85c-0011dc3607d5" />

•Track utility and recharge payments.

## 1️ KPI Summary

**Total Amount:** 51M

**Total Transactions:** 50K

**Successful:** 48K

**Failed:** 2K

## 2️ Payment Status

**Success rate:** 96%

**Failed:** 3.92%

## 3️ Payment Failure by Reason

•Server Error

•Wrong PIN

•Insufficient Amount

## 4️ Bill Type-wise Amount

•Mobile Recharge

•Electricity Bill

•DTH

•Cable TV

##  Observation:

Utility payments are high frequency but low value, ideal for customer retention.

## 5️ Recharge Amount by Day

vPeaks at ~83K

•Sudden drop at month end

##  Tools & Technologies Used

•Power BI

•DAX

•Data Modeling

•Time-Series Analysis

•Business KPI Design

•UX-focused Dashboard Design

•Excel

##  Key Business Takeaways

•Loan services generate maximum monetary value

•Server errors are a systemic failure reason

•High success rates across all services indicate platform stability

•End-of-month data drops suggest partial data capture or processing lag
