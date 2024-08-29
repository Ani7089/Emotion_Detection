# Emotion Detection Project

## Overview

This project focuses on developing an emotion detection model that can classify facial expressions into one of seven categories. The model is built using the ResNet50V2 architecture and is trained on the FER-2013 dataset, which contains grayscale images of faces labeled with different emotions.

## Features

- **Data Preprocessing**: Preprocess the FER-2013 dataset, including resizing images, normalizing pixel values, and converting labels to categorical format.
- **Model Architecture**: Utilize the ResNet50V2 architecture pre-trained on ImageNet, with additional layers for adapting to the emotion classification task.
- **Emotion Detection**: The model can detect and classify emotions into the following seven categories:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Sad
  - Surprise
  - Neutral
- **Evaluation Metrics**: Assess model performance using accuracy, confusion matrix, and other relevant metrics.

## Dataset

### FER-2013 Dataset

- **Source**: The dataset used for this project is the FER-2013 dataset, which is available on Kaggle [here](https://www.kaggle.com/datasets/msambare/fer2013).
- **Format**: The dataset contains 35,887 grayscale images of faces, each 48x48 pixels in size. Each image is labeled with one of the seven emotion categories.
  - `pixels`: The pixel values of the image, represented as a string of comma-separated values.
  - `emotion`: The label corresponding to one of the seven emotion categories.
  
- **Usage**: The dataset is split into training and validation sets for training and evaluating the emotion detection model.

## Installation

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

### Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/emotion-detection.git
2. Navigate to the project directory:
   ```bash
	cd emotion-detection
3. Download the Inshorts dataset and place it in the data directory.

### Visualizing Results
- To visualize the model's predictions on a batch of test images, run:
  ```bash
  python Gradio_deployment.py

### Results
The model's performance is evaluated using accuracy and a confusion matrix.
You can find the evaluation results and visualizations of predictions in the results directory.





