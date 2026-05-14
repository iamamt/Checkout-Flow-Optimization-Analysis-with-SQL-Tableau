# Checkout Flow Optimization Analysis with SQL & Tableau

## Project Overview

This project focuses on analyzing and optimizing the checkout flow of an online learning platform using SQL and Tableau. The objective was to identify key friction points in the payment journey, improve checkout success rates, and reduce cart abandonment by transforming raw checkout activity data into actionable business insights.

The analysis was conducted on user checkout activity between July 2022 and January 2023, covering cart creation, checkout attempts, payment failures, successful transactions, and device-level behavior.

---

## Business Problem

The platform experienced checkout inefficiencies that impacted conversion rates and customer experience. Users were abandoning carts, encountering payment-related errors, and facing usability challenges during the checkout process.

The project aimed to:

* Analyze user behavior throughout the checkout funnel
* Identify major causes of checkout failures
* Measure checkout success and cart abandonment trends
* Detect device-specific payment issues
* Recommend data-driven improvements to enhance conversions

---

## Objectives

* Measure Monthly Checkout Success Rate
* Measure Monthly Cart Abandonment Rate
* Identify the most common checkout errors
* Analyze checkout behavior across desktop and mobile devices
* Build an interactive Tableau story dashboard for business stakeholders

---

## Tools & Technologies

* SQL (CTEs, JOINs, Aggregations, Filtering)
* Tableau Public
* MySQL Workbench
* CSV Data Processing

---

## Dataset Overview

The dataset included:

* User checkout activity logs
* Cart creation records
* Checkout actions
* Payment status events
* Device information
* Error messages

Analysis period:

* 2022-07-01 to 2023-01-31

---

## Key SQL Operations Performed

* Built multiple Common Table Expressions (CTEs)
* Performed JOIN operations to map user journeys
* Aggregated daily and monthly checkout metrics
* Filtered successful and failed payment events
* Exported processed datasets for Tableau visualization

Key metrics calculated:

* Checkout Success Rate
* Cart Abandonment Rate
* Checkout Attempts
* Successful Transactions
* Device-wise Error Frequency

---

## Tableau Dashboard Features

Developed a 3-page interactive story dashboard containing:

### 1. Checkout Success Rate Dashboard

* Monthly checkout attempts
* Monthly successful payments
* Checkout success percentage trends

### 2. Cart Abandonment Dashboard

* Monthly cart creation trends
* Abandonment rate analysis
* Conversion drop-off identification

### 3. Error & Device Analysis Dashboard

* Most frequent checkout errors
* Device-wise error distribution
* Desktop vs Mobile checkout comparison

---

## Key Insights

* September 2022 recorded the lowest checkout success rate.
* October 2022 showed the highest cart abandonment rate.
* The most frequent error identified was “Number Field is Required”.
* Mobile users experienced significantly more checkout errors compared to desktop users.
* Despite only 32% of checkout attempts coming from mobile devices, mobile users generated the highest error occurrences.

---

## Business Recommendations

### 1. Improve Mobile Checkout Experience

* Enhance visibility of card input fields
* Optimize form responsiveness for smaller screens
* Simplify mobile payment flow

### 2. Implement Real-Time Validation

* Validate card number, expiry date, and CVV during input
* Reduce payment failures caused by incorrect entries

### 3. Introduce Alternative Payment Methods

* Add digital wallets and buy-now-pay-later options
* Reduce dependency on traditional card payments

### 4. Analyze User Demographics

* Investigate payment behavior by device, region, and card type
* Personalize payment support for high-failure user groups

---

## Project Outcomes

* Improved understanding of user checkout behavior
* Identified critical conversion bottlenecks
* Enabled data-driven optimization opportunities
* Delivered actionable insights for improving customer experience and conversion rates

---

## Skills Demonstrated

* Data Cleaning & Transformation
* SQL Query Optimization
* Funnel & Conversion Analysis
* Dashboard Development
* Data Visualization
* Business Intelligence
* User Behavior Analytics
* Problem Solving

---

## Project Structure

```
checkout-flow-optimization/
│
├── sql_queries/
│   ├── checkout_steps.sql
│   ├── checkout_errors.sql
│
├── datasets/
│   ├── checkout_steps.csv
│   ├── checkout_errors.csv
│
├── tableau_dashboard/
│   ├── checkout_story_dashboard.twbx
│
├── screenshots/
│   ├── dashboard_preview.png
│
└── README.md
```

---

## Conclusion

This project demonstrates how SQL and Tableau can be leveraged together to analyze customer checkout behavior, uncover conversion bottlenecks, and improve user experience through data-driven insights. The findings highlight the importance of optimizing mobile checkou
