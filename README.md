# CIFAR-10 Image Classification

This project demonstrates image classification using a Convolutional Neural Network (CNN) trained on the CIFAR-10 dataset. The goal is to achieve high accuracy in distinguishing between 10 classes of natural images.

## Project Structure

- `Image_Classification_CIFAR10.ipynb` — Main notebook for loading data, building the model, training, and evaluating results
- `Diagram.png` — Visual representation of the model architecture or data pipeline

## Features

- Loads and preprocesses CIFAR-10 dataset using Keras
- Builds and trains a CNN with convolutional, pooling, and dense layers
- Achieves ~73% test accuracy
- Includes training curves and performance evaluation

## Technologies

- Python 3
- TensorFlow / Keras
- Matplotlib, NumPy

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/amoorali/ImageClassificationCifar10.git
   cd ImageClassificationCifar10
   ```
2. Run the notebook:
   ```bash
   jupyter notebook Image_Classification_CIFAR10.ipynb
   ```

## Dataset
CIFAR-10 is a labeled dataset of 60,000 32x32 color images in 10 classes, with 6,000 images per class.

## Results
- Training accuracy: ~85%
- Test accuracy: ~73%
- Confusion matrix and training graphs included in the notebook.
