# 🎓 Hyperparameter Tuning with Weights & Biases 

The main objective of this project is to improve the use of the hyperpameter Tuning (Sweep) tool of the WandB platform.

In addition, putting into practice techniques of Data augmentation, Batch Normalization, Droupout, etc., were also activities developed during the elaboration of this assigment, in order to evolve the understanding in convolutional neural networks.

To make this possible, one of the first CNNs created was used, LeNet-5, published by Yann LeCun, et al. in November, 1998 ([Gradient-Based Learning Applied to Document Recognition](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)). 

Since the network was developed for the application of digit recognition technique, we will also use the same dataset in which it was originally validated, the MNIST. This dataset composes a set of images with digits from 0 to 9, as show in the image below.

## 📋 Stages Organization 

For every practice, 3 models were divided (all based on LeNet-5), with the objective of working on different aspects, as already mentioned. Thus, the organization and the respective tasks developed in each of them are presented below:

1. LeNet-5: Working with the original network architecture, where the main goal was to start understanding the use of hyperpameter tuning from Sweeps.
2. LeNet-5 With Data augmentation: Still a job done using the original network, but with a slight addition, the use of data augmentation in order to create a more generalized model.
3. PadocaNet: In the last model a "new" network was created, using as base the original LeNet-5, but with the addition of BatchNormalization techniques, Droupout and even a change in the activation function. In order to attempt to improve even more the model, techniques of data augmentation were also used here.

## 💭 Brief overview of the results

Here its displayed the results from the best models that the created Sweeps were able to generate.

Model                           |Accuracy|Precision|Recall|F1-Score
--------------------------------|:--------:|:---------:|:------:|:--------:
[LeNet-5](https://github.com/MiguelEuripedes/embedded_AI/tree/main/Projects/mnist_with_lenet/LeNet-5)               |  0.9873   | 0.9873    | 0.9873 | 0.9873
[LeNet-5 With Data augmentation](https://github.com/MiguelEuripedes/embedded_AI/tree/main/Projects/mnist_with_lenet/LeNet-5_with_Data_Augmentation)                 | 0.9607   | 0.9615    |  0.9607 | 0.9607
[PacodaNet](https://github.com/MiguelEuripedes/embedded_AI/tree/main/Projects/mnist_with_lenet/PadocaNet)              | 0.9835   | 0.9835    | 0.9835 | 0.9835

# Reference 
[Ivanovitch's repository for embedded artificial intelligence repository](https://github.com/ivanovitchm/embedded.ai)

