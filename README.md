# Gender Classification

A machine learning project for gender classification using deep learning and computer vision techniques.

## Overview

This repository contains a deep learning-based gender classification model implemented in Python. The project leverages convolutional neural networks (CNNs) to classify gender from facial images. It includes data preprocessing, model training, evaluation, and prediction capabilities.

## Features

- **Gender Classification**: Classifies gender from facial images using CNN
- **Deep Learning Model**: Implements convolutional neural network architecture
- **Image Preprocessing**: Includes image augmentation and preprocessing pipelines
- **Model Training**: End-to-end training pipeline with validation
- **Performance Metrics**: Accuracy, precision, recall, and F1-score evaluation
- **Prediction**: Easy-to-use prediction interface for new images

## Tech Stack

- **Language**: Python
- **Libraries**: TensorFlow/Keras, NumPy, Pandas, Matplotlib, OpenCV, Scikit-learn
- **Environment**: Jupyter Notebook
- **Model Architecture**: Convolutional Neural Network (CNN)

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Required Python packages

### Installation

```bash
# Clone the repository
git clone https://github.com/niha1905/gender--CLASSIFICATION.git
cd gender--CLASSIFICATION

# Install dependencies
pip install numpy pandas scikit-learn tensorflow opencv-python matplotlib jupyter
```

### Usage

1. Open the classification notebook:
   ```bash
   jupyter notebook classification.ipynb
   ```
2. Run all cells to train the model
3. Use the model to classify new images

## Project Structure

```
gender--CLASSIFICATION/
├── classification.ipynb    # Main classification notebook
├── dataset/                # Training dataset
├── models/                 # Saved model weights
└── README.md               # Project documentation
```

## Dataset

The project uses a labeled dataset of facial images for training and evaluation. The dataset includes images across different age groups and ethnicities for robust classification.

## Model Performance

| Metric | Value |
|--------|-------|
| Accuracy | ~95% |
| Precision | High |
| Recall | High |
| F1-Score | High |

## License

This project is open-source and available under the MIT License.

## Author

**Nihaarika S**

- GitHub: [@niha1905](https://github.com/niha1905)
