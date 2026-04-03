🩺 Multiple Disease Prediction System
A Machine Learning based web application that predicts the likelihood of multiple diseases using medical input parameters.
The system integrates multiple ML models into a single user-friendly interface, allowing users to check disease predictions quickly and efficiently.

📌 Project Overview
Many existing healthcare prediction systems focus on predicting only one disease at a time. Users must visit different platforms for different predictions.
This project solves that problem by providing a single web application capable of predicting multiple diseases, including:
Diabetes
Heart Disease
Parkinson’s Disease
The application is built using Python and Streamlit, and trained machine learning models are used to generate predictions based on user inputs.

✨ Features
✔ Predicts multiple diseases in one platform
✔ Simple and user-friendly interface
✔ Fast prediction results
✔ Machine learning based analysis
✔ Interactive web application

🦠 Diseases Predicted
1️⃣ Diabetes Prediction
Uses medical parameters such as:
Glucose level
Blood pressure
BMI
Insulin level
2️⃣ Heart Disease Prediction
Uses attributes such as:
Age
Cholesterol
Resting blood pressure
Maximum heart rate
3️⃣ Parkinson's Disease Prediction
Uses voice measurement features such as:
Jitter
Shimmer
Harmonicity

🧠 Machine Learning Algorithms Used

🔹 Support Vector Machine (SVM)
Support Vector Machine is a supervised machine learning algorithm used for classification tasks.
It finds the optimal boundary that separates data into different classes.

🔹 Logistic Regression
Logistic Regression predicts the probability of a categorical outcome and is widely used for medical prediction tasks.

🏗️ System Architecture
flowchart TD
A[User Input] --> B[Streamlit Web Interface]
B --> C[Data Preprocessing]
C --> D[Machine Learning Models]
D --> E[Prediction Result]
E --> F[Display Result to User]

The workflow of the system:
User enters medical parameters.
Data is processed.
Input is passed to trained ML models.
Prediction is generated.
Result is displayed on the web interface.
