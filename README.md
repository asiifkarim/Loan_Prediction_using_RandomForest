# **`Loan Prediction Project`**

## **About Dataset**
### `Loan Prediction Dataset`
This dataset contains information about individuals applying for loans, including their financial and personal details. The dataset is designed to help predict whether an applicant is likely to default on a loan (indicated by the "Risk_Flag" column). The dataset includes 1,404 entries with 13 features, providing a comprehensive view of each applicant's profile.

**Features:**
- `Id`: Unique identifier for each applicant.
- `Income`: Annual income of the applicant.
- `Age`: Age of the applicant.
- `Experience`: Number of years of professional experience.
- `Married/Single`: Marital status of the applicant (married or single).
- `House_Ownership`: Housing status of the applicant (e.g., rented, owned, or no rent/no own).
- `Car_Ownership`: Whether the applicant owns a car (yes or no).
- `Profession`: The profession of the applicant (e.g., Software Developer, Mechanical Engineer, etc.).
- `CITY`: The city where the applicant resides.
- `STATE`: The state where the applicant resides.
- `CURRENT_JOB_YRS`: Number of years in the current job.
- `CURRENT_HOUSE_YRS`: Number of years in the current residence.
- `Risk_Flag`: Binary flag indicating whether the applicant is at risk of defaulting on the loan (1 = high risk, 0 = low risk).

**Key Insights:**
- The dataset includes a diverse range of professions, income levels, and geographic locations, making it suitable for building predictive models for loan default risk.
- The "Risk_Flag" column is the target variable, which can be used to train machine learning models for classification tasks.
- Features like income, age, experience, and housing status may play a significant role in determining the likelihood of loan default.

**Potential Use Cases:**
- **Loan Default Prediction:** Build machine learning models to predict whether an applicant is likely to default on a loan.
- **Risk Assessment:** Analyze the factors that contribute to loan default risk.
- **Customer Segmentation:** Segment applicants based on their financial and personal profiles for targeted marketing or risk management.

**Dataset Source:**
The dataset is synthetic and designed for educational purposes, making it ideal for practicing data analysis, feature engineering, and machine learning model building.

**License:**
This dataset is publicly available for educational and non-commercial use.

--
## 1. Importing Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns


## 2. Loading Dataset
The dataset is loaded using pandas and initial exploration includes viewing the first few rows and descriptive statistics.

---

## Project Workflow Overview
- **Data Loading:** Read and inspect the dataset.
- **Data Cleaning:** Handle missing values and inconsistencies.
- **Feature Engineering:** Encode categorical variables and create new features if necessary.
- **Exploratory Data Analysis (EDA):** Visualize distributions and relationships.
- **Model Building:** Train machine learning models to predict loan default risk.
- **Model Evaluation:** Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.

---

## How to Use
1. Clone or download the project files.
2. Install required Python libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Run the notebook cells sequentially to perform data analysis and model training.
4. Modify or extend the notebook to experiment with different models or features.

---




