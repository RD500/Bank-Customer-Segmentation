# Bank Customer Segmentation

## Overview

This project focuses on **bank customer segmentation** using clustering techniques to group clients based on their demands and financial habits. The goal is to derive actionable insights for personalized banking services and targeted marketing campaigns.

---

## Table of Contents

1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Literature Survey](#literature-survey)
4. [Dataset Description](#dataset-description)
5. [Implementation](#implementation)
    - [Tools and Libraries](#tools-and-libraries)
    - [Clustering Methodology](#clustering-methodology)
    - [Code and Results](#code-and-results)
6. [Conclusion](#conclusion)
7. [References](#references)

---

## Abstract

The project employs **clustering techniques** such as K-Means to analyze customer data, including transaction patterns, account history, and demographics. This segmentation enables improved customer targeting and service optimization.

---

## Introduction

Customer segmentation is critical in understanding and catering to diverse customer needs. Banks can utilize this to:

- Enhance customer service.
- Optimize marketing campaigns.
- Tailor products and services to specific groups.

The project implements **K-Means Clustering** for grouping customers based on parameters like demographics, spending habits, and account balance.

---

## Literature Survey

### Key Papers:
1. **Bin Song**  
   - *Fresh Produce E-commerce Segmentation*  
   - 2023 IEEE ITOEC Conference.

2. **S. Raj et al.**  
   - *Customer Segmentation Using Credit Card Data Analysis*  
   - 2023 IEEE SERA Conference.

### Key Insights:
- Various clustering algorithms have been employed for customer segmentation in fields like e-commerce, banking, and telecommunications.

---

## Dataset Description

- **Size**: Over 1 million transactions by 800,000+ customers.  
- **Features**:
  - Customer demographics (age, gender, location).
  - Account balance.
  - Transaction details (amount, type).

### Objectives:
1. Perform clustering to identify customer groups.
2. Analyze regional patterns.
3. Conduct transaction-related studies for service optimization.

---

## Implementation

### Tools and Libraries

- **NumPy**: Array operations and linear algebra.  
- **Pandas**: Data manipulation and analysis.  
- **Matplotlib & Seaborn**: Data visualization.  
- **Scikit-Learn**: Clustering algorithms.

### Clustering Methodology

1. **Demographic Segmentation**  
   - Based on customer age and account balance.

2. **Behavioral Segmentation**  
   - Transaction amount vs. account balance.

3. **Geographic Segmentation**  
   - Location vs. account balance.

### Code and Results

- **Elbow Method**: Determining optimal clusters.  
- **K-Means Algorithm**: Segmentation across various dimensions.

#### Results:

- **Demographic Segmentation:**
  - Ages 20–25 contribute less to clusters; working-class customers are the main targets.

- **Behavioral Segmentation:**
  - Customers with high transaction amounts and account balances are key targets.

- **Geographic Segmentation:**
  - Locations with high account balances are identified for expansion.

> **Images Placeholder**:  
> Include elbow plots and cluster visualizations for each segmentation type.  
> Example:  
> ![Elbow Plot](path/to/elbow_plot.png)  
> ![Cluster Visualization](path/to/cluster_visualization.png)

---

## Conclusion

Effective clustering allows banks to:

1. Identify high-value customers.
2. Enhance service personalization.
3. Make informed decisions regarding new services and resource allocation.

Future work involves refining clustering methods and experimenting with real-world workload data.

---

## References

1. Bin Song. *A Path to Implementing Fresh Produce E-commerce Customer Segmentation*. DOI:10.1109/ITOEC57671.2023.10291762.  
2. S. Raj et al. *Customer Segmentation Using Credit Card Data Analysis*. DOI:10.1109/SERA57763.2023.10197704.  
3. L. Rajput et al. *Customer Segmentation of E-commerce Data*. DOI:10.1109/SERA57763.2023.10197704.

---

## Authors

- **Aishwarya V Shetty** (RVCE23BCS195)  
- **D Rakshitha** (RVCE23BCS252)  
- **Bhoomika Sundar** (RVCE23BCS086)  

Project submitted as part of the **Introduction to Python Programming - AI115AI** course at RV College of Engineering.

Dataset:
https://www.kaggle.com/datasets/shivamb/bank-customer-segmentation
