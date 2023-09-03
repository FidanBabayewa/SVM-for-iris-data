# SVM-for-iris-data
Welcome to the Support Vector Machine Project! In this project, we will explore the famous Iris flower dataset and provide solutions and explanations for each step.

## About the Data

The Iris flower dataset, introduced by Sir Ronald Fisher in 1936, is a multivariate dataset widely used in machine learning. It consists of measurements from 150 iris flowers, representing three different species: Iris setosa, Iris versicolor, and Iris virginica. The dataset includes four features for each sample, which are the length and width of both the sepals and petals, all measured in centimeters.

The dataset is divided as follows:
- Iris-setosa: 50 samples
- Iris-versicolor: 50 samples
- Iris-virginica: 50 samples
- Four features: sepal length, sepal width, petal length, petal width


## Getting the Data

To begin, we'll load the Iris dataset using Seaborn:

```python
import seaborn as sns
iris = sns.load_dataset('iris')
```

This will provide us with the necessary data to perform our analysis.

## Exploratory Data Analysis (EDA) - Solutions

For a better understanding of the data, here are the solutions and explanations for the tasks performed during EDA:

### 1. Pairplot

A pairplot was created to visualize relationships between features and identify separability among flower species. It is evident that Iris-setosa is the most separable species.

### 2. KDE Plot

A KDE plot of sepal length versus sepal width for the setosa species of flower was created to examine the characteristics of Iris-setosa.

## Train-Test Split - Solutions

The data was split into a training set and a testing set for model evaluation.

## Training a Model - Solutions

A Support Vector Machine Classifier (SVC) model from Scikit-Learn was used to train the model. The model was fitted to the training data.

## Model Evaluation - Solutions

The model was evaluated by performing the following tasks:

- Predictions were made on the test data.
- A confusion matrix and a classification report were created to assess accuracy and precision. The results demonstrated that the model performed well.

## GridSearch Practice - Solutions

GridSearchCV from Scikit-Learn was used to practice hyperparameter tuning. The following steps were taken:

- GridSearchCV was imported.
- A parameter grid called "param_grid" was created, specifying values for parameters such as C and gamma.
- GridSearchCV was used to find the best combination of hyperparameters.
- The tuned model's predictions were evaluated with a confusion matrix and a classification report.


## Conclusion

The Support Vector Machines Project - Solutions provides comprehensive guidance and explanations for the steps involved in working with the Iris flower dataset and training an SVM classifier. 
