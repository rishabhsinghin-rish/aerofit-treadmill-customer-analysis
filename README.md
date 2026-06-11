# Aerofit Treadmill Customer Analysis

## Project Overview

This project analyzes customer purchasing behavior for Aerofit treadmills to identify which customer profiles prefer different treadmill models.

The objective is to help Aerofit understand customer characteristics, purchasing patterns, and product preferences so that marketing efforts and product recommendations can be optimized.

---

## Business Problem

Aerofit wants to answer:

- Who purchases each treadmill model?
- How do income and fitness levels influence product choice?
- Which customer segments prefer premium treadmills?
- What is the probability of purchasing a particular treadmill model?
- How can Aerofit improve customer targeting and sales?

---

## Dataset Information

Dataset Size:

- 180 customer records
- 9 variables

Features:

- Product
- Age
- Gender
- Education
- Marital Status
- Usage
- Fitness
- Income
- Miles

Dataset contains customer demographics, fitness habits, and treadmill purchase information. :contentReference[oaicite:0]{index=0}

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Customer Segmentation
- Probability Analysis
- Business Analytics
- Correlation Analysis
- Data Visualization
- Product Recommendation Analytics

---

## Project Workflow

### 1. Data Understanding

- Dataset Structure
- Data Types
- Descriptive Statistics

### 2. Data Quality Check

- Missing Value Analysis
- Data Validation

### 3. Univariate Analysis

Analyzed:

- Age Distribution
- Income Distribution
- Fitness Levels
- Weekly Usage
- Miles Run

### 4. Bivariate Analysis

Compared treadmill models across:

- Income
- Age
- Miles
- Fitness Levels

### 5. Correlation Analysis

Studied relationships between:

- Income
- Fitness
- Usage
- Miles
- Age
- Education

### 6. Probability Analysis

Calculated:

- Marginal Probabilities
- Product Purchase Probabilities
- Product vs Gender Distribution
- Product vs Marital Status Distribution

---

## Product Portfolio

### KP281

Entry-Level Treadmill

Target Users:

- Beginners
- Budget-conscious customers
- Casual runners

### KP481

Mid-Range Treadmill

Target Users:

- Regular runners
- Moderate fitness customers
- Mid-income buyers

### KP781

Premium Treadmill

Target Users:

- High-income customers
- Fitness enthusiasts
- Heavy treadmill users

---

## Key Findings

### Product Popularity

Purchase Distribution:

- KP281 → 44.4%
- KP481 → 33.3%
- KP781 → 22.2%

KP281 is the most frequently purchased treadmill. :contentReference[oaicite:1]{index=1}

---

### Customer Demographics

Gender Distribution:

- Male: 104 customers
- Female: 76 customers

Marital Status:

- Partnered: 107 customers
- Single: 73 customers

---

### Income Analysis

Premium treadmill buyers (KP781) have significantly higher incomes than KP281 and KP481 customers.

KP781 customers represent Aerofit's high-value customer segment. :contentReference[oaicite:2]{index=2}

---

### Fitness Analysis

Customers purchasing KP781 generally have:

- Higher fitness scores
- Greater weekly usage
- More miles run per week

Fitness level strongly influences premium treadmill adoption. :contentReference[oaicite:3]{index=3}

---

### Running Behavior

Customers running:

- 15+ miles per week
- More frequent workout sessions

show a stronger preference for premium treadmill models. :contentReference[oaicite:4]{index=4}

---

### Correlation Insights

Strong positive relationships observed between:

- Fitness and Miles
- Usage and Miles
- Income and Fitness

This suggests that highly active customers are more likely to invest in premium fitness equipment. :contentReference[oaicite:5]{index=5}

---

## Probability Analysis

### Marginal Probability of Purchase

| Product | Probability |
|----------|------------|
| KP281 | 44.4% |
| KP481 | 33.3% |
| KP781 | 22.2% |

These probabilities can be used to estimate product demand and inventory requirements. :contentReference[oaicite:6]{index=6}

---

## Business Insights

### Entry-Level Customers

KP281 buyers tend to be:

- New to fitness
- Lower income customers
- Casual runners

### Mid-Range Customers

KP481 buyers are generally:

- Moderately active
- Moderate income earners
- Consistent runners

### Premium Customers

KP781 buyers are:

- Higher income earners
- More fitness-oriented
- Heavy treadmill users

---

## Recommendations

### 1. Beginner-Focused Marketing

Promote KP281 to:

- First-time buyers
- Budget-conscious customers
- Young professionals

### 2. Position KP481 as a Growth Product

Target customers who:

- Exercise regularly
- Need better features
- Are upgrading from entry-level models

### 3. Premium Segment Targeting

Market KP781 to:

- High-income customers
- Fitness enthusiasts
- Marathon and endurance runners

### 4. Offer EMI Financing

Provide flexible payment options for premium treadmills to increase adoption.

### 5. Personalized Recommendations

Use customer:

- Income
- Fitness Score
- Weekly Usage

to recommend the most suitable treadmill model.

---

## Visualizations Included

- Product Distribution
- Gender Distribution
- Marital Status Distribution
- Income vs Product Boxplots
- Age vs Product Analysis
- Miles vs Product Analysis
- Correlation Heatmap
- Pairplot Analysis
- Probability Analysis

---

## Project Structure

aerofit-treadmill-customer-analysis/

│

├── Aerofit_Case_Study.ipynb

├── aerofit_treadmill.csv

├── README.md

├── images/

│   ├── product_distribution.png

│   ├── income_analysis.png

│   ├── fitness_analysis.png

│   ├── correlation_heatmap.png

│   └── probability_analysis.png

│

└── project_report.pdf

---

## Project Outcome

This project demonstrates how customer demographics, fitness habits, and income levels influence product selection. The analysis helps Aerofit improve customer segmentation, marketing strategies, and personalized product recommendations.

---

## Author

Rishabh Kumar Singh

Aspiring Data Analyst

Skills:
SQL | Python | Statistics | Pandas | NumPy | Tableau | Excel | Business Analytics
