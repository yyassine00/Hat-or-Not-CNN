# Hat Classification using Convolutional Neural Networks (CNN)

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-4.0%2B-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

This project implements a CNN-based image classification model to distinguish between "Hat" and "No Hat" in images. The model is trained on a labeled dataset and provides predictions for test images.

## Overview

This code trains a CNN model to classify images as "Hat" or "No Hat." The project consists of data loading, model creation, training, and inference components. The trained model's weights are saved for later use, and test image predictions are generated and saved to a CSV file.

## Prerequisites

Ensure you have the following dependencies installed:

- Python 3.7 or higher
- TensorFlow 2.0 or higher
- OpenCV 4.0 or higher
- NumPy
- Pandas

You can install the required packages using `pip` with the provided `requirements.txt` file.

```bash
pip install -r requirements.txt
