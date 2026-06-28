# PR2_Maths

# PR.-2-Derivable-Judgement-Statistical-Decision-Making-Model

## Derivable Judgement: A Statistical Decision-Making Model

### Project Overview

This project focuses on applying inferential statistics to analyze a public health dataset. The objective is to evaluate multiple hypotheses and derive statistical conclusions using various hypothesis testing techniques. The analysis includes confidence intervals, critical values, p-values, Independent t-Test, Chi-Square Test, One-Way ANOVA, covariance, and correlation to identify significant relationships among health-related variables.

---

## Project Objectives

* Understand the concepts of inferential statistics.
* Formulate statistical hypotheses.
* Calculate confidence intervals for numerical variables.
* Perform hypothesis testing using statistical methods.
* Interpret p-values and critical values.
* Analyze relationships between health variables.
* Draw meaningful conclusions from statistical analysis.

---

## Dataset Description

The dataset contains **500 health records** with information related to individuals from different regions.

### Features

| Column             | Description             |
| ------------------ | ----------------------- |
| record_id          | Unique identifier       |
| age_group          | Age category            |
| age                | Age of individual       |
| weight             | Weight of individual    |
| gender             | Gender                  |
| region             | Geographic region       |
| smoking_status     | Smoking habit           |
| exercise_frequency | Exercise frequency      |
| bmi                | Body Mass Index         |
| blood_pressure     | Systolic blood pressure |
| diabetes           | Diabetes status         |
| hypertension       | Hypertension status     |
| cholesterol_level  | Cholesterol level       |
| glucose_level      | Fasting glucose level   |
| visit_date         | Health check-up date    |

---

## Statistical Techniques Used

* Confidence Interval
* Critical Value
* p-value
* Independent t-Test
* Chi-Square Test
* One-Way ANOVA
* Covariance
* Correlation Analysis

---

## Hypotheses

### Hypothesis 1

**H₀:** Smoking status and diabetes occurrence are independent.

**H₁:** Smoking status and diabetes occurrence are dependent.

### Hypothesis 2

**H₀:** The mean glucose level is the same for all age groups.

**H₁:** At least one age group has a different mean glucose level.

---

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Explore and inspect the dataset.
4. Calculate confidence intervals.
5. Perform Independent t-Test.
6. Perform Chi-Square Test.
7. Perform One-Way ANOVA.
8. Calculate covariance and correlation.
9. Visualize results using charts.
10. Interpret statistical findings.

---

## Libraries Used

* NumPy
* Pandas
* Matplotlib
* SciPy

---

## Visualizations

The project includes the following visualizations:

* Histogram of Age Distribution
* Box Plot of BMI by Diabetes Status
* Bar Chart of Smoking Status vs Diabetes
* Box Plot of Glucose Level by Age Group
* Scatter Plot showing the relationship between Age and BMI

---

## Results Summary

* Confidence intervals were calculated for important numerical variables.
* The Independent t-Test indicated a significant difference in mean BMI between diabetic and non-diabetic individuals.
* The Chi-Square Test showed no significant association between smoking status and diabetes occurrence.
* The One-Way ANOVA found no significant difference in mean glucose levels among different age groups.
* Covariance and correlation analysis indicated a very weak positive relationship between age and BMI.

---

## Project Structure

```
PR.-2-Derivable-Judgement-Statistical-Decision-Making-Model/
│
├── Derivable_Judgement.ipynb
├── Health_Dataset.csv
├── Theory.pdf
├── README.md
└── Images/
```

---

## Conclusion

This project demonstrates the practical application of inferential statistics in public health data analysis. Various statistical techniques were used to test hypotheses, estimate population parameters, and evaluate relationships among health variables. The results support informed decision-making through statistical evidence and provide a clear understanding of the factors analyzed.

---

## Author

 Devanshi Kanthariya

