# Titanic Survival Prediction

Titanic Survival Prediction is a machine learning project that predicts whether a passenger survived or not based on various features like age, class, gender, and other attributes. This project demonstrates the use of machine learning models for classification tasks, specifically applied to the Titanic dataset.

## Features

- Data preprocessing and feature engineering for Titanic survival prediction.
- Utilizes machine learning algorithms for classification.
- Provides performance metrics for model evaluation.
- Simple and interactive user interface using Streamlit for prediction.

## Dataset

The dataset used is the **Titanic dataset** from Kaggle, which includes information about passengers, such as their age, class, sex, and whether they survived the Titanic disaster.

## Prerequisites

Before running the Titanic Survival Prediction project, ensure you have the following installed:

1. **Python** (>=3.8)
2. **Streamlit** (`pip install streamlit`)
3. **Pandas** (`pip install pandas`)
4. **NumPy** (`pip install numpy`)
5. **Scikit-Learn** (`pip install scikit-learn`)
6. **Matplotlib** (`pip install matplotlib`)
7. **Seaborn** (`pip install seaborn`)

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/abhimanyu726/Titanic_survival_prediction.git
    cd Titanic_survival_prediction
2. **Install the Dependencies**
Install the dependencies using pip:

    ```bash
    pip install -r requirements.txt
## Usage
1. **Run the Jupyter Notebook**
Open and run the Jupyter notebook titanic_survival_prediction.ipynb for data exploration, model training, and evaluation.

    ```bash
    jupyter notebook titanic_survival_prediction.ipynb
2. **Streamlit Interface**
For an interactive web-based prediction tool, use the Streamlit app:

    ```bash
    streamlit run app.py
Enter the required details (age, class, sex, etc.) in the input fields.
The model will predict the likelihood of survival based on these inputs.
## Model
The project employs several machine learning algorithms to achieve optimal predictions. Models used include:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Each model’s performance is evaluated based on metrics like accuracy, precision, and recall.

## Results
Best Model: The Random Forest Classifier achieved the highest accuracy with effective predictions on the Titanic dataset.
Feature Importance: Features like sex, age, and class played a significant role in survival predictions.
