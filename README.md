# 🧠 Optimizer Comparison on Fashion MNIST

This project presents a comparative study of various **gradient-based optimization algorithms** applied to a **Convolutional Neural Network (CNN)** trained on the **Fashion MNIST** dataset. The goal is to evaluate and rank each optimizer based on performance metrics such as **validation loss**, **accuracy**, and **F1 score**.

---

## 📊 Optimizers Compared

The following optimizers were implemented and analyzed:

* **SGD with Momentum**
* **SGD with Nesterov Momentum**
* **AdaGrad**
* **RMSProp**
* **Adam**

---

## 🧾 Dataset

**Fashion MNIST** is used as the benchmark dataset. It consists of grayscale 28x28 pixel images across 10 categories of fashion products.

* **Train set**: 60,000 images
* **Test set**: 10,000 images
* **Classes**: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

---

## 🧠 Model Architecture

We used a simple and efficient **Convolutional Neural Network (CNN)** architecture

---

## 📈 Results Summary

| Optimizer         | Loss   | Accuracy (%) | F1 Score |
| ----------------- | ------ | ------------ | -------- |
| Adam              | 0.2895 | 91.81        | 0.9175   |
| Momentum          | 0.2500 | 91.56        | 0.9160   |
| RMSProp           | 0.2803 | 91.72        | 0.9156   |
| AdaGrad           | 0.2463 | 91.15        | 0.9112   |
| Nesterov Momentum | 0.2585 | 91.05        | 0.9101   |

Adam led the performance across **F1 Score** and **accuracy**, making it the best optimizer for this specific setup.

---

## 📷 Visualizations

The project includes visual plots comparing:

* Validation Loss
* Accuracy
* F1 Score

Each optimizer’s learning curve is also visualized for deeper insights into convergence behavior.

---

## 🚀 Getting Started

### 1. Clone the repo

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

You can launch the analysis notebook using:

```bash
jupyter notebook optimizers.ipynb
```

---

## 🧪 Experiments

Experiments are modularly structured:

* `train_model(optimizer_name)`: Trains model using the specified optimizer.
* `evaluate_model()`: Computes accuracy and F1 score.
* `plot_metrics()`: Generates visual comparisons.

---

## 📌 Future Work

* Add more optimizers like AdamW, RAdam, and Lookahead
* Apply learning rate schedulers (e.g., Cosine Annealing, StepLR)
* Evaluate on more complex datasets (e.g., CIFAR-10)

---

## 🙌 Acknowledgments
* Fashion MNIST by Zalando Research
---

## 🙌 Team
* Tigist Wondimneh
* Nahom Senay


