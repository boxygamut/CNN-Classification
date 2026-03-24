# Short Overview

- 4 Convolutional layers, 3 Max Pooling layers, 1 Adaptive Average Pooling Layer
- Adam optimizer
- Cross Entropy Loss as loss function

Conv -> ReLU -> MaxPool

Adaptive pool used to turn each feature map into a single averaged value

Classifier goes Flatten -> Linear -> ReLU -> Linear