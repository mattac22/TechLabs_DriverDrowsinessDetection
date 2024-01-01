# Driver Drowsiness Recognition Project

## Introduction
This project, part of TechLabs' Digital Shaper Program in Aachen (Winter Term 2022/23), addresses the critical issue of driver drowsiness, a significant contributor to road accidents. Utilizing convolutional neural networks (CNNs), the project aims to detect drowsy driving effectively.

## Dataset
The project leverages the Driver Drowsiness Dataset (DDD) from Kaggle, featuring 41,793 RGB images of drowsy and non-drowsy drivers.

## Methodology
### 1. OpenCV Landmark Approach
- **Description**: Employs facial landmarks detection using OpenCV to identify drowsy behavior based on specific facial feature movements.
- **Notebook**: `opencv_landmark_approach.ipynb`

### 2. CNN Approach
- **Description**: Utilizes a custom Convolutional Neural Network (CNN) to analyze images for signs of drowsiness.
- **Notebook**: `CNN_approach_DDD.ipynb`

### 3. Transfer Learning Approach
- **Description**: Applies Transfer Learning technique using a pre-trained ResNet50 model to detect drowsiness, allowing for high accuracy with less data.
- **Notebook**: `Transfer_Learning_approach_DDD.ipynb`

## Results
Achieved an accuracy and F1-score of around 64% using Landmark detection, 90% with CNN, and 86% with Transfer learning for drowsiness recognition.

## Further Improvements
Suggestions include expanding the dataset, enhancing data preprocessing, and integrating more landmarks in the detection algorithm.

## Acknowledgments
Special thanks to mentor Jöran Rixen and TechLabs Aachen. 

## Team Members
- Christian Sinn
- Aishwarya Bose
- Maroof Mohammed Abdul Aziz
- Misha Abramovich

## Links
- [Driver Drowsiness Dataset on Kaggle](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd)

