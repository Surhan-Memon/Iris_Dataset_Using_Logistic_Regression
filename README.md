# Iris_Dataset_Using_Logistic_Regression
A machine learning project that classifies Iris flower species (Setosa, Versicolor, Virginica) using Logistic Regression with hyperparameter tuning via GridSearchCV.
Dataset
The classic Iris Dataset with 150 samples across 3 balanced species classes, featuring 4 numerical attributes: Sepal Length, Sepal Width, Petal Length, and Petal Width.
Workflow

Exploratory Data Analysis —> count plots, scatter plots, and pair plots to visualize feature distributions and class separability
Preprocessing —> train/test split (75/25) and StandardScaler normalization
Modeling —> Logistic Regression (saga solver) with GridSearchCV tuning over L1, L2, and ElasticNet penalties
Evaluation —> confusion matrix, classification report, and multiclass ROC curves with AUC scores

Results
Achieved 100% accuracy on the test set, with perfect precision, recall, and F1-score across all three species. All classes returned an AUC of 1.00 on the ROC curve.
Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn
