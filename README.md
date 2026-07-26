# Pumpkin Seed Classification Using Machine Learning

## Project Overview

This project applies machine learning techniques to classify two pumpkin
seed varieties based on their geometric characteristics.

The project covers the complete machine learning workflow, including
exploratory data analysis, data preprocessing, visualization, model
training, model evaluation, and model comparison.

## Dataset

The dataset contains:

- 2,500 pumpkin seed observations
- 12 geometric input features
- 2 pumpkin seed varieties
- 1 target variable: `Class`

The input features describe the geometric characteristics of pumpkin seeds,
including area, perimeter, axis length, eccentricity, roundness, solidity,
aspect ratio, and compactness.

## Project Workflow

1. Loaded and inspected the dataset
2. Performed exploratory data analysis
3. Checked missing values and class distribution
4. Encoded the target variable
5. Conducted correlation analysis and feature selection
6. Split the dataset into training and testing sets
7. Standardized numerical features
8. Trained and compared multiple classification models
9. Evaluated the models using classification metrics

## Models Evaluated

- K-Nearest Neighbors
- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- Support Vector Machine
- AdaBoost
- Gradient Boosting
- XGBoost
- Voting Classifier

## Results

The dataset was divided using a 70/30 train-test split:

- Training set: 1,750 observations
- Testing set: 750 observations

Gradient Boosting achieved the best performance:

- Test accuracy: approximately 89%
- Precision: 0.87 and 0.90
- Recall: 0.91 and 0.87
- F1-score: 0.89 and 0.88

The experimental results showed that ensemble learning models generally
performed better than individual classification models.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Plotly
- XGBoost
- Jupyter Notebook
- Google Colab

## Repository Files

- `pumpkin-seed-classification.ipynb`: data analysis and machine learning notebook
- `Pumpkin_Seeds_Dataset.xlsx`: dataset used in the project
- `pumpkin-seed-classification-report.pdf`: complete academic project report

## Author

Ho Khanh Ngoc
Ho 
Third-year Mathematical Economics Student  
University of Economics and Law, VNU-HCM
