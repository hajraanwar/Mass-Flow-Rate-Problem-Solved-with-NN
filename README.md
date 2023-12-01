# Mass Flow Rate Prediction Neural Network
This repository contains implementations of a neural network for predicting mass flow rates based on fluid dynamics parameters. Three different approaches are demonstrated, each showcasing various aspects of neural network implementation.

### 1. MLPRegressor with Scikit-Learn
The first implementation uses MLPRegressor from the Scikit-Learn library. It predicts mass flow rates based on delta pressure (delta_p) and drag coefficient (Cd). The results include evaluation metrics such as R2 score and Mean Squared Error (MSE).


### 2. Numpy-Based Neural Network
The second implementation is a more manual approach where the neural network is built from scratch using NumPy. It includes defining the architecture, activation functions (ReLU), and training the model using gradient descent. Similar evaluation metrics are provided.

### 3. Numpy-Based Neural Network with Custom Learning Rate
The third implementation is an extension of the NumPy-based neural network with the addition of a custom learning rate. This allows experimentation with different learning rates to observe their impact on training performance.


## Usage
Execute the respective Python scripts mentioned above to run each implementation. The results, including actual vs. predicted data plots and evaluation metrics, will be displayed.

## Neural Network Architectures
### Input Layer:
The neural networks take input parameters such as delta_p and Cd.
### Hidden Layer: 
A single hidden layer with 50 neurons is used in each implementation.
### Output Layer:
The output layer predicts the mass flow rate.


## Results and Evaluation
The results include 3D surface plots comparing actual and predicted mass flow rates. Additionally, R2 score and MSE metrics are provided to evaluate the model performance.

## Libraries Used
### NumPy: 
For mathematical operations and neural network implementation.
### Scikit-Learn: 
For the MLPRegressor model in the first implementation.

## Notes
These implementations serve as educational resources for understanding neural network concepts in both manual and library-dependent approaches.
Experiment with different hyperparameters and architectures for a deeper understanding of their impact on model performance.
Feel free to explore and experiment with the code. If you encounter any issues or have improvement suggestions, please open an issue.

Happy coding and mass flow rate prediction!







