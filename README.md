# 🌸 Iris Species Classification using KNN (R)

## 📌 Project Overview

This project implements a complete machine learning pipeline to classify Iris flower species using the **K-Nearest Neighbors (KNN)** algorithm in **R**.

The model predicts whether a flower belongs to:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

based on four physical features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA)
* Apply feature normalization
* Train a KNN classifier (K = 3)
* Evaluate model performance
* Visualize decision boundaries
* Analyze effect of different K values

---

## 📊 Dataset

* Built-in **iris dataset** from R
* Total samples: 150
* Features: 4 numeric
* Classes: 3 (balanced dataset)
* Missing values: None

---

 Technologies Used

* R Programming
* ggplot2 (visualization)
* class (KNN algorithm)
* base R (data processing)

---

## 🔍 Methodology

### 1. Data Preprocessing

* Selected key features: Petal Length & Petal Width
* Applied Min-Max normalization
* Split dataset (80% training, 20% testing)

### 2. Model Building

* Algorithm: K-Nearest Neighbors (KNN)
* K value: 3
* Distance metric: Euclidean

### 3. Evaluation

* Accuracy: ~96–97%
* Confusion matrix analysis
* Class-wise performance evaluation

---

## 📈 Results

* **Setosa**: ~100% accuracy (perfect separation)
* **Versicolor & Virginica**: ~90–95% accuracy
* Minor errors due to overlapping feature space

---

## 🧠 Key Insights

* Petal features are the most discriminative
* Feature normalization is essential for KNN
* Optimal K value is typically between 3–5
* Decision boundary visualization improves interpretability

---

## 📉 Limitations

* Slower predictions for large datasets
* Sensitive to feature scaling
* Limited to 2D visualization for plotting

---

## 🚀 Future Improvements

* Use all 4 features for classification
* Implement cross-validation
* Compare with other ML models (SVM, Random Forest)
* Build an interactive Shiny app

---

## 📷 Visualization

Includes:

* Decision boundary plot
* Accuracy vs K graph
* Scatter plots of features

---

## ▶️ How to Run

```r
# Install required packages
install.packages("ggplot2")

# Load libraries
library(ggplot2)
library(class)

# Load dataset
data(iris)
```

Run the scripts provided in the repository to reproduce results.

---

## 📚 References

* "An Introduction to Statistical Learning"
* R Documentation

---


---

##
