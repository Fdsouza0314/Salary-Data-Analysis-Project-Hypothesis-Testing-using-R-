# Salary-Data-Analysis-Project-Hypothesis-Testing-using-R-
Salary Data Analysis Project  This project demonstrates a complete analysis of a sample salary dataset using R, RStudio, and the tidyverse suite of packages, including readxl and dplyr. The goal was to explore the dataset, summarize key statistics, and perform hypothesis testing on salaries.


Project Overview

This project is all about exploring and analyzing a sample salary dataset using R and RStudio. By leveraging the tidyverse packages, including readxl and dplyr, the goal is to understand the data, summarize important statistics, and use hypothesis testing to uncover insights about salary distributions.

What This Project Does: Data Import & Exploration

Reads Excel data with read_excel() from the readxl package.

Checks the structure of the dataset using str() and gets a quick statistical summary with summary().


Data Analysis:

Counts the number of males and females using group_by() and summarise().

Calculates the proportion of males versus females in the dataset.

Computes the overall average salary and tests whether it differs from a benchmark value ($90,000) using a one-sample t-test.


Hypothesis Testing:

Overall Salary Test

Null hypothesis (H0): The population mean salary = $90,000

Alternative hypothesis (H1): The population mean salary ≠ $90,000

Determines significance using p-values and confidence intervals.

Gender-Based Salary Test

Null hypothesis (H0): The average salary for males = the average salary for females

Alternative hypothesis (H1): The average salary for males ≠ the average salary for females

Uses an independent t-test to see if salary differences between genders are statistically significant.

Outputs

An R Markdown file (.Rmd) showing all the analysis steps.

A Word document (.docx) generated from the R Markdown file for submission or sharing.


Tools & Packages:

R & RStudio – Main environment for coding and analysis

tidyverse – For data wrangling and visualization (dplyr, etc.)

readxl – For reading Excel files

Base R – For statistical calculations and hypothesis testing (t.test, mean, sd)


Key Insights:

Provides descriptive statistics for salaries and gender distribution.

Shows how hypothesis testing can be applied to real-world salary data.

Offers clear interpretation of results to inform decisions about salary differences.
