# Breast Cancer Classification

This project focuses on building a classification model to predict whether a breast tumor is **malignant** or **benign** using the Breast Cancer Wisconsin dataset. It leverages a simple neural network built with **TensorFlow** and standard ML tools for preprocessing and evaluation.

## 🔍 Overview

- **Goal**: Classify tumors as malignant or benign
- **Dataset**: Breast Cancer Wisconsin (from `sklearn.datasets`)
- **Accuracy**: Achieved **95.6%** on test data
- **Tools**: TensorFlow, Scikit-learn, Pandas, NumPy, Matplotlib

## 🧠 Model

A feedforward neural network was built using TensorFlow with:
- Input layer matching 30 features
- Hidden layers with ReLU activations
- Output layer with softmax for binary classification

## ⚙️ Workflow

1. **Data Loading**  
   Loaded the Breast Cancer dataset using Scikit-learn's built-in API.

2. **Preprocessing**  
   - Converted to Pandas DataFrame  
   - Standardized features using `StandardScaler`  
   - Train-test split (80-20)

3. **Model Training**  
   - Used TensorFlow's Keras API  
   - Trained over 10 epochs with validation split  
   - Visualized accuracy and loss over epochs

4. **Evaluation**  
   - Evaluated on test set  
   - Achieved **95.6% accuracy**

## 📈 Results

- Accuracy: **95.6%**
- Visualized training vs. validation accuracy and loss

## 📁 Files

- `breastCancerClassification.ipynb` — main Jupyter notebook
- `README.md` — project overview

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/breast-cancer-classification.git
   cd breast-cancer-classification

## 🚀 Installation

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Run the notebook:
Open `breastCancerClassification.ipynb` in Jupyter Notebook or VS Code.

## 🧰 Requirements

- Python 3.x
- TensorFlow
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

You can install these with:
```bash
pip install tensorflow scikit-learn pandas numpy matplotlib
```

## 📌 License

This project is open source and available under the MIT License.
