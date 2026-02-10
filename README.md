## Salary Prediction using Multiple Linear Regression

### Project Overview

This project predicts an employee’s salary based on different features such as experience, education, and other factors using Multiple Linear Regression.
It demonstrates the complete machine learning workflow from data loading to model evaluation.

---

### Objective

The main goals of this project are:

* To understand how salary prediction works using regression
* To build a Multiple Linear Regression model
* To evaluate model performance using standard metrics

---

### Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib (for visualization)

---

### Dataset

The dataset contains information about employees, including:

Example features:

* Years of Experience
* Education Level
* Age
* Job Role (optional)

Target variable:

* Salary

---

### Machine Learning Workflow

1. Import required libraries
2. Load the dataset
3. Explore and clean the data
4. Convert categorical data (if any)
5. Split data into training and testing sets
6. Train the Multiple Linear Regression model
7. Make predictions
8. Evaluate the model

---

### Model Evaluation

The model is evaluated using:

* Mean Squared Error (MSE) – measures prediction error
* R² Score – shows how well the model explains the data

Example output:

Mean Squared Error: 2.39e-29
R2 Score: 1.0

---

### Project Structure

salary-prediction/
│
├── salary_dataset.csv
├── salary_prediction.py
├── README.md

---

### How to Run the Project

1. Install required libraries:
   pip install pandas numpy scikit-learn matplotlib

2. Run the script:
   python salary_prediction.py

---

### What I Learned

* Concept of regression in machine learning
* Data preprocessing techniques
* Model training and testing
* Performance evaluation using metrics

---

### Future Improvements

* Use a larger real-world dataset
* Apply advanced regression models
* Add feature engineering
* Deploy the model as a web app

