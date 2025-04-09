# 🧠 MNIST Handwritten Digit Classifier (NumPy)

This project is a simple implementation of a neural network from scratch using **NumPy**, trained to recognize handwritten digits from the [MNIST dataset](https://www.kaggle.com/competitions/digit-recognizer).

---

## 🔧 Features

- Two-layer neural network (ReLU + Softmax)
- Trained using gradient descent
- No external ML libraries — just **NumPy**
- Evaluates accuracy on a development set
- Easy to customize and extend

---

## 📁 Dataset

Download the `train.csv` from the [Kaggle Digit Recognizer competition](https://www.kaggle.com/competitions/digit-recognizer/data) and place it in the project root or update the path in the code.

---

## 🚀 How to Run

1. Clone the repo or download the code:
   ```bash
   git clone https://github.com/your-username/mnist-numpy-classifier.git
   cd mnist-numpy-classifier
   ```

2. Run the notebook:
   - Open `main.ipynb` in Jupyter Notebook or Jupyter Lab.
   - Run all cells to train the model and evaluate accuracy.


---

## 🧪 Model Architecture

- **Input Layer**: 784 nodes (28x28 pixels)
- **Hidden Layer**: 64 nodes with ReLU
- **Output Layer**: 10 nodes with Softmax (for digits 0–9)

---

## 📊 Sample Output

```
Iteration 0 - Training Accuracy: 0.11
Iteration 50 - Training Accuracy: 0.45
...
Dev Set Accuracy: 0.87
```

---

## 📌 Todo (for extensions)

- [ ] Add a test set evaluation
- [ ] Visualize predictions on sample images
- [ ] Save and load model weights
- [ ] Add loss plotting
