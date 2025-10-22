# 🌼 Decision Tree Classifier — Iris Dataset

A simple **Machine Learning** project using the **Decision Tree Classifier** to predict iris flower species based on sepal and petal measurements.

---

## 🔍 Overview
- Built with **scikit-learn**
- Uses **Entropy** criterion for splitting
- Evaluates accuracy and displays the decision tree

---

## 🧠 Code Highlights
```python
from sklearn.tree import DecisionTreeClassifier
clf = DecisionTreeClassifier(criterion="entropy")
clf.fit(X_train, Y_train)
y_pred = clf.predict(X_test)

Accuracy: ~96%
Dataset: Iris.csv (150 samples, 3 species)

Run it
pip install numpy pandas scikit-learn matplotlib
python decision_tree_classifier.py
Author

Ananya Prasad M
MSc Electronics (AI), University of Kerala