# SVM Assignment - Iris Dataset Classification

This project demonstrates the implementation of a Support Vector Machine (SVM) model using Python and Scikit-learn for classifying the Iris flower dataset.

## Project Overview

The notebook includes:

* Data loading using Seaborn
* Exploratory Data Analysis (EDA)
* Data visualization with PairPlot and KDE plots
* Splitting the dataset into training and testing sets
* Training an SVM classifier
* Evaluating the model using:

  * Confusion Matrix
  * Classification Report
* Hyperparameter tuning using GridSearchCV

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

## Dataset

The project uses the built-in Iris dataset available in Seaborn.

Features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

Target Classes:

* Setosa
* Versicolor
* Virginica

## Machine Learning Workflow

1. Import libraries
2. Load dataset
3. Perform Exploratory Data Analysis
4. Visualize data
5. Prepare training and testing data
6. Train SVM model
7. Evaluate model performance
8. Optimize model using GridSearchCV
9. Compare results before and after tuning

## Results

The tuned SVM model achieved very high classification accuracy on the Iris dataset after parameter optimization.

## How to Run

1. Open the notebook:
   `02-SVM-Assignment-Completed.ipynb`

2. Install required libraries if needed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run all notebook cells.
