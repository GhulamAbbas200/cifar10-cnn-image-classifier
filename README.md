# CIFAR-10 CNN Classifier

Deep Convolutional Neural Network for CIFAR-10 image classification with advanced data augmentation and model persistence.

## Features
- 6-layer CNN with progressive filter sizes (32→64→128)
- Batch normalization and dropout regularization
- Data augmentation pipeline
- Model checkpointing and persistence
- Real-time inference capabilities

## Tech Stack
- Python, TensorFlow/Keras, NumPy, Matplotlib

## Usage
1. Open `src/main_training.ipynb` in Google Colab
2. Run all cells to train the model
3. Use `src/model_reload.ipynb` for inference

## Results
- Achieved high accuracy on CIFAR-10 test set
- Robust performance with data augmentation
