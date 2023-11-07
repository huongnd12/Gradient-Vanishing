In this project, I would like to introduce 6 methods to avoid `Gradient Vanishing` in Multi-layer Perceptron (MLP): Weight increasing, Better activation, Better Optimizer, Normalize inside network, Skip connection, Train some layers.

I will use `Fashion MNIST` dataset and build a MLP model to classify 10 classes on this dataset. However, there are several problems need to be solved when selecting parameters and hyper-parameters. This project concentrates on solving `Gradient Vanishing` which affects the training performance.

In theory, the deeper we build a model (more hidden layers), the model's ability to learn and represent data will be better than models with fewer layers, but in reality sometimes the result is the opposite.

![image](https://github.com/huongnd12/Gradient-Vanishing/assets/57044034/c020c71c-bf59-4a92-afa2-22517a48f18b)
