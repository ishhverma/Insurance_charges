# Insurance Charges Prediction
This project predicts health insurance charges using a **Linear Regression** model.  
The dataset contains information about individuals and their insurance costs.  
The goal is to estimate how factors like age, BMI, smoking status, and region affect insurance charges.

## 📁 Dataset
The dataset used is `insurance.csv`, which contains 1338 records and 7 features:
| Column   | Type      | Description |
|----------|-----------|-------------|
| age      | numeric   | Age of primary beneficiary |
| sex      | categorical | Gender of the beneficiary (male/female) |
| bmi      | numeric   | Body Mass Index |
| children | numeric   | Number of children covered by insurance |
| smoker   | categorical | Whether the beneficiary is a smoker (yes/no) |
| region   | categorical | Residential area in the US |
| charges  | numeric   | Individual medical costs billed by health insurance |

## 📌 Objective
Predict the insurance charges (`charges`) using features like:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region

## 🧠 Model Used
### Linear Regression
A simple yet effective algorithm to model the relationship between the target variable (`charges`) and the input features.

## 📈 Model Performanc
The model achieves:
| Metric | Value |
|--------|-------|
| R² (Training) | 0.742 |
| Mean Squared Error (Training) | 37,277,681 |
| Mean Squared Error (Test) | 33,596,915 |
The model shows good generalization and captures the most significant feature (**smoking**) accurately.

## 🔍 Key Insights
- **Smoking status has the highest impact** on insurance charges.
- Other features like age, BMI, and number of children also contribute but to a lesser extent.
- The model is stable and not overfitting, as the training and test MSE values are similar.
