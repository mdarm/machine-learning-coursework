This work is one of a series of three distinct repositories that collectively constitute the coursework focused on Neural Networks for the Μ124 - Machine Learning course at the National and Kapodistrian University of Athens (NKUA) during the Fall 2022 semester. The other two repos deal with [Activation functions & gradient analysis](https://github.com/KyriakosPsa/ActFunc-GradientAnalysis) and [Adversarial Neural Networks (ANN)](https://github.com/KyriakosPsa/Neural-Networks-Adversarial-Examples).

# Machine Learning Homework 2: Neural Network Exploration

This machine learning project was undertaken using Python and Keras, focusing on neural networks. The exercise explored network architectures and activation functions, and the capability to reproduce results was demonstrated.

## Highlights

- **Implementation**: Python and the Keras library were used for the exercises.

- **Backpropagation**: The backpropagation algorithm for Multi-Layer Perceptrons (MLPs) was revisited, and adjustments were made for:
  - ReLU (Rectified Linear Unit)
  - Hyperbolic Tangent
  - Sigmoid

- **MNIST Classification**: The MNIST dataset was used to address handwritten digit recognition. The approach included:
  - **Data Preprocessing**: Data was normalised.
  - **Network Depth**: Networks of 5, 20, and 40 layers were experimented with.
  - **Activation Functions**: Performance was assessed with ReLU, Hyperbolic Tangent, and Sigmoid.
  - **Compilation**: The SGD optimizer with a learning rate of 0.01 was used, and the categorical crossentropy loss function was employed.

- **Adaptability**: The capability to utilize any publicly available dataset was shown.

- **Reproducibility**: Documentation and code clarity were maintained for easy replication.
