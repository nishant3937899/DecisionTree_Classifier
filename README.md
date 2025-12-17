# DecisionTree_Classifier

A **Decision Tree Classification** project implemented using **Python** and **Jupyter Notebooks**.  
This repository demonstrates **pre-pruning** and **post-pruning** techniques using **two different datasets** to clearly illustrate how pruning impacts model performance and overfitting.

---

## 📁 Project Structure

```
DecisionTree_Classifier/
├── .ipynb_checkpoints/
├── Breast_Cancer.csv
├── prepruning.ipynb        # Decision Tree with pre-pruning (Breast Cancer dataset)
├── postpruning.ipynb       # Decision Tree with post-pruning (Iris dataset)
└── README.md
```

---

## 🧠 Project Overview

Decision Trees are powerful and interpretable supervised learning algorithms, but they are prone to **overfitting**.  
This project focuses on controlling overfitting using **pruning techniques**:

- **Pre-Pruning** – limits tree growth during training
- **Post-Pruning** – simplifies the tree after it has fully grown

Each method is demonstrated using a different dataset for better conceptual understanding.

---

## 📊 Datasets Used

### 🔹 Breast Cancer Dataset (Pre-Pruning)
- Notebook: `prepruning.ipynb`
- File: `Breast_Cancer.csv`
- Problem Type: Binary Classification
- Objective: Control tree complexity during training

### 🔹 Iris Dataset (Post-Pruning)
- Notebook: `postpruning.ipynb`
- Source: `sklearn.datasets`
- Problem Type: Multi-class Classification
- Objective: Reduce overfitting after full tree growth

---

## ✂️ Pruning Techniques

### Pre-Pruning
Applied during training using constraints such as:
- `criterion`
- `max_depth`
- `max_features`
- `splitter`

This prevents the model from becoming overly complex.

### Post-Pruning
The tree is first allowed to grow fully and is then pruned back based on performance metrics to improve generalization.

---

## 🛠 Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Key Learnings

- How decision trees split data
- Difference between pre-pruning and post-pruning
- Impact of pruning on model performance
- Working with real-world and built-in datasets


