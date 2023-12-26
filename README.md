# Driver Drowsiness Recognition Project

## Introduction
This project, part of TechLabs' Digital Shaper Program in Aachen (Winter Term 2022/23), addresses the critical issue of driver drowsiness, a significant contributor to road accidents. Utilizing convolutional neural networks (CNNs), the project aims to detect drowsy driving effectively.

## Dataset
The project leverages the Driver Drowsiness Dataset (DDD) from Kaggle, featuring 41,793 RGB images of drowsy and non-drowsy drivers.

## Methodology
1. **Data Preprocessing**: Involves cleaning and transforming data using Pytorch and Google Colab.
2. **CNN Approach**: Employs a CNN architecture for image classification.
3. **Landmark Detection Approach**: Uses dlib for facial landmark detection and drowsiness prediction.

## Results
Achieved an accuracy and F1-score of around 83% with CNN, and 64% using landmark detection for drowsiness recognition.

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
- [GitHub Repository](https://github.com/mattac22/TechLabs_DriverDrowsinessDetection)
- [Driver Drowsiness Dataset on Kaggle](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd)

