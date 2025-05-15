# 🧠 Decision Tree Classifier on Social Network Ads Dataset

This notebook demonstrates a complete machine learning pipeline using a **Decision Tree Classifier** to predict whether a user purchases a product based on their social network behavior. This is a classic binary classification problem that highlights decision boundaries, model explainability, and model evaluation metrics.

---

## 📚 Table of Contents

1. [Project Overview](#-project-overview)
2. [Technologies Used](#-technologies-used)
3. [Workflow Summary](#-workflow-summary)
   - [Data Loading and Exploration](#1-data-loading-and-exploration)
   - [Preprocessing](#2-preprocessing)
   - [Model Training](#3-model-training)
   - [Evaluation](#4-evaluation)
   - [Visualization](#5-visualization)
4. [Results](#-results)
5. [Future Improvements](#-future-improvements)
6. [Contribution](#-contribution)
7. [License](#-license)

---

## 📌 Project Overview

- **Goal:** Predict user behavior (purchase or not) based on age and estimated salary using Decision Trees.
- **Dataset:** [Social Network Ads Dataset](https://www.kaggle.com/datasets/rakeshrau/social-network-ads)
- **ML Task:** Binary classification  
- **Algorithm:** Decision Tree (from `sklearn`)

---

## 🔧 Technologies Used

- **Python 3**
- **Pandas & NumPy** – for data manipulation
- **Matplotlib & Seaborn** – for data visualization
- **Scikit-learn** – for ML modeling and evaluation

---

## 🔬 Workflow Summary

### 1. Data Loading and Exploration
- Load CSV using `pandas`
- Check for null values
- Overview of feature statistics

### 2. Preprocessing
- Select relevant features: `Age`, `EstimatedSalary`, and `Purchased`
- Encode categorical variables if necessary
- Train/test split using `train_test_split`

### 3. Model Training
- Use `DecisionTreeClassifier`
- Fit model on training data

### 4. Evaluation
- Accuracy, confusion matrix, classification report
- Visualize the decision tree using `plot_tree`

### 5. Visualization
- Plot decision regions
- Tree structure interpretation for model transparency

---

## 📊 Results

- Achieved high accuracy on both training and test sets
- Tree visualization reveals interpretable decision rules
- Evaluation metrics include precision, recall, and F1-score

---

## 📈 Future Improvements

- Hyperparameter tuning with GridSearchCV
- Compare with other classifiers (Random Forest, SVM, Logistic Regression)
- Feature engineering & scaling

---

## 🤝 Contribution

Feel free to fork the repo, make improvements, and submit a pull request. Contributions are welcome!

---

## 🧾 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
