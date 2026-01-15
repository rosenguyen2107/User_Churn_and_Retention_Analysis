# User Churn & Retention Analysis in E-commerce
*A Product Analytics & Predictive Modeling Case Study*

## Project Overview
This project analyzes user behavior and churn dynamics in a large-scale e-commerce platform using event-level data.
The objective is to answer three core product questions:
1. Where do users drop off in the activation funnel?
2. Which behavioral signals causally drive churn?
3. Which product levers can most effectively improve retention?
   
The project combines:
- Funnel and cohort analysis (descriptive)
- Churn prediction (logistic regression)
- Causal interpretation (Partial Dependence)
- Behavioral segmentation (value & engagement)
- Prescriptive business recommendations
- This structure mirrors how Product Analytics and Data Science teams support growth and retention decisions in real-world companies.

## Data Source
Dataset:

E-commerce Events History (October 2019)

Source: Kaggle – Multi-category online retail platform

Granularity: Event-level (view, cart, purchase)

Key columns:

| Column        | Description              |
| ------------- | ------------------------ |
| event_time    | Timestamp of user action |
| event_type    | view / cart / purchase   |
| user_id       | Unique user identifier   |
| user_session  | Session identifier       |
| product_id    | Product identifier       |
| category_code | Product category         |
| price         | Transaction price        |

This analysis focuses on a one-month window to study early activation, short-term retention, and churn dynamics. While longer horizons enable seasonality analysis, this time frame is sufficient to identify behavioral drivers of attrition and high-leverage product interventions.
