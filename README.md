# Potato-Disease-Classification
Predict the type of Disease a potato leaf if suffering with, using Convolutional Neural Network (CNN).
You can get the Dataset from "https://www.kaggle.com/datasets/ashokkumarpalivela/potato-diseases"
![Potato_Disease](https://user-images.githubusercontent.com/102272183/213642582-247ccf58-c130-4349-9936-7dbda300f76c.png)

# Potato Disease Classifier
This project aims to classify potato diseases based on their appearance in images. The project uses Keras and Tensorflow as its main libraries for building and training the model. The dataset used for this project consists of 2152 images of three different classes: Early Blight, Healthy, and Late Blight.

## Requirements

Tensorflow

Keras

Matplotlib

## Usage

1. Clone the repository to your local machine
2. Navigate to the directory containing the code
3. Install the required libraries mentioned in the Requirements section
4. Run the code with the command: python main.py

## Data Preprocessing

The images are resized to 256 x 256

The images are normalized with a rescale factor of 1/255

The data is split into three parts: train, validation, and test with a ratio of 80%, 10%, 10% respectively

The train and validation datasets are further augmented with random flip and rotation operations

## Model
The model consists of several Convolutional Neural Network (Conv2D) layers, followed by Max Pooling layers, and finally a fully connected layer to produce the final output. The model has been trained to classify the images into three classes with the categorical crossentropy loss function and the Adam optimizer.

## Evaluation
The model's accuracy can be evaluated by running the code and comparing the results with the ground truth.

## Contributions
Contributions are welcome in the form of issues and pull requests. If you have any questions or suggestions, feel free to reach out to us.

