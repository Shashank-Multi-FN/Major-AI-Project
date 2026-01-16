# Major Project Report: Data Preprocessing & AI Models

## 1. Objective
The goal of this project is to clean and preprocess a public dataset, build machine learning models using scikit-learn, evaluate model performance using standard metrics, and train a simple deep learning model using TensorFlow.

---

## 2. Dataset Used
**Titanic Dataset**
- Source: Public dataset
- Task: Predict survival of passengers based on input features

---

## 3. Data Preprocessing
Steps performed:
1. Checked missing values
2. Filled missing Age values using median
3. Filled missing Embarked values using mode
4. Dropped Cabin column due to large missing data
5. Encoded categorical columns using one-hot encoding
6. Normalized Age and Fare using MinMaxScaler

---

## 4. Machine Learning Models (Scikit-learn)
### Models used:
1. Logistic Regression
2. Random Forest Classifier

### Evaluation metrics:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

Random Forest performed better overall compared to Logistic Regression.

---

## 5. Deep Learning Model (TensorFlow)
Dataset used:
- MNIST Handwritten Digit Dataset

Model used:
- Fully connected neural network with dropout layer

Evaluation:
- Checked test accuracy
- Plotted training/validation accuracy and loss graphs

---

## 6. Conclusion
This project successfully demonstrated:
- Real-world data preprocessing
- Model training using scikit-learn
- Proper evaluation using multiple metrics
- Training a basic neural network using TensorFlow

This improved understanding of the full machine learning workflow from data cleaning to model evaluation.
