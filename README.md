# wine-quality
Wine Quality Prediction using SVC, Random Forest and Decision Tree

Wine Quality Prediction Using Machine Learning

Project Overview

This project performs a comparative analysis of three machine learning
classification algorithms for predicting wine quality using the Red
Wine Quality dataset from Kaggle.

The three algorithms used are:

Support Vector Classifier (SVC)

Random Forest Classifier

Decision Tree Classifier

The models are evaluated and compared using Accuracy, Precision, Recall,
F1 Score, and Confusion Matrix.

Dataset

Dataset Name: Red Wine Quality
Source: Kaggle
Dataset Link:
https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

The dataset contains physicochemical measurements of red wine samples
and a quality score.

Input Features

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

Target

The original quality score is converted into a binary classification
target:

0 --- Not Good: quality < 7

1 --- Good: quality >= 7

Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Machine Learning Algorithms

1. Support Vector Classifier (SVC)

SVC finds a suitable decision boundary that separates the classes.
Feature scaling is applied before training because SVC is sensitive to
the scale of input features.

2. Random Forest Classifier

Random Forest combines multiple decision trees to make a final
prediction. It can also be used to identify the importance of different
wine features.

3. Decision Tree Classifier

Decision Tree uses a sequence of feature-based decisions to classify a
wine sample. The tree can be visualized to understand its
decision-making process.

Project Workflow

Kaggle Dataset
      ↓
Load Dataset
      ↓
Data Inspection
      ↓
Check Missing Values
      ↓
Create Good/Not Good Target
      ↓
Train-Test Split
      ↓
Feature Scaling for SVC
      ↓
Train 3 ML Models
      ↓
SVC | Random Forest | Decision Tree
      ↓
Model Prediction
      ↓
Evaluation
      ↓
Accuracy | Precision | Recall | F1 Score
      ↓
Confusion Matrices
      ↓
Final Comparison

Evaluation Metrics

Accuracy

Measures the overall percentage of correct predictions.

Precision

Measures how many predicted positive samples are actually positive.

Recall

Measures how many actual positive samples are correctly identified.

F1 Score

Provides a balance between Precision and Recall.

Confusion Matrix

Shows the number of correct and incorrect predictions for each class.

Visualizations

The project includes:

SVC Confusion Matrix

Random Forest Confusion Matrix

Decision Tree Confusion Matrix

Decision Tree visualization

Random Forest feature importance graph

Final comparison graph of the three algorithms

Installation

Install the required libraries using:

pip install pandas numpy matplotlib seaborn scikit-learn ipykernel

If using Jupyter Notebook, the following can also be run in a notebook
cell:

%pip install pandas numpy matplotlib seaborn scikit-learn ipykernel

How to Run

Download winequality-red.csv from Kaggle.

Place the CSV file in the same folder as the Jupyter Notebook.

Open the notebook in VS Code or Jupyter Notebook.

Select the correct Python kernel/environment.

Run the cells in order.

Review the evaluation metrics and graphs.

Compare the three algorithms.

Expected Output

The notebook produces:

Dataset preview and shape

Missing-value check

Training and testing data sizes

SVC performance metrics

Random Forest performance metrics

Decision Tree performance metrics

Three confusion matrices

Decision Tree visualization

Random Forest feature importance

Final comparison table

Final comparison graph

Conclusion

This project demonstrates how different supervised machine learning
algorithms can be applied to the same wine-quality classification
problem. SVC, Random Forest, and Decision Tree are trained using the
same train-test split and evaluated using the same metrics. The
algorithm with the strongest evaluation results on the test data can be
selected as the best-performing model for this experiment.

Note: The final performance values depend on the train-test split,
preprocessing, and model settings. Use the values produced by your own
notebook in the final report.

Project Structure

wine-quality-ml/
│
├── winequality-red.csv
├── Wine_Quality_ML.ipynb
└── README.md
