# MNIST Handwritten Digit Classification using TensorFlow/Keras

## Project Overview

This project implements a simple Artificial Neural Network (ANN) using TensorFlow/Keras to classify handwritten digits (0–9) from the MNIST dataset. The model is trained on 60,000 handwritten digit images and evaluated on 10,000 test images.

The objective of this project is to understand the basic workflow of image classification using deep learning, including data preprocessing, model training, evaluation, visualization, and experimentation.

---

## Dataset

The MNIST dataset contains:

- 60,000 training images
- 10,000 testing images
- Image size: 28 × 28 pixels
- 10 classes (digits 0–9)
- Grayscale images

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
The MNIST dataset was loaded using TensorFlow/Keras.

### 2. Data Exploration
Sample handwritten digit images were displayed to understand the dataset.

### 3. Data Preprocessing
Pixel values were normalized from the range 0–255 to 0–1.

### 4. Model Development
A neural network was created using:

- Flatten Layer
- Dense Layer (128 neurons, ReLU)
- Dense Layer (64 neurons, ReLU)
- Output Layer (10 neurons, Softmax)

### 5. Model Training
The model was trained using:
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 10

### 6. Model Evaluation
The model was evaluated on the test dataset to calculate test accuracy.

### 7. Visualization
Training and validation accuracy/loss graphs were plotted.

### 8. Prediction
The model was tested on 5 handwritten digit images and the actual labels were compared with predicted labels.

### 9. Experiment
An additional experiment was performed by increasing the number of neurons in the hidden layers and comparing the results with the original model.

---

## Model Architecture

Input Image (28×28)

↓ Flatten

Dense (128, ReLU)

↓ Dense (64, ReLU)

↓ Dense (10, Softmax)

---

## Results

### Original Model Accuracy
- Test Accuracy: 0.9768000245094299

### Experimental Model Accuracy
- Test Accuracy: 0.9767000079154968

### Comparison
The experimental model was compared with the original model to observe the effect of changing the network architecture.

---

## Repository Contents

```
MNIST Classification/
│
├── MNIST_Assignment.ipynb
├── README.md
├── Report.pdf
└── requirements.txt
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Tapaswini005/MNIST-Classification.git
```

2. Install dependencies:

```bash
pip install tensorflow numpy matplotlib
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run all cells in `MNIST_Assignment.ipynb`.

---

## Conclusion

This project successfully demonstrates handwritten digit classification using a neural network built with TensorFlow/Keras. The model achieved high accuracy on the MNIST dataset and provided practical experience in deep learning, image classification, model evaluation, and experimentation.

---

## Author

**Tapaswini Shaw**  
B.Tech CSE (AI & ML)  
Rai Technology University