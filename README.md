# Employee Attrition Prediction

This project aims to predict employee attrition (whether an employee will leave the company or not) using logistic regression. The dataset includes various features related to employee satisfaction, performance, and demographics.

## Table of Contents
- Dataset
- Features
- Installation
- Usage
- Model Training
- Evaluation
- Contributing

## Dataset
The dataset contains the following columns:
- `satisfaction_level`: Employee satisfaction level (0-1)
- `last_evaluation`: Last evaluation score (0-1)
- `number_project`: Number of projects
- `average_montly_hours`: Average monthly working hours
- `time_spend_company`: Number of years spent in the company
- `Work_accident`: Whether the employee had a work accident (0: No, 1: Yes)
- `left`: Whether the employee left the company (0: No, 1: Yes)
- `promotion_last_5years`: Whether the employee was promoted in the last 5 years (0: No, 1: Yes)
- `Department`: Department the employee belongs to
- `salary`: Salary level (low, medium, high)

## Features
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling features.
- **Model Training**: Training a logistic regression model to predict employee attrition.
- **Model Evaluation**: Evaluating the model using accuracy, precision, recall, and F1-score.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/cemileturkel/Hr_Analytics_Job_Prediction-Logistic_Regression.git
    cd Hr_Analytics_Job_Prediction-Logistic_Regression
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare the dataset and place it in the project directory.
2. Run the preprocessing script:
    ```bash
    python preprocess.py
    ```
3. Train the model:
    ```bash
    python train.py
    ```
4. Evaluate the model:
    ```bash
    python evaluate.py
    ```

## Model Training
The logistic regression model is trained using the following features:
- `satisfaction_level`
- `last_evaluation`
- `number_project`
- `average_montly_hours`
- `time_spend_company`
- `Work_accident`
- `promotion_last_5years`
- `Department`
- `salary`

## Evaluation
The model is evaluated using the test dataset. The following metrics are used:
- **Accuracy**: Overall accuracy of the model.
- **Precision**: Precision of the model.
- **Recall**: Recall of the model.
- **F1-score**: F1-score of the model.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
