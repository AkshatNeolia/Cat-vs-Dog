# Cat vs Dog Classification

## Overview
This project implements a deep learning model to classify images of cats and dogs. The model is trained using a convolutional neural network (CNN) on a dataset of labeled images.

## Features
- Image classification using CNN
- Data preprocessing and augmentation
- Model training and evaluation
- Predictions on new images

## Technologies Used
- Python
- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib

## Dataset
The dataset consists of labeled images of cats and dogs. It can be obtained from Kaggle or other online sources.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AkshatNeolia/cat-vs-dog-classification.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare the dataset and organize it in the required directory structure.
2. Run the training script:
   ```bash
   python train.py
   ```
3. Test the model on new images:
   ```bash
   python predict.py --image path/to/image.jpg
   ```

## Results
- The model achieves high accuracy on test images.
- Performance can be improved by fine-tuning the architecture.
