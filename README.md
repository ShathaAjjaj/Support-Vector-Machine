# SVM Classifier on Iris Dataset

## 📖 Description

This project applies a Support Vector Machine (SVM) model to classify the Iris dataset into three species: Setosa, Versicolor, and Virginica.

## 🧠 Model Explanation

SVM is a supervised learning model that finds the optimal hyperplane separating data into classes. It works well for clear margin separation and is effective in high-dimensional spaces.

SVM is a supervised machine learning algorithm used for classification and sometimes regression.

It tries to find the best boundary (hyperplane) that separates classes of data.

It focuses on the support vectors (data points closest to the boundary) to make decisions.

🎯 Goal of SVM (in classification):

To find a line (in 2D) or hyperplane (in higher dimensions) that:

Maximizes the margin (distance between the line and the nearest data points from both classes).

Classifies data points correctly.

## ✅ Benefits

- Handles both linear and non-linear classification using kernels
  
- Effective in high-dimensional spaces
  
- Robust to overfitting (especially with proper kernel)

## ⚠️ Limitations

- Slower on large datasets
  
- Requires tuning of kernel and regularization parameters

## 📊 Dataset

- **Name:** Iris Dataset
  
- **Source:** scikit-learn
  
- **Features:** Sepal/Petal Length & Width
  
- **Target:** Flower species (Setosa, Versicolor, Virginica)
