# Starship Titanic – Machine Learning Classification

A Machine Learning project developed as part of the **Kaggle Spaceship Titanic** competition. The objective is to predict whether passengers were transported to an alternate dimension using demographic, spending, and travel information.

## Overview

The Spaceship Titanic dataset presents a binary classification problem where machine learning models are trained to determine whether a passenger was **Transported** after a spacetime anomaly affected the spacecraft.

This project demonstrates a complete machine learning pipeline, including data preprocessing, exploratory data analysis, feature engineering, model development, evaluation, and prediction.

## Problem Statement

The Spaceship Titanic, carrying nearly 13,000 passengers, collided with a spacetime anomaly during its maiden voyage. As a result, nearly half of the passengers were transported to another dimension.

Using passenger information, the goal is to build a predictive model that determines whether a passenger was transported.

## Project Workflow

1. Import required libraries
2. Load training and test datasets
3. Exploratory Data Analysis (EDA)
4. Handle missing values
5. Feature engineering
6. Encode categorical variables
7. Train machine learning models
8. Evaluate model performance
9. Generate predictions
10. Prepare Kaggle submission

## Dataset Features

The dataset contains passenger information such as:

* Passenger ID
* Home Planet
* CryoSleep Status
* Cabin
* Destination
* Age
* VIP Status
* Room Service Expenses
* Food Court Expenses
* Shopping Mall Expenses
* Spa Expenses
* VR Deck Expenses
* Passenger Group Information

### Target Variable

* **Transported**

  * True
  * False

## Repository Structure

```text id="n11wqk"
Assignment_3_StarshipTitanic/
│
├── Assignment_3_StarshipTitanic.ipynb
├── train.csv
├── test.csv
├── sample_submission.csv
├── README.md
└── requirements.txt
```

> Update the filenames if your repository structure is different.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Data Preprocessing

The preprocessing pipeline includes:

* Missing value handling
* Duplicate removal
* Feature engineering
* Encoding categorical variables
* Feature scaling (where required)
* Train-validation split

## Exploratory Data Analysis

The project explores:

* Passenger demographics
* Spending behaviour
* Age distribution
* Missing value analysis
* Correlation between features
* Feature importance
* Data visualization

## Machine Learning Models

Depending on the notebook implementation, the following algorithms can be applied:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost
* Support Vector Machine (SVM)

The best-performing model is selected based on validation accuracy.

## Model Evaluation

The classification model is evaluated using metrics such as:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

## Installation

Clone the repository:

```bash id="vjlwm0"
git clone https://github.com/Assignment3StarshipTitanic/Assignment_3_StarshipTitanic.git
cd Assignment_3_StarshipTitanic
```

Install the required dependencies:

```bash id="ag91uv"
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

or

```bash id="vqop2u"
pip install -r requirements.txt
```

## Running the Project

Start Jupyter Notebook:

```bash id="x9l4cb"
jupyter notebook
```

Open the project notebook and run all cells sequentially.

## Applications

This project demonstrates skills applicable to:

* Customer behaviour prediction
* Risk assessment
* Binary classification problems
* Predictive analytics
* Data preprocessing
* Feature engineering
* Machine Learning model development

## Skills Demonstrated

* Machine Learning
* Classification
* Exploratory Data Analysis
* Feature Engineering
* Data Cleaning
* Model Evaluation
* Python Programming
* Data Visualization
* Kaggle Competition Workflow

## Future Improvements

Potential enhancements include:

* Hyperparameter optimization using GridSearchCV or RandomizedSearchCV
* Ensemble learning techniques
* Cross-validation
* Advanced feature engineering
* Explainable AI using SHAP values
* Model deployment with Streamlit or Flask
* Automated ML pipeline

## Author

**Bharanimaran**

GitHub: https://github.com/Bharanimaran

## License

This project was developed for educational purposes and as part of a machine learning assignment using the Kaggle Spaceship Titanic dataset.
