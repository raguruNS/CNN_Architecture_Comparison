# Project 13: CNN Architecture Comparison

## 📌 Project Overview

This project compares two Convolutional Neural Network (CNN) architectures to understand how network structure and depth affect image classification performance.

A Simple CNN is compared with a ResNet-style CNN using the CIFAR-10 dataset. Both models are trained and evaluated on the same dataset subsets to ensure a fair comparison.

The models are evaluated based on accuracy, loss, number of parameters, training time, confusion matrices, and classification reports.

## 🎯 Objectives

- Implement two different CNN architectures.
- Train both models using the same image dataset.
- Compare their classification accuracy and loss.
- Analyze model complexity and training time.
- Generate confusion matrices and classification reports.
- Understand the impact of residual connections on CNN performance.

## 🛠️ Technologies Used

- Python
- TensorFlow and Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 📂 Project Structure

```text
Project-13-CNN-Architecture-Comparison/
│
├── Project_13_CNN_Architecture_Comparison.ipynb
└── README.md
```

## 📊 Dataset: CIFAR-10

The CIFAR-10 dataset contains 60,000 color images of size 32 × 32 pixels, divided into 10 classes.

The classes are:

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

The notebook uses the same selected training and test subsets for both models.

## 🧠 CNN Architectures

### 1. Simple CNN

The Simple CNN uses convolutional layers, max pooling, global average pooling, and dense layers to extract image features and classify images.

**Main components:**
- Convolutional layers
- Batch normalization
- ReLU activation
- Max pooling
- Global average pooling
- Dense classification layer

### 2. ResNet-Style CNN

The ResNet-style CNN uses residual blocks and skip connections to help information and gradients flow through deeper networks.

**Main components:**
- Convolutional layers
- Batch normalization
- ReLU activation
- Residual blocks
- Skip connections
- Global average pooling
- Softmax classification layer

*Note: This is a custom ResNet-style model trained from scratch, not a pretrained ResNet50 model.*

## ⚙️ Installation

The notebook installs the required libraries using:

```python
!pip install tensorflow numpy pandas matplotlib seaborn scikit-learn
```

Google Colab can run the project without requiring a local Python installation.

## 🚀 How to Run the Project

1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook**.
4. Upload `Project_13_CNN_Architecture_Comparison.ipynb`.
5. Run each cell in order.
6. Allow both models to train.
7. Review the evaluation metrics, graphs, confusion matrices, and classification reports.

For faster training, select a GPU under **Runtime → Change runtime type**, if available.

## 🔬 Project Tasks

### Task 1: Implement Two CNN Models

Build a Simple CNN and a ResNet-style CNN with residual connections.

### Task 2: Train and Test Both Models

Train both architectures on the same CIFAR-10 training subset and evaluate them on the same test subset.

### Task 3: Compare Model Performance

Compare the models using:

- Test accuracy
- Test loss
- Number of trainable and non-trainable parameters
- Training time
- Confusion matrix
- Precision, recall, and F1-score
- Prediction errors

## 📈 Evaluation Metrics

| Metric | Purpose |
|---|---|
| Accuracy | Measures the proportion of correct predictions |
| Loss | Measures the model's prediction error according to the loss function |
| Precision | Measures how many predicted positives are correct for a class |
| Recall | Measures how many actual examples of a class are correctly identified |
| F1-score | Combines precision and recall |
| Confusion matrix | Shows correct and incorrect predictions by class |
| Parameter count | Indicates model size and complexity |
| Training time | Measures the time required to train each model |

## 📉 Expected Output

The notebook generates:

- Sample CIFAR-10 images
- Training and validation accuracy graphs
- Training and validation loss graphs
- Test accuracy and loss for both models
- Confusion matrices
- Classification reports
- A model comparison table
- Graphs comparing accuracy, parameter count, and training time
- Examples of incorrect predictions

Actual results depend on the number of epochs, training subset, initialization, and available hardware.

## 🏁 Conclusion

This project demonstrates how CNN architecture influences image classification performance. The Simple CNN provides a baseline, while the ResNet-style CNN introduces residual connections to support deeper feature learning.

By comparing accuracy, loss, computational complexity, confusion matrices, and classification reports, we can identify the strengths and weaknesses of both architectures. The experiment also demonstrates that a more complex model does not automatically guarantee better performance under every training configuration.

## 👨‍💻 Author

**Name:** Nitheesh

**Project:** Project 13 – CNN Architecture Comparison
