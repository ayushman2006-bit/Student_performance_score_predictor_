Student Performance Score Predictor

A Machine Learning project that predicts a student's **final examination score** based on academic and demographic factors such as study hours, attendance, previous scores, assignments, age, gender, and extracurricular activities.

---

Project Overview

Educational institutions generate a large amount of academic data every year. This project demonstrates how Machine Learning can be used to analyze student information and predict their final examination scores.

The project performs:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training
* Model Evaluation
* Feature Importance Analysis
* Model Serialization using Pickle

Three regression algorithms are implemented and compared to determine the best-performing model.

---

Features

* Exploratory Data Analysis (EDA)
* Correlation Heatmap
* Histograms and Distribution Plots
* Scatter Plots
* Box Plots
* Label Encoding for Categorical Features
* Multiple Machine Learning Models
* Model Performance Comparison
* Save Trained Model using Pickle

---

Dataset

The dataset contains student information with the following attributes:

| Feature         | Description                                 |
| --------------- | ------------------------------------------- |
| Student_ID      | Unique Student Identifier                   |
| Gender          | Male / Female                               |
| Age             | Student Age                                 |
| Study_Hours     | Hours Spent Studying                        |
| Attendance      | Attendance Percentage                       |
| Previous_Score  | Previous Examination Score                  |
| Assignments     | Assignment Marks                            |
| Extracurricular | Participation in Extracurricular Activities |
| Final_Score     | Target Variable                             |
| Pass            | Pass/Fail Status                            |

---
Technologies Used

* Python 3
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Pickle

---

Exploratory Data Analysis

The notebook includes:

* Dataset Information
* Missing Value Analysis
* Duplicate Value Check
* Descriptive Statistics
* Correlation Matrix
* Heatmap
* Histograms
* Scatter Plots
* Box Plots
* Count Plots

---

 Machine Learning Models

The following regression models were trained and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

---

Evaluation Metrics

Model performance is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

Future Improvements

* Deploy the model using Streamlit or Flask
* Increase dataset size
* Hyperparameter tuning
* Cross-validation
* Add more student-related features
* Integrate deep learning models

---

Sample Output

The project generates:

* Correlation Heatmap
* Feature Importance Plot
* Model Evaluation Metrics
* Predicted Student Scores


#Author

Ayushman Pyne

B.Tech CSE (Data Science)

University of Engineering & Management (UEM), Kolkata

---

If you found this project useful

Please consider giving this repository a Star on GitHub!
