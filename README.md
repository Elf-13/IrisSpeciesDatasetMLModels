# Iris Species Classification 🌸

A machine learning project for classifying Iris flower species using **Gaussian Naive Bayes** and **Support Vector Classification (SVC)**.

## 📌 About the Project

This project uses the classic **Iris dataset** to predict the species of an Iris flower based on its sepal and petal measurements.

The main goal of this project is to practice the fundamental steps of a machine learning classification workflow, including data preprocessing, feature scaling, model training, evaluation, and hyperparameter optimization.

## 📊 Dataset

The dataset contains measurements of three Iris species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

The features used for classification are:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The `Id` column was removed because it does not provide useful information for classification.

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## ⚙️ Machine Learning Workflow

The project follows these main steps:

1. Load and explore the dataset
2. Check the structure and statistics of the data
3. Separate features and target variable
4. Encode the target labels
5. Split the dataset into training and test sets
6. Standardize the features using `StandardScaler`
7. Train a Gaussian Naive Bayes model
8. Train an SVC model
9. Optimize SVC hyperparameters using `GridSearchCV`
10. Evaluate the models using classification metrics

## 🤖 Models

### Gaussian Naive Bayes

Gaussian Naive Bayes was used as one of the baseline classification models.

### Support Vector Classification (SVC)

SVC was used to classify the three Iris species based on their feature measurements.

### GridSearchCV + SVC

`GridSearchCV` was used to search for the best SVC hyperparameters, including:

* `C`
* `gamma`
* `kernel`

This helped find a better-performing SVC configuration through cross-validation.

## 📈 Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### Results

Both Gaussian Naive Bayes and SVC achieved **100% accuracy on the test set**.

The final SVC model optimized with GridSearchCV also achieved:

**Accuracy: 1.00**

Confusion Matrix:

```text
[[12  0  0]
 [ 0 14  0]
 [ 0  0 12]]
```

This means that all 38 test samples were classified correctly.

> Note: The Iris dataset is a small and well-separated dataset, so very high accuracy can be achieved by several classification algorithms.

## 📁 Project Structure

```text
Iris-Species-Classification/
│
├── Iris_Species.ipynb
├── README.md
└── iris.csv
```

## 🎯 What I Learned

Through this project, I practiced:

* Data exploration with Pandas
* Data preprocessing
* Feature scaling
* Train-test splitting
* Classification with Gaussian Naive Bayes
* Classification with SVC
* Model evaluation
* Confusion matrices
* Hyperparameter optimization with GridSearchCV

## 🚀 Future Improvements

Possible future improvements include:

* Comparing additional classification algorithms
* Visualizing decision boundaries
* Performing more detailed feature analysis
* Experimenting with different SVC kernels and parameters
* Evaluating the models using cross-validation

---

**Built as part of my machine learning learning journey.**
