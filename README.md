# Teen Mental Health and Social Media Analysis

This project explores the impact of social media usage on the mental health and academic performance of teenagers. The analysis is based on a survey dataset of 1,200 respondents, focusing on variables such as sleep patterns, physical activity, anxiety, stress, and addiction levels.

## Table of Contents
1. [Dataset Overview](#dataset-overview)
2. [Files Description](#files-description)
3. [Data Cleaning](#data-cleaning)
4. [Statistical Summary](#statistical-summary)
5. [Analysis and Key Findings](#analysis-and-key-findings)

---

## Dataset Overview
The dataset contains information on 1,200 teenagers across several quantitative and categorical variables. 

### Key Variables:
- **Demographics:** `age` (13-19), `gender`.
- **Usage Patterns:** `daily_social_media_hours`, `platform_usage` (Instagram, TikTok, Both), `screen_time_before_sleep`.
- **Lifestyle & Health:** `sleep_hours`, `physical_activity` (hours), `social_interaction_level` (Low, Medium, High).
- **Mental Health Indicators:** `stress_level`, `anxiety_level`, `addiction_level` (all scaled 1–10), and `depression_label` (0 = No, 1 = Yes).
- **Academic Performance:** `academic_performance` (GPA scale).

---

## Files Description
The analysis is organized into the following files:
- **`Teen_Mental_Health_Dataset.csv`**: The primary raw dataset containing 1,200 records.
- **`Data Dictionary.csv`**: Definitions, data types, and units for every variable.
- **`Data Cleaning.csv`**: Documentation of preprocessing and outlier detection.
- **`Descriptive Statistics.csv`**: Summary statistics (mean, median, mode, SD) for all numerical columns.
- **`Visualizations.csv`**: Data summaries used to generate histograms and box plots.
- **`Hypothesis Testing.csv`**: Results of T-tests and ANOVA tests.
- **`Correlation Analysis.csv`**: Matrix showing relationships between usage time and mental health.
- **`Linear Regression.csv`**: Statistical modeling predicting stress levels based on social media hours.

---

## Data Cleaning
- **Missing Values:** The dataset contains zero (0) missing values.
- **Outliers:** No severe outliers were found in quantitative variables (Age, GPA, Social Media Hours, etc.).
- **Data Quality:** The data is highly consistent and required no row removal before analysis.

---

## Statistical Summary
*Based on the 1,200 participants:*
- **Average Age:** 15.9 years.
- **Daily Social Media Usage:** 4.54 hours per day.
- **Sleep:** Average of 6.45 hours per night.
- **Academic Performance:** Average GPA of 2.99.
- **Stress & Anxiety:** Mean levels are 5.45 and 5.64 respectively (on a scale of 1-10).

---

## Analysis and Key Findings

### 1. Hypothesis Testing
- **Anxiety by Gender:** A Two-Sample T-test was conducted to determine if anxiety levels differ between male and female students.
- **Stress vs. Social Interaction:** An ANOVA (Single Factor) test was performed to determine if stress levels vary based on social interaction levels (Low, Medium, High).

### 2. Correlation & Regression
- **Social Media vs. Stress:** Linear regression analysis was applied to test the predictive power of social media hours on stress levels.
- **Platform Usage:** Instagram was identified as the most frequent (modal) platform used among the surveyed teenagers.

### 3. Key Visual Insights
- **Academic Performance:** Box plots confirm that the middle 50% of students fall within a narrow range around the 2.99 median.
- **Sleep Trends:** Females reported a slightly higher average sleep duration (6.50 hours) compared to males (6.40 hours).

---

## How to Use
1. Refer to the **Data Dictionary** for variable definitions.
2. Use the **Cleaned Dataset** for further modeling or visualization in Python/R.
3. Review the **Hypothesis Testing** file for detailed p-values and statistical significance results.
