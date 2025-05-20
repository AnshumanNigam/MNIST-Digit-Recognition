# MNIST-Digit-Recognition
This project builds and trains a Multi-Layer Perceptron (MLP) model to classify handwritten digits from the MNIST dataset. The MLP processes flattened 28x28 pixel images and predicts the digit class.

---

## Features

- Loads and preprocesses the MNIST dataset
- Builds and trains a ANN model using TensorFlow/Keras
- Evaluates model accuracy on test data
- Saves example prediction images with matplotlib
- Uses `categorical_crossentropy` loss for one-hot labels or `sparse_categorical_crossentropy` for integer labels (adjustable)

---

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib

Install dependencies with:


## How to Run

### Clone this repository:
```bash
git clone <your-repo-url>
cd <repo-folder>
