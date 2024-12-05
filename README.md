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
   - *A path to implementing a fresh produce e-commerce customer segmentation method based on clustering algorithms*  
   - 2023 IEEE ITOEC Conference.

2. **S. Raj, S. Roy, S. Jana, S. Roy, T. Goto and S. Sen.**  
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
  ![image](https://github.com/user-attachments/assets/2cd7eb7a-b8b1-4819-b1d4-c8938cf498ac)
  ![image](https://github.com/user-attachments/assets/a3f0f7d2-90b9-4f98-88ee-b8c0cb4e248e)
  ![image](https://github.com/user-attachments/assets/238b1ef6-e383-4c82-beb6-aafb6d93c9ec)




#### Results:

1. **Clusters and their corresponding elbow plots (Demographic Segmentation):**
 - ![Demographic Plot](https://github.com/user-attachments/assets/493b5614-a2eb-40e4-88ec-a8a907111304)   ![Demographic Plot](https://github.com/user-attachments/assets/86a1fd93-dbc6-4c14-9fb1-02b37734e8cd)
 - Ages 20–25 contribute less to clusters; working-class customers are the main targets.

2. **Clustering using Transaction Amount and Account Balance ( Behavioral Segmentation):**
 - ![Behavioral Plot](https://github.com/user-attachments/assets/79e41b6a-73c9-4afe-a4c6-5aa0a366a3bb) ![Behavioral Plot](https://github.com/user-attachments/assets/a11138c5-a384-45f1-9845-4714be2f320f)
 - Customers with high transaction amounts and account balances are key targets.


    

3. **Clustering using Customer Location and Account Balance (Geographic Segmentation):**
  - ![Geographic Plot](https://github.com/user-attachments/assets/411d0b1e-05b7-4b7e-9452-d37dd9ea9c05) ![Geographic Plot](https://github.com/user-attachments/assets/f9ecfe28-6432-441d-b800-0e4d0e30dbde)
  - Variability is least in green cluster and gets higher towards yellow cluster



4. **Clustering using Customer Location and Account Balance:**
 - ![image](https://github.com/user-attachments/assets/d0ee9ba9-c30b-4cdc-84c8-83bcf4d69199)  ![image](https://github.com/user-attachments/assets/28f2f23b-a76b-424f-bea0-d0f1e471e314)


  - We can see the locations where transaction amount is high and specifically target them




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
 

Project submitted as part of the **Introduction to Python Programming - AI115AI** course at RV College of Engineering.

Dataset:
https://www.kaggle.com/datasets/shivamb/bank-customer-segmentation
