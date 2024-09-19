
# Hyperspectral Image Classification

This project focuses on classifying hyperspectral images using advanced machine learning techniques. Hyperspectral imaging captures a wide range of wavelengths for each pixel in an image, which provides critical data for applications like land cover classification, environmental monitoring, and anomaly detection. By leveraging machine learning models, this project aims to achieve high accuracy in classifying various features within these images.

## Features
- **Dataset**: The project utilizes benchmark hyperspectral datasets such as Pavia University, Indian Pines, and Salinas.
- **Classification Models**: Multiple machine learning models are employed, with a focus on deep learning techniques, particularly **Convolutional Neural Networks (CNNs)**, which excel at handling high-dimensional data like hyperspectral images.
- **Dimensionality Reduction**: Techniques such as **Principal Component Analysis (PCA)** are used to reduce data dimensionality while preserving essential information, improving model performance.
- **Anomaly Detection**: In addition to classification, the model identifies anomalies in the data, aiding in the early detection of potential natural hazards.

## Technical Stack
- **Python**: Primary programming language for model development.
- **Libraries**: Utilized libraries like **TensorFlow**, **Keras**, **NumPy**, and **Pandas** for deep learning, data manipulation, and analysis.
- **Data Preprocessing**: Techniques like normalization and data augmentation are implemented to enhance model performance.

## Installation & Setup
1. Clone the repository.
2. Install required dependencies using `pip install -r requirements.txt`.
3. Download the hyperspectral datasets from the links provided in the repository.
4. Train the model by running `train.py`.

This project demonstrates the power of machine learning in analyzing hyperspectral data, making it a valuable tool for applications like remote sensing and environmental monitoring.

