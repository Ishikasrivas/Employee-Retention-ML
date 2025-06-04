Employee Retention Prediction Using scikit-learn
In this project, you will leverage decision trees and random forests with scikit-learn and Python to develop an interactive employee churn prediction model. The project guides you through several key steps to build, evaluate, and interpret classification models.

Overview of the Project Workflow
This hands-on project is organized into the following stages:

Task 1: Introduction and Library Imports
Gain an understanding of the dataset and the problem context.

Preview the final interactive application you will create.

Get familiar with the Rhyme interface used for interactive controls.

Import essential Python libraries including NumPy, Matplotlib, and scikit-learn.

Task 2: Exploratory Data Analysis (EDA)
Load the employee turnover dataset using pandas.

Conduct visual exploration of data by plotting features against the target variable using Matplotlib.

Task 3: Categorical Feature Encoding
Identify categorical columns such as Department and Salary.

Convert these categorical variables into dummy/one-hot encoded variables suitable for machine learning.

Task 4: Assess Class Distribution
Use Yellowbrick’s Class Balance visualizer to plot the frequency of each class label.

Determine if the dataset suffers from class imbalance, which will influence how you approach sampling for model training and validation.

Task 5: Training and Validation Set Preparation
Split the dataset into training and validation subsets using an 80/20 ratio.

Employ stratified sampling to maintain consistent class proportions in both sets.

Task 6: Decision Tree Classifier with Interactive Controls
Utilize the interact function to generate interactive UI elements for model parameters.

Train a decision tree classifier using scikit-learn on the training data.

Calculate and display training and validation accuracy scores.

Visualize the structure of the trained decision tree.

Task 7: Random Forest Classifier with Interactive Controls
Again use interact to create adjustable controls for the random forest model parameters.

Train a random forest classifier to address decision trees’ high variance.

Compute and present accuracy scores for training and validation datasets.

Provide a graphical visualization of one of the fitted trees in the forest.

Task 8: Feature Importance and Model Evaluation
Examine the relative importance of features as determined by the fitted decision tree and random forest models using the feature_importances_ attribute.

Create plots to rank features based on their impact.

Review key evaluation metrics to assess model performance.

