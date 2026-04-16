# Lung Cancer AI Diagnostic Engine 🩺

## Project Overview
This project is a clinical decision-support tool designed to predict the probability of lung cancer based on 16 clinical features and patient habits. It combines a robust Machine Learning backend with a modern Graphical User Interface (GUI) built using `CustomTkinter`.

## Aim of the Project
The primary goal is to provide a reliable, data-driven diagnostic aid that helps healthcare professionals assess lung cancer risk levels quickly. The project emphasizes both model accuracy and user accessibility.

## Dataset & Features
The model is trained on a lung cancer dataset containing various clinical attributes:
- **Demographics:** Age, Gender.
- **Habits:** Smoking, Alcohol consumption, Smoking pack-years.
- **Clinical Symptoms:** Coughing, Shortness of breath, Wheezing, Chest pain, Swallowing difficulty, Fatigue, Allergy.
- **Pre-existing Conditions:** Chronic disease, Anxiety, Peer pressure, Yellow fingers.

## Data Preprocessing
- **Feature Encoding:** Categorical variables (like Gender and Symptoms) were transformed using `LabelEncoder` to ensure compatibility with the machine learning algorithm.
- **Data Cleaning:** Column names were stripped of extra spaces, and numerical features were normalized to ensure consistent model performance.

## Machine Learning Model
- **Algorithm:** Random Forest Classifier (an ensemble learning method).
- **Rationale:** Chosen for its high accuracy, ability to handle non-linear relationships, and robustness against overfitting.
- **Configuration:** 100 estimators with a fixed `random_state` for reproducibility.

## How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Mustafayarub/Lung-Cancer-AI-Diagnosis-App.git](https://github.com/Mustafayarub/Lung-Cancer-AI-Diagnosis-App.git)
