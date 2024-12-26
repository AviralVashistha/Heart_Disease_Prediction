
> # Heart Disease Prediction Model

This repository contains a machine learning project for predicting heart disease using a dataset sourced from [Kaggle](https://www.kaggle.com/) consisting of 303 observations and 14 features. The project includes a Flask-based web application to provide predictions based on user inputs.

## Dataset Description

The dataset consists of 303 observations and the following features:

- `age`: Age of the person
- `sex`: Gender (1 = male, 0 = female)
- `cp`: Chest pain type (0-3)
- `trtbps`: Resting blood pressure (mm Hg)
- `chol`: Serum cholesterol (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- `restecg`: Resting electrocardiographic results (0-2)
- `thalachh`: Maximum heart rate achieved
- `exng`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slp`: Slope of the peak exercise ST segment (0-2)
- `caa`: Number of major vessels colored by fluoroscopy (0-3)
- `thall`: Thalassemia (1-3)
- `output`: Target variable (1 = heart disease present, 0 = no heart disease)

The dataset is publicly available on [Kaggle](https://www.kaggle.com/) for educational purposes.

Dataset used: [Heart Disease Predictions](https://www.kaggle.com/code/desalegngeb/heart-disease-predictions/input?select=heart.csv)

## Project Features

- **Exploratory Data Analysis (EDA):** Data visualization and preprocessing steps.
- **Feature Selection:** Selection of top features for model building.
- **Model Building:** Logistic Regression is used as the prediction model.
- **Web Application:** A Flask-based interface for user input and prediction.

## Requirements

To install the required dependencies, ensure that you have Python installed and run the following command:

```bash
pip install -r requirements.txt
```


## How to Run

1. Clone this repository:

   ```
   git clone https://github.com/your-repository-link.git
   cd your-repository-folder
   ```
2. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Run the Flask application:

   ```
   python main.py
   ```
4. Access the application in your browser at `http://127.0.0.1:5000`.

## File Structure

* `main.py`: The main Python script for running the Flask application.
* `heart.csv`: The dataset file sourced from Kaggle.
* `requirements.txt`: List of required Python libraries.

## Model Performance

The Logistic Regression model achieved an accuracy of **91%** on the test set after hyperparameter tuning.

## Future Work

* Implementing additional machine learning models.
* Enhancing the UI for better user interaction.
* Using a larger dataset for improved generalization.
