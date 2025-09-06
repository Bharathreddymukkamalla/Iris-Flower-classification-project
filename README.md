🌸 Iris Classification using Machine Learning

This project demonstrates how different machine learning algorithms can be applied to the Iris dataset to classify iris flowers into three species:

Iris-setosa

Iris-versicolor

Iris-virginica

The dataset contains measurements of four features:

Sepal Length

Sepal Width

Petal Length

Petal Width

📌 Project Workflow

Data Import & Exploration

Loaded the dataset using Pandas.

Displayed the first few records with head().

Summarized statistics using describe().

Visualization

Used Seaborn pairplot to visualize relationships between features.

Plotted line graphs to understand trends in petal and sepal dimensions.

Data Preparation

Separated features (X) and labels (y).

Split the dataset into training (80%) and testing (20%) sets using train_test_split.

Model Training
Trained three different models:

Support Vector Machine (SVC)

Logistic Regression

Decision Tree Classifier

Model Evaluation

Compared accuracy of each model.

Generated classification reports.

Predictions on New Data

Tested the trained models on unseen input vectors.

📈 Results

Support Vector Machine (SVM) Accuracy: ~96.7%

Logistic Regression Accuracy: ~96.6%

Decision Tree Classifier Accuracy: ~96.6%

All three models performed very well, with slight variations in predictions for new data.
