# 🎬 Movie Industry Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a movie industry dataset to uncover financial and performance trends.  

The analysis focuses on profitability (ROI), genre trends, release timing impact, and actor experience to understand what drives movie success.

---

## 🎯 Objectives

The project answers the following key business questions:

1. Is there a relationship between Budget and Revenue?
2. Which genre generates the highest average revenue?
3. Does release timing (Holiday vs Normal) affect revenue?
4. Do movies with new actors perform differently from experienced actors?
5. How are movies distributed across ROI-based performance categories?

---

## 🧹 Data Cleaning & Preparation

- Removed duplicate records
- Dropped irrelevant columns
- Calculated ROI Percentage using:

  ROI = (Revenue - Budget) / Budget × 100

- Created a new feature: `Movie_Performance` based on ROI classification:

  - Disaster  
  - Flop  
  - Below Average  
  - Above Average  
  - Hit  
  - Blockbuster  

This transformation enables business-level performance evaluation.

---

## 📊 Key Analyses

### 1️⃣ Budget vs Revenue
- Scatter plot analysis
- Observed positive relationship between budget and revenue
- Identified outliers where high budget did not guarantee success

### 2️⃣ Genre-wise Revenue Analysis
- Grouped movies by genre
- Calculated average revenue
- Identified top-performing genres

### 3️⃣ Release Period Impact
- Compared revenue distribution between Holiday and Normal releases
- Used boxplot visualization

### 4️⃣ New vs Experienced Actors
- Compared average revenue and budget
- Evaluated financial performance differences

### 5️⃣ ROI-Based Performance Distribution
- Classified movies into performance categories
- Visualized distribution of Hits, Flops, and Blockbusters

---

## 🧠 Key Insights

- Higher budgets generally correlate with higher revenues.
- Certain genres demonstrate stronger earning potential.
- Holiday releases may influence revenue distribution.
- Experienced actors tend to generate higher average revenue.
- The movie industry exhibits high variability in ROI, indicating risk.

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---
