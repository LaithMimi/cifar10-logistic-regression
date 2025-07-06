# 🌐 CIFAR-10 Logistic Regression Classifier

A hands-on machine learning project using logistic regression to classify CIFAR-10 image features. This repo demonstrates both **One-vs-All (OvA)** and **Softmax Regression** approaches for multi-class classification, provides evaluation metrics, and analyzes class confusion.

## 🚀 Features

* Binary and multinomial logistic regression with scikit-learn
* One-vs-All (OvA) custom implementation
* Softmax model for direct multi-class classification
* Evaluation using accuracy, log-loss, F1-score
* Confusion matrix analysis for model insight
* Binary comparison model on most-confused classes
* Test function for evaluating unseen data

## 📅 Files

* `Ex1.ipynb`: Main notebook with code, training, evaluation
* `cifar10_features.npy`: Pre-extracted 16D features per image
* `cifar10_labels.npy`: Labels from 0 to 9

## 📊 Example Output

```text
OvA Accuracy: 0.78
OvA Log-loss: 0.54
OvA F1-score: 0.77

Softmax Accuracy: 0.81
Softmax Log-loss: 0.48
Softmax F1-score: 0.80

Most confused classes: 3 vs 5
Binary accuracy (3 vs 5): 0.88
```

## 📁 How to Use

1. Clone the repository
2. Install dependencies:

```bash
pip install numpy scikit-learn
```

3. Run the Jupyter notebook `Ex1.ipynb`

## 🧪 Educational Goal

Learn how logistic regression scales from binary to multi-class classification. Explore how OvA compares to softmax regression. Gain insight into model predictions via the confusion matrix.

## ❤️ Authors

* Laith Mimi
* Mohamad Dweik
* Amro Tarter

---

Made with scikit-learn and CIFAR-10 features
