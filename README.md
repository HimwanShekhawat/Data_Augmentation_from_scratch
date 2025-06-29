# Fashion MNIST Classifier with Data Augmentation

This project implements a deep neural network from scratch (NumPy) to classify Fashion MNIST images. It includes:
- Data normalization
- Data augmentation (random flips and rotations)
- ReLU and Softmax activations
- L2 regularization
- Mini-batch gradient descent
- Model checkpointing

## Features
✅ Fully custom training loop  
✅ Label one-hot encoding  
✅ Batch-wise evaluation  
✅ Accuracy and cost tracking  

## Training
The model is trained for 600 epochs on the Kaggle Fashion MNIST dataset. The best model weights (achieving highest test accuracy) are saved automatically.

## Requirements
- Python 3
- NumPy
- Pandas
- OpenCV
- Matplotlib
- scikit-learn

## Running
Simply run the script in a Kaggle notebook or any Python environment supporting the above libraries.

## Results
The script prints training/test accuracy and cost at each epoch. You can adjust architecture, batch size, learning rate, and regularization.

