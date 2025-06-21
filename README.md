# 🌸 Iris Flower Classifier — KNN Project

This project is a beginner-friendly introduction to supervised machine learning using the classic **Iris dataset**. I built a **K-Nearest Neighbors (KNN)** model to classify different species of iris flowers based on sepal and petal measurements.

---

## 📂 Table of Contents
- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Visuals](#visuals)
- [What You’ll Learn](#what-youll-learn)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 📌 Overview
This project:
- Loads and explores the Iris dataset 🌸
- Scales features using `StandardScaler`
- Trains a **K-Nearest Neighbors (KNN)** model
- Evaluates performance using accuracy, classification report, and confusion matrix
- Explores the effect of different `k` values
- Saves and displays key plots for visual understanding

---

## 🧰 Tech Stack
- Python 3.8+
- Jupyter Notebook
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

---

## ⚙️ Installation
1. Clone the repo
```bash
git clone https://github.com/opoku-fokuoemmanuel/iris-knn-classifier.git
cd iris-knn-classifier
```

2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🗂 Project Structure
```
iris-knn-classifier/
├── iris_knn_classifier.ipynb     # Main Jupyter Notebook
├── README.md                     # This file
├── requirements.txt              # Python dependencies
└── _assets/                      # Images or plots used in README and analysis
    ├── iris_flower_pairplot.png
    ├── confusion_matrix.png
    └── k_accuracy.png
```

---

## 🚀 Usage
To run the notebook:
```bash
jupyter notebook iris_knn_classifier.ipynb
```

The notebook will walk you through each step:
- Exploratory data analysis
- Model training and evaluation
- Tuning `k` to see which value works best
- Saving and displaying plots inline

---

## 📊 Results
| k Value | Accuracy |
|---------|----------|
| 3       | ~93.50%  |
| 5       | ~93.50%  |
| 7       | ~93.50%  |

The KNN classifier performs well, especially for `k=3` or `k=5` or 'k=7'.

---

## 🖼️ Visuals

### 🌸 Pairplot of Iris Dataset
This plot shows how the three iris species are separated based on their sepal and petal measurements:

![Pairplot of iris dataset](_assets/iris_flower_pairplot.png)

### 🧮 Confusion Matrix
Illustrates model performance visually:

![Confusion matrix](_assets/confusion_matrix.png)

### 📈 Accuracy vs. k Plot
Demonstrates how accuracy changes with different `k` values:

![Accuracy plot](_assets/k_accuracy.png)

---

## 📚 What I Learnt
- Why scaling is important for distance-based models like KNN
- How to split and evaluate datasets
- How to visualize class separation using pairplots
- How to fine-tune a simple model for better results
- How to save and display model evaluation visuals

---

## 🚧 Future Improvements
- I will try other classifiers (Logistic Regression, SVM, etc.)
- I wil add cross-validation to improve model reliability
- I will turn it into a web app using Streamlit or Gradio

---

## 📝 License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

