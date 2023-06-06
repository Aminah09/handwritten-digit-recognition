# Handwritten Digit Recognition using MNIST Dataset

This project aims to implement a handwritten digit recognition system using the MNIST dataset. The MNIST dataset is a widely used benchmark dataset in the field of machine learning and computer vision.

## Overview

The task of handwritten digit recognition involves training a machine learning model to correctly identify and classify handwritten digits. The MNIST dataset consists of a large collection of labeled images of handwritten digits, ranging from 0 to 9. Each image is a grayscale image of size 28x28 pixels.

## Requirements

To run this project, you will need the following:

- Python 3 (preferably Python 3.6 or later)
- Jupyter Notebook or any other Python development environment
- Required Python libraries: TensorFlow, Keras, NumPy, Matplotlib

## Getting Started

1. Clone this repository to your local machine or download the project files.
2. Install the required Python libraries if not already installed. 
3. Launch Jupyter Notebook or any other Python development environment.
4. Open the `handwritten_digit_recognition.ipynb` notebook file.
5. Follow the instructions provided in the notebook to execute the code and train the model.
6. Once the model is trained, you can use it to make predictions on new handwritten digit images.

## Project Structure

The project structure is as follows:

- `Digit Recognition.ipynb`: The Jupyter Notebook containing the code for loading and preprocessing the MNIST dataset, building and training the model, and evaluating the performance.
- `README.md`: This readme file providing an overview of the project and instructions for running it.
- `bestmodel.h5`: The trained model saved in the Hierarchical Data Format (HDF5) file format.
- `image.png`: An example image of a handwritten digit for testing the trained model.
- `interface.py`: A Python script that provides an interface to interact with the trained model and make predictions on new handwritten digit images.

## Dataset

The MNIST dataset is not included in this repository. You can download the dataset from the following sources:

- [MNIST handwritten digit database](http://yann.lecun.com/exdb/mnist/)

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore and modify the code according to your needs. Happy digit recognition!
