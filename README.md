# Machine Learning Classification Projects

Two machine learning projects covering classical ML and deep learning approaches to classification problems.

## Projects

### 1. Decision Tree Classifier — Iris Dataset
Implemented a Decision Tree classification model on the classic Iris dataset to classify flower species.

**Features:**
- Data loading and preprocessing with pandas
- Model training using scikit-learn DecisionTreeClassifier
- Model evaluation — accuracy, confusion matrix, classification report
- Visualisation of the decision tree

**Tech:** Python, scikit-learn, pandas, matplotlib

---

### 2. CNN Image Classifier — MNIST Dataset
Built a Convolutional Neural Network for handwritten digit classification on the MNIST dataset.

**Features:**
- CNN architecture design — Conv2D, MaxPooling, Dense layers
- Model training and validation with TensorFlow and Keras
- Training progress visualisation with Matplotlib
- Achieved **98.6% test accuracy**

**Tech:** Python, TensorFlow, Keras, Matplotlib, NumPy

---

## Tech Stack

| Library | Purpose |
|---|---|
| scikit-learn | Decision Tree implementation |
| TensorFlow | CNN model building and training |
| Keras | High level neural network API |
| pandas | Data loading and preprocessing |
| NumPy | Numerical operations |
| Matplotlib | Visualisation |

## Setup

1. Clone the repository
```bash
git clone https://github.com/DRAGOSYS/Decision-Tree-Classifier-and-MNIST-Data-Classifier.git
cd Decision-Tree-Classifier-and-MNIST-Data-Classifier
```

2. Install dependencies
```bash
pip install tensorflow scikit-learn pandas numpy matplotlib
```

3. Run Decision Tree project
```bash
python decision_tree/iris_classifier.py
```

4. Run CNN project
```bash
python cnn/mnist_classifier.py
```
