# FIRST-MNIST-DIGIT-CLASSIFIER
# MNIST Digit Classifier using PyTorch

## Overview

This project is a handwritten digit classifier built using PyTorch. The model is trained on the MNIST dataset to recognize digits from 0 to 9 using a simple feedforward neural network.

## Features

- Built with PyTorch
- Uses the MNIST dataset
- Fully connected neural network
- Trained using the Adam optimizer
- Evaluates model accuracy on the test dataset
- Saves the trained model as `mnist_model.pth`
- Predicts handwritten digits from test images

## Model Architecture

Input (784)

↓

Linear (784 → 128)

↓

ReLU

↓

Linear (128 → 64)

↓

ReLU

↓

Linear (64 → 10)

## Technologies Used

- Python
- PyTorch
- Torchvision
- Matplotlib

## Dataset

The project uses the MNIST handwritten digit dataset provided by `torchvision.datasets.MNIST`.

- Training images: 60,000
- Test images: 10,000
- Image size: 28 × 28 pixels

## Installation

```bash
git clone https://github.com/your-username/mnist-digit-classifier.git

cd mnist-digit-classifier

pip install torch torchvision matplotlib
```

## Run

```bash
python train.py
```

## Output

The program:

- Downloads the MNIST dataset
- Trains the neural network
- Displays training loss
- Calculates test accuracy
- Saves the trained model
- Predicts a sample digit

## Sample Result

```
Epoch 1/5 | Loss: ...
Epoch 2/5 | Loss: ...
...
Test Accuracy: 97.8%

Actual Label: 7
Predicted Label: 7
```

## Future Improvements

- Add Convolutional Neural Network (CNN)
- Build a GUI using Tkinter
- Create a web app using Flask or FastAPI
- Deploy the model online
- Add support for custom handwritten digit images

## Author

Ravi Yadav
B.Sc. AI & ML Student
