# Diabetes Prediction using Logistic Regression

This project uses Machine Learning to predict whether a person has diabetes based on medical data.
The model is built using **Logistic Regression**, a classification algorithm used for binary outcomes.

The project also includes visualization of the **Logistic Regression S-shaped (sigmoid) curve**, which shows how prediction probability changes with input features.

---

## Dataset

The dataset used in this project is **diabetes.csv**.
It contains medical data collected from patients.

Features in the dataset:

* Pregnancies – Number of pregnancies
* Glucose – Plasma glucose concentration
* BloodPressure – Blood pressure level
* SkinThickness – Skin fold thickness
* Insulin – Insulin level in blood
* BMI – Body Mass Index
* DiabetesPedigreeFunction – Diabetes family history score
* Age – Age of the patient
* Outcome – Target variable

Target variable meaning:

* 0 → No Diabetes
* 1 → Diabetes

---

## Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

---

## Machine Learning Model

The model used in this project is **Logistic Regression**.

Logistic Regression is used when the output variable is categorical.
It predicts the **probability of belonging to a class (0 or 1)** using a **sigmoid function**.

---

## Project Workflow

1. Import required libraries
2. Load the dataset using Pandas
3. Explore dataset structure using head(), info(), and describe()
4. Separate input features and target variable
5. Split the dataset into training and testing data
6. Normalize the data using StandardScaler
7. Train the Logistic Regression model
8. Predict diabetes outcomes
9. Evaluate the model using accuracy score and confusion matrix
10. Plot the Logistic Regression S-curve

---

## Model Evaluation

The model performance is evaluated using:

Accuracy Score – Measures overall correctness of predictions

Confusion Matrix – Shows:

* True Positive
* True Negative
* False Positive
* False Negative

---

## Visualization

The project includes visualization such as:

* Regression probability curve
* Logistic sigmoid S-curve
* Model prediction distribution

These graphs help understand how the model makes predictions.

---

## How to Run the Project

Step 1 – Install required libraries

pip install pandas numpy matplotlib seaborn scikit-learn

Step 2 – Download the dataset and place it in the project folder

diabetes.csv

Step 3 – Run the notebook or python script

python diabetes_prediction.py

or open the Jupyter Notebook file.

---

## Project Structure

Diabetes-Prediction-Logistic-Regression

│

├── diabetes.csv
├── diabetes_prediction.ipynb
├── README.md

---

## Learning Outcomes

From this project you can learn:

* Data preprocessing
* Binary classification
* Logistic Regression
* Model evaluation
* Confusion Matrix interpretation
* Machine Learning visualization

---

## Author

Vinay Mohan

Machine Learning Student
