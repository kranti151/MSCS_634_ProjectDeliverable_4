# MSCS 634 – Final Project Deliverable 4: Advanced Data Mining for Data-Driven Insights and Predictive Modeling

**Author:** Komalben Suthar
**Course:** Advanced Big Data and Data Mining

---

## Overview

This repository contains the final deliverable of a multi-phase data mining project focused on understanding customer behavior through advanced analytical techniques. Using a synthetic Customer Experience Dataset with 1,000 records and 10+ features, the goal is to build predictive models, uncover behavioral patterns, and derive actionable insights that can support customer experience optimization.

The project integrates:

*   Data preprocessing and exploration
*   Regression modeling
*   Classification and clustering
*   Association rule mining
*   Final insights, recommendations, and ethical considerations

This deliverable consolidates all findings and presents a complete end-to-end data mining workflow.

---

## Dataset Summary

**Dataset:** Customer Experience Dataset for AI-Driven Optimization
**Records:** 1,000
**Features:** Demographics, behavioral metrics, interactions, satisfaction scores, retention status

**Why this dataset?**

*   Simulates real-world customer journeys
*   Includes enough attributes to run regression, classification, and clustering
*   Enables meaningful business insights for customer satisfaction and retention
*   Cleanly structured and suitable for educational data mining tasks

---

## Summary of Project Steps

### Deliverable 1: Data Preprocessing & EDA

**Key Actions**

*   Checked data types, missing values, duplicates
*   Handled outliers and normalized numeric features
*   One-hot encoded Gender, Location, and Retention Status
*   Visualized distributions, correlations, and interaction patterns

**Insights**

*   Engagement variables drive strong behavioral relationships
*   Feedback Score correlates positively with Satisfaction Score
*   Retention patterns hinted at strong separability (later confirmed in classification)

### Deliverable 2: Regression Modeling

**Feature Engineering**

*   Engagement Rate (time spent per interaction)
*   Purchase-to-View Ratio (purchase conversion intensity)

**Models Built**

*   Linear Regression
*   Ridge Regression
*   Lasso Regression

**Findings**

*   All models produced low or negative R² values
*   Satisfaction Score is not predictable with the available features
*   Indicates missing qualitative or contextual drivers of satisfaction

### Deliverable 3: Classification, Clustering, and Pattern Mining

**Classification**

*   Decision Tree and tuned Random Forest
*   Achieved 100 percent accuracy and F1 score on this synthetic dataset
*   Retention Status is highly predictable due to clear feature separability

**Clustering**

*   PCA used to reduce dimensions for visualization
*   K-Means grouped customers into three meaningful segments:
    *   High engagement
    *   Moderate engagement
    *   Low engagement

**Association Rules (Apriori)**

*   Strong co-occurrence found between:
    *   Product views
    *   Interactions
    *   Purchases
*   Indicates a smooth engagement-to-purchase behavioral flow
