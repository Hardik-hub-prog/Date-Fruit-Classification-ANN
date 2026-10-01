# Date Fruit Classification using Artificial Neural Network (ANN)

## 📌 Project Overview

This project implements a **Feedforward Neural Network (FNN)** using PyTorch to classify date fruits into seven different classes based on the dataset's input features.

The model was trained for 100 epochs and achieved approximately **92% classification accuracy**, demonstrating the application of deep learning to a multiclass classification problem.

## 🎯 Objectives

- Understand the architecture of an Artificial Neural Network.
- Implement forward propagation and backpropagation.
- Apply CrossEntropyLoss for multiclass classification.
- Optimize model parameters using the Adam optimizer.
- Evaluate model performance using classification accuracy.

## 📊 Dataset

The project uses the Date Fruits Dataset, containing approximately 900 samples and seven fruit classes.

The dataset contains numerical features describing date fruits, which are used as inputs to train the classification model.

## 🧠 Model Architecture

The ANN consists of the following layers:

- **Input Layer:** Accepts the dataset's input features.
- **Hidden Layer 1:** 64 neurons.
- **Hidden Layer 2:** 64 neurons.
- **Output Layer:** 7 neurons, representing the seven classes.

The hidden layers use the activation function implemented in the model. The output layer produces class scores for multiclass classification.

## ⚙️ Training Workflow

1. Load and prepare the dataset.
2. Split the data into training and testing sets.
3. Convert the data into PyTorch tensors.
4. Define the ANN architecture.
5. Perform forward propagation to generate predictions.
6. Calculate the loss using `CrossEntropyLoss`.
7. Perform backpropagation to compute gradients.
8. Update model parameters using the Adam optimizer.
9. Train the model for 100 epochs.
10. Evaluate the trained model using classification accuracy.

## 🛠️ Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn


## 📈 Results

The trained ANN achieved approximately **92% classification accuracy**.

This project provided practical experience with neural network architecture, loss calculation, gradient computation, parameter optimization, and multiclass classification.

## 📚 Key Learnings

- Understanding the working of Feedforward Neural Networks.
- Implementing forward propagation and backpropagation.
- Understanding loss functions and gradient-based optimization.
- Training neural networks using PyTorch.
- Evaluating a multiclass classification model.

## 🚀 Future Improvements

- Evaluate performance using a confusion matrix and classification report.
- Experiment with different hidden-layer sizes and learning rates.
- Compare different optimizers and activation functions.
- Improve generalization through hyperparameter tuning.

## 👨‍💻 Author

**Hardik Jain**

Aspiring AI/ML Engineer | Python | Deep Learning | PyTorch
