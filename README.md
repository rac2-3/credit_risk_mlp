# Neural Network–Based Credit Risk Prediction (MLP)

## 📌 Project Overview
This project implements a Multi-Layer Perceptron (MLP) model for binary classification of credit risk using the German Credit dataset. The goal is to predict whether a customer is a good or bad credit risk based on financial and demographic features.

## 📊 Dataset
- Dataset: German Credit Dataset
- Total Instances: 1000
- Features: 20 input features
- Target Variable:
  - 0 → Bad Credit
  - 1 → Good Credit

## ⚙️ Data Preprocessing
- Handling missing values using mode imputation
- Encoding categorical variables using LabelEncoder
- Feature scaling using StandardScaler
- Train-test split (80% training, 20% testing)

## 🧠 Model Architecture
- Input Layer: 20 features
- Hidden Layer 1: 64 neurons (ReLU)
- Hidden Layer 2: 32 neurons (ReLU)
- Output Layer: 1 neuron (Sigmoid)
- Loss Function: Binary Cross-Entropy
- Optimizer: Adam
- Metric: Accuracy

## 📈 Results
- Training Accuracy: ~84%
- Validation Accuracy: ~70%
- Test Accuracy: 74%
- Confusion Matrix and Classification Report included.

## 📦 Libraries Used
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🎯 Conclusion
The MLP model demonstrates moderate performance in predicting credit risk. It performs better in identifying good credit customers compared to bad credit customers.

---

### Author
Raj Tilak Singh  
MCA (AI & ML)  
K.R. Mangalam University
