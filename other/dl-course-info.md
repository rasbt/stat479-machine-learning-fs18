# STAT 479 SS 2019: Deep Learning

## Abstract

Deep learning is an exciting, young field that specializes in discovering and extracting intricate structures in large, unstructured datasets for parameterizing artificial neural networks with many layers. Since deep learning has pushed the state-of-the-art in many applications, it's become indispensable for modern technology. This is owed to the vast utility of deep learning for tackling complex tasks in the fields of computer vision and natural language processing -- tasks that humans are good at but are traditionally challenging for computers. This includes tasks such as image classification, object detection, and speech recognition.

The focus of this course will be on understanding artificial neural networks and deep learning algorithmically (discussing the math behind these methods on a basic level) and implementing network models in code as well as applying these to real-world datasets. Some of the topics that will be covered include convolutional neural networks for image classification and object detection, recurrent neural networks for modeling text, and generative adversarial networks for generating new data.

Familiarity with general machine learning concepts (such as the FS2018 STAT479: Machine Learning course) is recommended but not required. We will review some relevant background concepts, which include general machine learning concepts such as supervised learning, classification, model evaluation, etc. Furthermore, some lectures will focus on reviewing the use of Python's stack for scientific computing (NumPy, SciPy, matplotlib) prior to the introduction of PyTorch as the main computational deep learning library that we are going to use in this course.


## Tentative List of Topics

- brief history of neural networks and what makes deep learning different from "classic machine learning"
- introducing the concept of neural networks by connecting it to familiar concepts such as logistic regression and multinomial logistic regression (which can be seen as special cases: single-layer neural nets)
- modeling and deriving non-convex loss function through computation graphs
- introduction to automatic differentiation and PyTorch for efficient data manipulation using GPUs
- convolutional neural networks for analyzing unstructured data (image analysis)
- using 1D convolutions for sequence analysis
- more advanced sequence analysis using recurrent neural networks
- introducing generative models to sample from input distributions: autoencoders, variational autoencoders, and generative adversarial neural networks