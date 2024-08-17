# 📝 Stack Overflow Survey Analysis

## Project Overview

This project involves analyzing the Stack Overflow Developer Survey data using Python. The primary goal is to extract insights about the survey respondents, focusing on aspects like remote work, programming languages, experience, and salary distribution. The analysis answers several specific questions about the dataset.

## 🔍 Analysis Breakdown

### 1. Survey Completion
- **Objective:** Determine how many respondents completed the survey.
- **Result:** Number of Respondents: 89184

### 2. Full Responses
- **Objective:** Find out how many respondents answered all questions.
- **Result:** Number of respondents who answered all questions: 0

### 3. Central Tendency of Experience
- **Objective:** Calculate central tendency measures (mean, median, mode) for the work experience (WorkExp) of respondents.
- **Result:** Mean respondents work experience: 11.41
              Median respondents work experience: 9.0

### 4. Remote Work
- **Objective:** Count how many respondents work remotely.
- **Result:** Respondents working remotely: 30566

### 5. Python Programmers
- **Objective:** Determine what percentage of respondents program in Python.
- **Result:** Share of respondents coding in Python: 48.39%

### 6. Learning via Online Courses
- **Objective:** Find out how many respondents learned to program through online courses.
- **Result:** Number of respondents who learned coding online: 70084

### 7. Salary Analysis
- **Objective:** Compute the average and median salary (ConvertedCompYearly) by country among respondents who program in Python.
- **Result:**
    | Country | Mean Salary | Median Salary |
    |---------|-------------|---------------|
    | Afghanistan | 665.00 | 48.0 |
    | Albania | 28008.60 | 11844.0 |
    | Algeria | 8336.33 | 6586.0 |
    | Andorra | 32127.00 | 32127.0 |
    | Angola | 662.00 | 662.0 |
    | ...     | ...     | ...   |
    | Venezuela, Bolivarian Republic of... | 24973.53 | 12000.0 |
    | Viet Nam | 20191.87 | 13401.0 |
    | Yemen | 8373.00 | 9000.0 |
    | Zambia | 13051.00 | 9687.0 |
    | Zimbabwe | 5600.00 | 6000.0 |
    
    *[173 rows x 2 columns]*

### 8. Education Level of Top Earners
- **Objective:** Identify the education level of the 5 respondents with the highest salary.
- **Result:**
    | ConvertedCompYearly | EdLevel |
    |---------------------|---------|
    | 74351432.0 | Professional degree (JD, MD, Ph.D, Ed.D, etc.) |
    | 73607918.0 | Professional degree (JD, MD, Ph.D, Ed.D, etc.) |
    | 72714292.0 | Bachelor’s degree (B.A., B.S., B.Eng., etc.) |
    | 57513831.0 | Primary/elementary school |
    | 36573181.0 | Professional degree (JD, MD, Ph.D, Ed.D, etc.) |

### 9. Python Programming by Age Group
- **Objective:** Calculate the percentage of respondents who program in Python within each age group.
- **Result:** 
    | Age | Coding in Python |
    |-----|------------------|
    | 18-24 years old | 12.34% |
    | 25-34 years old | 17.74% |
    | 35-44 years old | 9.54% |
    | 45-54 years old | 3.59% |
    | 55-64 years old | 1.39% |
    | 65 years or older | 0.41% |
    | Prefer not to say | 0.21% |
    | Under 18 years old | 3.18% |

### 10. Industry Analysis for High Earners
- **Objective:** Determine the industries most likely to employ respondents in the 75th percentile of median salary who work remotely.
- **Result:**
    ```
    MainBranch
    I am a developer by profession                                                           6554
    I am not primarily a developer, but I write code sometimes as part of my work/studies     368
    ```

## 🚀 Results
- Identified the most efficient campaigns and ad sets with the highest ROMI.
- Compared the performance of campaigns across different months to identify trends.
- Segmented campaign performance by media source, campaign, and ad set, highlighting areas for optimization in future campaigns.

## 📂 Project Structure

- `survey_analysis.py`: The Python script containing the full analysis code.
- `README.md`: This file, providing an overview of the project.

## 🔧 Tools Used

- **Python:** The primary programming language used for data analysis.
- **Pandas:** For data manipulation and analysis.
- **Matplotlib/Seaborn:** For data visualization.
- **Jupyter Notebook:** For an interactive development environment.

## 📊 Dataset

The dataset used in this project is the Stack Overflow Developer Survey. It contains responses from thousands of developers around the world, providing insights into various aspects of the software development industry.
