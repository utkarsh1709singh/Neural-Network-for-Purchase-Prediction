### Neural Network for Purchase Prediction

## Description
This project demonstrates the implementation of a neural network for predicting whether a customer will make a purchase based on their visit duration and the number of pages visited on a website. The neural network is trained using synthetic data generated for this purpose.

## Key Components
* Data Generation: Synthetic data is generated with 200 samples, consisting of two features: visit duration and pages visited. The labels indicate whether a purchase was made (1) or not (0).
* Model Definition and Training: A neural network model is defined using TensorFlow's Keras API. The model consists of an input layer with 2 features, a hidden layer with 10 neurons and ReLU activation, and an output layer with a sigmoid activation function for binary classification. The model is compiled with binary cross-entropy loss and trained using the generated data.
* Model Evaluation: The trained model is evaluated on a test set to assess its accuracy in predicting purchase behavior.
* Visualization: The decision boundary of the neural network model is visualized over the feature space of visit duration and pages visited. The contour plot shows the decision boundary separating the areas where purchases are likely from those where purchases are unlikely.

## Usage
To run the project and train the neural network model:

* Clone this repository to your local machine.
* Ensure you have Python installed along with the necessary libraries listed in the requirements.txt file.
* Run the Python script neural_network_purchase_prediction.py.
* The script will generate synthetic data, train a neural network model, evaluate its performance, and visualize the decision boundary.

## File Description
* neural_network_purchase_prediction.py: Python script containing the implementation of the neural network model for purchase prediction.
* README.md: This README file providing an overview of the project and instructions for usage.
* requirements.txt: File listing the required Python libraries and their versions.

## Contributors
Utkarsh Singh
