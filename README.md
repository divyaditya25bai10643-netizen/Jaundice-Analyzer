🩺 Jaundice Prediction Program
📌 Overview

This project presents a Python-based machine learning application designed to predict the likelihood of jaundice using key clinical symptoms and patient data. The system employs a Random Forest classifier trained on a structured dataset to analyze inputs such as bilirubin levels, physical symptoms, and patient age, and provides both a prediction and an associated risk percentage.

🎯 Objective

The objective of this project is to demonstrate the application of machine learning techniques in the healthcare domain for early detection and decision support, while highlighting the importance of symptom-based analysis.

⚙️ Features
User-friendly input system for entering patient symptoms
Prediction of jaundice presence using a trained ML model
Risk percentage estimation based on probability scores
Display of key symptoms contributing to the prediction
Advisory message encouraging medical consultation
🧪 Technologies Used
Python 3
scikit-learn (Random Forest Classifier)
NumPy
Pandas
▶️ How to Run
Ensure Python 3 is installed on your system

Install required libraries:

pip install scikit-learn numpy pandas

Run the program:

python projectman.py
Enter patient details as prompted
📥 Input Parameters
Bilirubin Level (0 = Normal, 1 = High)
Yellow Eyes (0 = No, 1 = Yes)
Yellow Skin (0 = No, 1 = Yes)
Age (Integer value)
Dark Urine (0 = No, 1 = Yes)
Fatigue (0 = No, 1 = Yes)
Abdominal Pain (0 = No, 1 = Yes)
📤 Output
Prediction: Jaundice Detected / Not Detected
Risk Percentage (0%–100%)
Identified Symptoms
Medical advisory message
🧠 Working Principle

The model is trained on a synthetic dataset containing labeled examples of jaundice and non-jaundice cases. A Random Forest algorithm is used to learn patterns between symptoms and diagnosis. When new input is provided, the model predicts the outcome and calculates the probability to estimate risk.

⚠️ Disclaimer

This project is developed for educational purposes only and is not intended for real-world medical diagnosis. Users are strongly advised to consult qualified healthcare professionals for accurate medical evaluation.
