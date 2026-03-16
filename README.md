# Practical_6-7

# Practical 6_7 – Data Analytics Implementation

## Student Details

Name: Shreyas Kapadiya
Enrollment No: 2054070500002
Course: Data Analytics Techniques (DAT)
Practical: 6_7

## Overview

This project focuses on performing **data storage, integration, and pattern analysis** on a dataset that studies the relationship between **mobile usage habits, sleep duration, and stress levels**.

The analysis was implemented using **Python in Google Colab** along with several data science libraries.

## Dataset Information

Dataset File: `sleep_mobile_stress_dataset_15000.csv`

### Available Attributes

The dataset contains the following variables:

- user_id
- age
- gender
- occupation
- daily_screen_time_hours
- phone_usage_before_sleep_minutes
- sleep_duration_hours
- sleep_quality_score
- stress_level
- caffeine_intake_cups
- physical_activity_minutes
- notifications_received_per_day
- mental_fatigue_score

These features allow us to analyze behavioral patterns and lifestyle factors affecting stress and sleep.

## Technologies Used

The following tools and libraries were used for the implementation:

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SQLite Database

## Workflow

### 1. Data Storage

The dataset was saved in multiple formats to support easy access and management:

- CSV file format
- Excel file format
- SQLite database

Storing the dataset in different formats ensures better data handling and accessibility for analysis.

### 2. Data Integration

To enhance the analysis, several new features were created by combining existing attributes:

Digital Behavior Index
Represents overall mobile usage behavior by combining:

- Daily screen time
- Phone usage before sleeping
- Number of notifications received

Lifestyle Score
Created using:

- Sleep duration
- Physical activity levels

Stress Risk Score
Calculated using:

- Stress level
- Mental fatigue score
- Digital behavior index

These integrated features help in understanding user behavior more effectively.

### 3. Pattern Discovery

Different analytical methods were applied to identify patterns in the dataset.

#### Correlation Analysis

A correlation heatmap was generated to examine relationships between different variables, such as:

- Screen time and stress level
- Sleep duration and mental fatigue

This helped identify strong relationships among the variables.

#### Clustering Using K-Means

K-Means clustering was used to group users with similar behavioral characteristics based on:

- Screen time
- Sleep duration
- Stress level
- Physical activity

This method allowed the identification of different lifestyle patterns among users.

## Key Findings

- Users with **higher screen time** tend to show **greater stress and mental fatigue**.
- **Reduced sleep duration** is associated with **increased fatigue levels**.
- K-Means clustering successfully categorized users into different **behavioral groups**.

## Final Outcome

This practical demonstrates how **data storage techniques, feature integration, and pattern discovery methods** can be applied to real-world datasets to gain insights into behavioral trends related to mobile usage and health.

## Project Structure

Practical-6-7
│
├── sleep_mobile_stress_dataset_15000.csv
├── practical_6_7_colab.ipynb
└── README.md

## Summary

The project illustrates a complete **data analytics pipeline**, starting from storing and preparing data to discovering hidden patterns using statistical analysis and clustering techniques.
