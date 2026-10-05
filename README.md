# 🌸 Module 5 – Iris Data Science Mini Project

## Project Title
**Iris Flower Classification using Python and K-Nearest Neighbors (KNN)**

## 📌 Project Overview
This project demonstrates a complete beginner-friendly Data Science workflow using the classic **Iris dataset** from the UCI Machine Learning Repository.

The project covers:

- Dataset collection
- Data cleaning
- Exploratory Data Analysis (EDA)
- Data visualization
- Insight generation
- Machine Learning classification
- Model evaluation
- Prediction of a new flower

## 🎯 Objectives

1. Load a public real-world dataset.
2. Understand the structure of the dataset.
3. Check and clean missing/duplicate values.
4. Perform exploratory data analysis.
5. Create meaningful visualizations.
6. Identify useful patterns and insights.
7. Build a KNN classification model.
8. Evaluate model accuracy.
9. Predict the species of a new Iris flower.

## 📊 Dataset

**Dataset:** Iris  
**Source:** UCI Machine Learning Repository  
**URL:** https://archive.ics.uci.edu/dataset/53/iris

The dataset contains:

- 150 observations
- 4 numerical features
- 3 flower species

### Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal in cm |
| Sepal Width | Width of the sepal in cm |
| Petal Length | Length of the petal in cm |
| Petal Width | Width of the petal in cm |

### Target

The target variable is the Iris species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

## 🧹 Data Cleaning

The notebook performs:

- Missing-value checking
- Duplicate checking
- Removal of missing rows if present
- Removal of duplicate rows
- Whitespace cleanup in the target column

The UCI documentation reports that the original Iris dataset has no missing values.

## 📈 Exploratory Data Analysis

The project analyzes:

- Dataset shape
- Data types
- Statistical summary
- Species distribution
- Average measurements by species
- Correlations between numerical features

## 📊 Visualizations

Six visualizations are included:

1. Species count plot
2. Feature histograms
3. Petal-length box plot
4. Sepal-length vs sepal-width scatter plot
5. Pair plot
6. Correlation heatmap

## 🤖 Machine Learning

### Algorithm
**K-Nearest Neighbors (KNN)**

### Process

```text
Features
   ↓
Train/Test Split
   ↓
Standardization
   ↓
KNN Training
   ↓
Prediction
   ↓
Accuracy Evaluation
```

The model uses:

- Sepal length
- Sepal width
- Petal length
- Petal width

## 📏 Model Evaluation

The notebook calculates:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

The exact accuracy is generated when the notebook is executed because it depends on the actual train/test evaluation.

## 🔍 Key Insights

- The three Iris classes have equal representation in the classic dataset.
- Petal measurements provide strong separation between species.
- Iris-setosa is particularly easy to distinguish.
- Petal length and petal width are strongly positively correlated.
- Sepal measurements have more overlap between classes.
- KNN can classify the Iris species effectively using the four measurements.

## ▶️ How to Run

### Google Colab

1. Open Google Colab.
2. Upload `Module_5_Iris_Data_Science_Mini_Project.ipynb`.
3. Run the cells from top to bottom.
4. Wait for the charts and model results.
5. Save the completed notebook.

### Local Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Then open the notebook and run all cells.

## 📁 Project Files

```text
Module_5_Iris_Data_Science_Mini_Project.ipynb
README_Module_5_Iris_Project.md
```

## 🏁 Conclusion

This project demonstrates the complete basic Data Science lifecycle from collecting a public dataset to data cleaning, visualization, insight generation, machine learning, evaluation, and prediction.

## 📚 Dataset Citation

Fisher, R. (1936). *Iris* [Dataset]. UCI Machine Learning Repository.

DOI: https://doi.org/10.24432/C56C76

## 👩‍💻 Author

**[Eniya K]**

Module 5 – Data Science Mini Project
