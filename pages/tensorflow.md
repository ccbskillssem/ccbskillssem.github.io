# Getting started with Tensorflow 2.0

Tensorflow is Google's public deep learning library, first released in 2015. Many would say that it's competed with PyTorch (released in 2016) for popularity, with PyTorch being the preferred library for most deep learning researchers over the past few years. However, just recently (2019), Tensorflow 2.0 was released which offered a much more user-friendly API and deep learning environment than its predecessor. Specifically, it interfaces with Keras now and offers several plug-and-play estimators as well as the ability to develop your own fancy deep learning architectures. While PyTorch still offers a bit more for the deep learning community like more fine-grained control over model architecture and cool [autodifferentiation](https://pytorch.org/tutorials/beginner/blitz/autograd_tutorial.html) capabilities, TensorFlow 2.0 is probably more widely used in development and offers a _ton_ of support like APIs from Javascript or Swift and tremendous amount of developer tools.

In this tutorial, I'll cover the following items:

1. How to identify and frame a machine learning problem
2. Running your first linear regression with Tensorflow 2.0
3. Classification with a Neural Network
4. Saving, loading, and checkpointing models
5. Creating Tensorboard reports

You can navigate to [this Colab](https://colab.research.google.com/drive/1Qf_GsRB8akTpVkcM2nUYj65dyRz7WO6t?usp=sharing) for the full tutorial.

# Additional Resources

- [Weights & Biases](https://www.wandb.com/) - A web-based UI, like Tensorboard, that also helps you track model optimization & peformance
- [Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) - Google's machine learning crash course, focused on Tensorflow 2.0 (mostly). This online resource covers _a lot_ of ground and I highly recommend it if you'd like to get working with more sophisticated models.
- [Estimator API](https://www.tensorflow.org/guide/estimator) - Another way to work with Tensorflow models which is supposed to be more straightforward though requires you to dive a bit more into the Tensorflow ecosystem. However, once you do, there are a ton of out of the box models you can use like BoostedTreeClassifiers and basic linear regression models. Take a look at all it has to offer [here](https://www.tensorflow.org/api_docs/python/tf/estimator).
