# Chest X-ray Image Classification for Pneumonia Detection

This project focuses on using deep learning techniques to classify chest X-ray images into pneumonia and normal classes. The dataset used is sourced from Kaggle and includes training, testing, and validation sets. The objective is to develop a robust convolutional neural network (CNN) model that accurately distinguishes between pneumonia-infected and normal chest X-ray images.

# Project Overview

**Approach:**

- Data preprocessing involves resizing images and performing grayscale normalization.
- Data augmentation techniques (rotation, zoom, shift, flip) are applied to increase the diversity of training examples and prevent overfitting.
- A CNN model is constructed using Keras, comprising convolutional layers, max pooling, dropout, batch normalization, and dense layers.
- The model is trained using the augmented data
- Performance metrics such as accuracy, precision, recall, and F1-score are evaluated using classification reports and confusion matrices.



## Tech Stack

- **Languages:** Python
- **Libraries:** TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn, OpenCV
- **Dataset:** The dataset consists of chest X-ray images categorized into pneumonia and normal classes.


## Prerequisites

- Python 
- TensorFlow
- Keras
- OpenCV
- Matplotlib
- Seaborn
- Pandas
- NumPy



## Results

- The trained CNN model achieves promising results with high accuracy and recall in detecting pneumonia from chest X-ray images.
- Visualizations and analysis of model predictions are provided to understand its performance.

![image](https://github.com/Javaria-Shabbir24/PneumoniaRecognitionUsingCNN/assets/102341169/ed983f18-34c3-42b8-9c69-ea1349816e4f)

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.


## Acknowledgements

- Kaggle for providing the chest X-ray dataset.
