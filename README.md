# Student Data Analysis

This project explores a dataset of student records to uncover insights into academic performance, career aspirations, and other related metrics. By cleaning and organizing the data, we derived meaningful insights and created new features to make the data more actionable.

## Project Overview
The analysis focused on:
- Data cleaning and handling missing values
- Segmenting student information and academic scores for targeted analysis
- Creating new features, such as Total Score and categorized score levels
- Exploring performance trends by career aspirations and gender

## Key Findings
- **Top Performers by Career Aspiration**: Identified the top 3 students within each career aspiration based on total score, providing insights into high achievers for each field.
- **Score Categories**: Created `High`, `Mid`, and `Low` score categories to simplify interpretation of student performance.
- **Gender & Career Aspiration Analysis**: Applied a pivot to evaluate total scores by gender and career aspiration, revealing performance trends across career goals.

## Data Cleaning
- Handled missing values by imputing categorical data with the mode and numeric data with the mean.
- Converted score columns to integer type for consistency.
- Segmented data into **Student Information** (demographics and career aspiration) and **Student Scores** (subject-specific scores).

## New Features Created
1. **Total Score**: Calculated total academic score for each student across all subjects.
2. **Score Category**: Classified each student’s total score into `High`, `Mid`, or `Low` categories for easier insights.
3. **Top Performers by Career Aspiration**: Ranked students by total score within each career aspiration to highlight top achievers.
4. **Gender-based Analysis**: Pivoted data to analyze total scores by gender and career aspiration.

## Analysis Process
1. **Data Loading**: Loaded the dataset and performed initial exploration.
2. **Data Cleaning**: Addressed missing values, converted data types, and split data into relevant segments.
3. **Feature Engineering**: Created `Total Score` and categorized performance levels.
4. **Insight Generation**: Ranked top students by career aspiration, categorized scores, and applied a pivot for gender and career analysis.
