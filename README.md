# Cats vs Dogs Image Classification Using CNN

## Project Overview
Image classification is an important application of Deep Learning and Computer Vision. This project focuses on developing a Convolutional Neural Network (CNN) that can automatically identify and classify images of cats and dogs.

CNNs are particularly effective for image recognition because they can automatically extract important visual features such as edges, shapes, textures, and patterns from images.

The model is developed using Python, TensorFlow, and Keras and trained on a dataset containing images of cats and dogs.

## Technologies Used
- Python
- TensorFlow & Keras
- NumPy
- Pandas
- Matplotlib

## Methodology
The project follows these major steps:

1. **Data Loading:** Loading cat and dog images from training and testing directories.
2. **Preprocessing:** Resizing images to 256 × 256 pixels and preparing them for model training.
3. **Model Building:** Designing a CNN architecture using convolutional and pooling layers.
4. **Model Training:** Training the network for 20 epochs with a batch size of 32.
5. **Evaluation:** Analyzing training and validation accuracy and loss.
6. **Prediction:** Using the trained model to classify images as cats or dogs.

## CNN Architecture
The model uses convolutional layers to extract image features, max pooling layers to reduce spatial dimensions, a flatten layer to convert feature maps into a vector, and dense layers for classification.

The final output layer uses the Sigmoid activation function to predict one of two classes: Cat or Dog.

## Dataset
The dataset contains separate training and testing folders, each organized into cats and dogs categories.

**Note:** The dataset ZIP file is not included in this repository due to its large size. It must be downloaded separately to run the project.

## Results
The model was trained for 20 epochs and achieved the following results:

- Training Accuracy: 73.25%
- Best Validation Accuracy: 68.57%
- Final Validation Accuracy: 57.14%
- Final Validation Loss: 0.7567


## Author
**Muhammad Taimoor**  
Aspiring AI Engineer | Machine Learning & Deep Learning
