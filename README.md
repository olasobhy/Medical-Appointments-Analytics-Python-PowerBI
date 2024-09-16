# Medical-Appointments-Python-PowerBI
## Overview
This project aims to analysis and predict appointment no-shows using a dataset of medical appointments. The dataset includes information such as the scheduled day, appointment day, and various patient features. The goal is to analyze the data, perform preprocessing, and apply machine learning models to predict whether a patient will show up for their appointment.

## Usage
### Python Notebook

- **Data Preprocessing**:
  1.Convert date columns to datetime forma
  2.Calculate the duration between scheduled and appointment days
  3.rename the some columns to valid names
  4.Map categorical values to numerical values
  
- **Exploratory Data Analysis (EDA)**: Analyze the dataset to uncover patterns and trends related to patient no-shows.
- **Handling Imbalanced Classes**: Applied **SMOTE** to address class imbalance and improve model performance.
- **Predictive Modeling**:
  - **Models Used**: I used **RandomForestClassifier** to predict appointment no-shows.
  - **Evaluation**: Models are evaluated using metrics like accuracy, precision, recall, and F1 score.

## Power BI Report

- I visualize the data to reveal insights.
  <br>
## Insights:
-The number of female appointments is almost double that of male appointments.
<br>
-Tuesday has the highest number of scheduled appointments.
<br>
-Wednesday has the highest number of actual appointments.
<br>
-Saturday has a very small number of both appointments and scheduled appointments.
<br>
-75% of people do not receive any SMS reminders, which impacts appointment attendance.
<br>
-The duration between scheduling and the appointment has a significant effect,
longer durations are associated with higher no-show rates.
<br>
img.png

