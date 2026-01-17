# Project Title 
Jamboree Education – Linear Regression Project

## Project Context
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

## Problem Statement
The objective of this project is to build a Linear Regression model to help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels

## Setup Instructions

Follow these steps to set up the project environment and run it locally.

```bash
### 1 Clone the Repository
git clone https://github.com/Aravind-91/JamboreeEducation--LinearRegression
cd JamboreeEducation-LinearRegression

### 2 Create & Activate Virtual Environment
python -m venv venv
.\venv\Scripts\Activate.ps1

If you see a script execution error, run:
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

### 3 Install Dependencies
pip install -r requirements.txt

```

### Data Overview
Source : Scaler
Size of Data : (500, 9)
Column Profiling :
    1. Serial No. (Unique row ID)
    2. GRE Scores (out of 340)
    3. TOEFL Scores (out of 120)
    4. University Rating (out of 5)
    5. Statement of Purpose and Letter of Recommendation Strength (out of 5)
    6. Undergraduate GPA (out of 10)
    7. Research Experience (either 0 or 1)
    8. Chance of Admit (ranging from 0 to 1)

### Concepts Used:
    1. Exploratory Data Analysis
    2. Linear Regression



