# Emotion Classification Neural Network

This repository contains a simple neural network implemented using Keras for classifying images as happy or sad based on their pixel intensities. The project is a basic demonstration of image classification using a feedforward neural network.

## Code Explanation
The emotion_classification.py script does the following:

Imports necessary libraries, including PIL, NumPy, and Keras.
Loads training images and corresponding labels, preprocesses the data, and constructs a neural network model.
Compiles and trains the model using the training data.
Loads a test image, preprocesses it, and predicts its emotion using the trained model.
## Result 

![image](https://github.com/abhigyan02/Smile-Detection/assets/75851981/ef19d3ca-f35b-4679-99f0-95aeba8ded5a)

## Notes
The script assumes that training images are black and white and have a size of 32x32 pixels. Modify the script if your images have different characteristics.
Ensure that the training and test images are correctly labeled and formatted.
Experiment with the model architecture, training parameters, and preprocessing steps to improve classification accuracy.
