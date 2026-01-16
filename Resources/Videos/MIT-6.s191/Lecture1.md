# MIT 6.S191

### Chapter 1: Introduction to Deep Learning:

Link to the Video: [MIT](https://youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI&si=oq6FATrOeTkYlT9W)

**Topic Involved:**

- [Perceptron](#perceptron)
    - [Forward Propagation](#forward-propagation)
    - [Activation Function](#activation-function)
    - [Multi Output Perceptron](#multi-output-perceptron)

- [Dense Layer From Scratch](#dense-layer-from-scratch)
    - [TensorFlow Implementation](#tensorflow-implementation)
    - [Pytorch Implementation](#pytorch-implementation)

- [Neural Network](#neural-network)
    - [Single Layer Neural Network](#single-layer-neural-network)
        - [Multi Output Perceptron](#multi-output-perceptron-1)
    - [Deep Neural Network](#deep-neural-network)
- [Practical Implementation](#practical-implementation)

- [Loss](#loss)
    - [Quantifying Loss](#quantifying-loss)
    - [Empirical Loss](#empirical-loss)
    - [Mean Squared Error Loss](#mean-squared-error-loss)

- [Loss Optimization](#loss-optimization)
    - [Gradient Descent](#gradient-descent)
        - [BackPropagation](#backpropagation)
    - [Learning Rates](#learning-rates)
        - [SGD](#sgd)
        - [Adam](#adam)
        - [Adadelta](#adadelta)
        - [Adagard](#adagard)
        - [RMSProp](#rmsprop)
    - [Batching](#batching)

- [Overfitting / Underfitting](#overfitting--underfitting)
    - [Regularization](#regularization)
        - [Dropout](#dropout)
        - [Early Stopping](#early-stopping)

