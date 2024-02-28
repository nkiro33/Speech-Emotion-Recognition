Speech Emotion Recognition using CNN Models
Introduction
This repository contains two distinct approaches to Speech Emotion Recognition (SER) using the Crema dataset. SER systems are designed to process and classify speech signals to detect embedded emotions, extending natural human communication to computer applications. This project explores the implementation of SER using two different convolutional neural network models: a 1D CNN model with TensorFlow and a 2D CNN model with PyTorch.

Dataset
The project uses the Crema dataset, available from Kaggle. This dataset is specifically designed for speech emotion recognition tasks and contains a variety of labeled speech samples corresponding to different emotional states.

Installation
To run the notebooks in this repository, you will need to install several dependencies including TensorFlow or PyTorch depending on the notebook you wish to run. Detailed instructions for setting up your environment can be found in the respective notebooks.

Prerequisites:
Python 3.8 or later
TensorFlow (for the TensorFlow notebook)
PyTorch (for the PyTorch notebook)
Additional Python libraries as specified in the notebooks
Usage
Clone the repository and navigate to the notebook you wish to run. Each notebook is self-contained and includes detailed steps on processing the dataset, building the model, and evaluating the results.

bash
Copy code
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
# Navigate to the TensorFlow or PyTorch notebook directory
Follow the instructions within each notebook to run the SER models.

Approach
TensorFlow 1D CNN Model
This approach utilizes TensorFlow to construct a 1D Convolutional Neural Network that processes the Crema dataset for emotion detection.

PyTorch 2D CNN Model
Alternatively, this approach applies a 2D Convolutional Neural Network using PyTorch to classify emotions from the same dataset.

Both notebooks explain the methodology, data preprocessing, model architecture, training, and evaluation processes in detail.

Contributing
Contributions to this project are welcome. Please feel free to fork the repository, make changes, and submit pull requests.
