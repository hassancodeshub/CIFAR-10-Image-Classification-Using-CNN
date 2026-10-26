# CIFAR-10 Image Classification Using CNN

## 📌 Overview

This project implements a **Convolutional Neural Network (CNN)** using PyTorch to classify images from the CIFAR-10 dataset. It covers dataset preparation, model architecture, training, and evaluation using a Jupyter Notebook.

## 🎯 Objectives

- Understand the fundamentals of CNNs for image classification.
- Load and preprocess the CIFAR-10 dataset using TorchVision.
- Build a CNN architecture using PyTorch.
- Train the model using backpropagation and the Adam optimizer.
- Evaluate model performance on the test dataset.

## 🛠️ Technologies Used

- **Python**
- **PyTorch**
- **TorchVision**
- **Jupyter Notebook**

## 📂 Project Structure

```text
CIFAR-10-Image-Classification-Using-CNN/
│
├── CNN_for_CIFAR10.ipynb   # CNN implementation, training, and evaluation
└── README.md                 # Project documentation
```

## 📊 Dataset

The project uses the **CIFAR-10 dataset**, which contains 60,000 color images of size 32 × 32 pixels across 10 classes.

The dataset consists of:
- **50,000 training images**
- **10,000 test images**
- **10 image classes**

The dataset is downloaded automatically through TorchVision when the notebook is executed.

## 🧠 Model Architecture

The CNN is implemented using PyTorch and includes convolutional layers, ReLU activation functions, max-pooling layers, and fully connected layers for classification.

The model is trained using:
- **Loss Function:** Cross-Entropy Loss
- **Optimizer:** Adam
- **Training Epochs:** 10
- **Batch Size:** 64

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/CIFAR-10-Image-Classification-Using-CNN.git
```

### 2. Navigate to the Project Directory

```bash
cd CIFAR-10-Image-Classification-Using-CNN
```

### 3. Install Dependencies

```bash
pip install torch torchvision jupyter
```

### 4. Run the Notebook

```bash
jupyter notebook "CNN_for_CIFAR10(1).ipynb"
```

Run the notebook cells sequentially to download the dataset, build the CNN, train the model, and evaluate its performance.

## 📈 Evaluation

The notebook evaluates the trained model on the CIFAR-10 test dataset by comparing predicted labels with the actual labels and calculating classification accuracy. The model achieved the accuracy of 74 %.

## 📌 Future Improvements

- Experiment with deeper CNN architectures.
- Tune hyperparameters to improve classification accuracy.
- Visualize training loss and model performance.
- Generate a confusion matrix and class-wise evaluation metrics.
- Experiment with data augmentation and regularization.
**Your Name**

Feel free to explore, fork, and improve this project!
