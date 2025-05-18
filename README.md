# 👩‍💼 Employee Attrition Analysis – Python Project

## 📌 Project Overview

This Python project explores employee attrition data with the goal of identifying **basic patterns** that may explain why employees leave an organization. Using data handling and visualization techniques, this project provides an introduction to how businesses can begin to understand attrition trends.

> ️**Disclaimer:** The dataset used is not real company data. It was sourced from the internet for learning and demonstration purposes only.

---

## 🎯 Project Objectives

- Learn how to import and explore a dataset using Python.
- Identify and handle missing values in a real-world-like dataset.
- Create basic visualizations to understand the relationship between different features and employee attrition.

---

## 📁 Dataset Description

The dataset (`dataset.csv`) contains synthetic employee records with details such as:

- **Demographics**: Age, Gender, Education, Marital Status
- **Work-Related Info**: Department, Job Role, Business Travel Frequency, Job Satisfaction, Monthly Income
- **Target Variable**: `Attrition` (Yes/No), showing whether the employee left the organization

This dataset is often used to introduce basic HR analytics concepts.

---

## 🧹 Data Cleaning & Preparation

Here’s what was done to clean and prepare the dataset:

- ✅ Imported the dataset using **pandas** in Google Colab.
- ✅ Identified missing values using **`.isnull()`** and visualized them using the `missingno` library.
- ✅ Filled missing values with either:
  - **Mean value** (for numerical columns)
  - **Most frequent value** (for categorical columns)
- ✅ Standardized inconsistent entries:
  - For example, replaced `'M'` with `'Male'` in the `Gender` column (11 such cases).
  
---

## 📊 Visualizations Performed

Using **Matplotlib** and **Seaborn**, a few basic visualizations were created to observe patterns in the data:

1. 📊 **Age-wise distribution of employees**  
   `sns.countplot()` was used to visualize how employee counts vary by age.

2. 📦 **Relation between Age and Attrition**  
   `sns.boxplot()` was used to observe age distribution among employees who left vs. those who stayed.

3. ✈️ **Business Travel Frequency vs. Attrition Rate**  
   `sns.barplot()` highlighted how travel frequency may relate to employee turnover.

4. 👨‍👩‍💼 **Job Satisfaction Levels among Genders**  
   `sns.countplot()` showed how job satisfaction varies across male and female employees.

> ℹ️ While many more visualizations could be added, these were selected to demonstrate a few key observations.

---

## 🧰 Tools & Libraries Used

- Python (Google Colab)
- pandas
- missingno
- seaborn
- matplotlib

Thank You!
