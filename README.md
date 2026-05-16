# student-performance-mlp
# 🎓 Student Performance Prediction using MLP

## 📌 Problem Description

This project predicts student performance (math score) using a Multilayer Perceptron (MLP).
The model uses features such as gender, parental education, and reading/writing scores.

---

## 📊 Dataset

Dataset: Student Performance Dataset

Link:
https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

Target Variable:

* math score

---

## ⚙️ Model

A simple Multilayer Perceptron (MLP) was implemented using PyTorch.

Architecture:

* Input layer
* Two hidden layers
* Output layer

Activation Functions:

* ReLU
* Tanh (experiment)

Loss Function:

* Mean Squared Error (MSE)

Optimizer:

* Adam

---

## 🧪 Experiments

| Experiment | Activation | Learning Rate | MSE     |
| ---------- | ---------- | ------------- | ------- |
| Exp 1      | ReLU       | 0.01          | 81.62   |
| Exp 2      | Tanh       | 0.01          | 46.37   |
| Exp 3      | ReLU       | 0.001         | 4880.17 |

---

## 📈 Results

* ReLU with lr = 0.01 gave better performance.
* Tanh showed different behavior.
* Lower learning rate reduced performance.

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python project.py
```

---

## 📌 Conclusion

The MLP model successfully predicts student performance.
Hyperparameters like learning rate and activation functions significantly affect performance.
