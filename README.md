# Artificial-Neural-Network
Topics Covered:
  - Deep Learning introduction
  - Machine learning VS Deep learning

  - Perceptron
      - Perceptron Trick
      - Different Loss Functions
      - Multi Layer Perceptron (MLP)
          - Ways to improve overall output of the model
          - MLP Notation

    - Forward Propagation (How the data flows forward in a model while training)
        - Covering the whole math behind forward propogation
    - Back Propagation
        - Step by Step Implementation
            - Initializing values for weights and biases
            - Selecting a point (usually random point is chosen)
            - Choosing a Loss Function
            - Updating the weights and biases using Back Propagation
              - Finding all the values for all the terms for gradient descent
         - Regression and Classification Problem (intro)
         - Main Intuition and covering few questions
      - Convergence
      - Memoization
      - Different Types of Gradient Descent
          - Stochastic GD
          - Batch GD
          - Mini-Batch GD
      - Vanishing Gradient Problem
  - # Improving a Neural Network
        1. Fine Tuning Hyperparametes
        2. By solving :
            - Vanishing / Exploding Gradient
            - Not enough Data
            - Slow training
            - Overfitting
    
    - Fine tuning Hyperparameters
    - Main problem with overfitting and possible solutions
      - Dropout Layer
      - Regularization
      - Activation Functions
          - Sigmoid
          - Tanh
          - ReLU
          - Different Variants of ReLU
            - Leaky ReLU
            - Parametric ReLU
            - ELU
            - SELU
      - Dying ReLU Problem
    - Weight Initialization Techniques
      - What not to do
        - Zero Initialization
        - Non zero constant values
        - Extremely small values (for ex. 0.0001)
        - Large Values (for ex. 0-1)
      - What to do
        - Xavier / Glorant Initialization
        - He Initialization
      - Batch Normalization
        - Internal Covariate Shift
        - How BN works?
        - Pros and Cons of BN
  - Optimizers
