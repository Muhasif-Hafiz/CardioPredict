# CardioPredict – Heart Disease Prediction System


<img width="772" height="746" alt="image" src="https://github.com/user-attachments/assets/1aff5f49-5a26-491e-b164-111761df3663" />


## Overview

CardioPredict is a machine learning-based project designed to predict the likelihood of heart disease using patient health-related attributes.

The project uses supervised machine learning classification algorithms to analyze patient data and identify patterns associated with heart disease. Multiple classification models were implemented and evaluated to determine which model performs best.

After comparing the performance of different models, **Logistic Regression achieved the best overall performance** on the evaluation dataset. Therefore, it was selected as the final model for the prediction system.

## Project Objectives

- Analyze patient health data to identify patterns associated with heart disease.
- Implement and compare multiple supervised classification algorithms.
- Evaluate model performance using accuracy and F1-score.
- Select the best-performing classification model.
- Build an interactive web application using Streamlit.

## Machine Learning Models Implemented

The following classification algorithms were implemented and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Decision Tree Classifier
5. Random Forest Classifier
6. Naive Bayes

## Model Selection

All the implemented models were trained and evaluated using the same training and testing datasets.

The performance of each model was compared using:

- Accuracy Score
- F1-Score

Based on the evaluation results, Logistic Regression demonstrated the best overall performance. Consequently, it was selected as the final model and used for the prediction application.

## Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning model development and evaluation
- **Streamlit** – Web application development

## Project Structure

```text
CardioPredict/
│
├── frontend/
│   └── app.py
│
├── models/
│   └── logistic_regression_model.pkl
│
├── dataset/
│   └── heart.csv
│
├── notebooks/
│   └── model_training.ipynb
│
├── requirements.txt
│
└── README.md
```

*Note: The structure above is a suggested layout. Adjust the filenames and folders according to your actual project.*

## Installation and Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd CardioPredict
```

### 3. Create a Virtual Environment

```bash
python3 -m venv venv
```

### 4. Activate the Virtual Environment

For macOS/Linux:

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Streamlit Application

```bash
streamlit run frontend/app.py
```

The application will be available at:

```text
http://localhost:8501
```

## Evaluation Metrics

The models were evaluated using accuracy and F1-score to understand their classification performance.

Logistic Regression was selected based on the comparative evaluation results.

## Disclaimer

CardioPredict is an educational machine learning project developed for learning and demonstration purposes. It is not a substitute for professional medical advice, clinical diagnosis, or treatment. Predictions should not be used to make medical decisions.

## Author

Developed as a machine learning project focused on supervised classification and predictive analytics.
