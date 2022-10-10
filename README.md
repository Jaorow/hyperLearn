# Python ML Image Gueser

My aim is to train a Deep Neural Network for item/animal detection to be able to have a model determine the probability that there is mentioned item/animal. 

My secondary aim is to create a python application/function that can evaluate my model when you give it any PNG and image. This application should be able to resize my images to 32x32 before having the model evaluate said image.

### Progress

```#####- 90%```

Model can predict image with about `76%` accuracy with the help of **hyperparameter** tuning to so my model can find out the best possible model compilation parameters for a much higher accuracy.


A simple Python function can intake all images in same file and predict what they are however this is currently ugly and not very user freindly 

## Dataset
For my model data I used CIFAR-10 dataset from [here](https://www.cs.toronto.edu/~kriz/cifar.html).
