# Ship Detection from Satellite Images

## Overview
This project focuses on detecting ships in satellite images using deep learning techniques. It utilizes Convolutional Neural Networks (CNNs) for image classification and object detection.

## Features
- **Data Preprocessing:**  
  - Loading and resizing satellite images.  
  - Augmenting images to improve model robustness.  

- **Model Architecture:**  
  - Implementing a CNN-based model for ship detection.  
  - Using Transfer Learning (e.g., ResNet, VGG16) to enhance performance.  
  - Training the model with annotated ship images.  

- **Evaluation:**  
  - Performance metrics such as accuracy, precision, recall, and F1-score.  
  - Visualizing predictions with bounding boxes on test images.  

## Dataset
The dataset consists of satellite images labeled for ship presence.  
Features include:
- High-resolution satellite images.  
- Labels indicating ship presence and location.  

## Dependencies
Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn tensorflow keras opencv-python
