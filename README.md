### Image Classification Challenge
## Overview
Welcome to the Image Classification challenge! We aim to build a neural network that can predict the object in a given image. The dataset consists of images belonging to 11 major food categories, including bread, dessert, rice, noodles, meat, seafood, dairy products, egg, soup, fruit, and fried food. The challenge involves training a model on the provided dataset and submitting predictions on a test set to evaluate categorization accuracy.

![image](https://github.com/Sajidcodes/ImageCLS/assets/101083684/18b736cd-ae21-4696-ac37-00d1678bf2de)


# Dataset
The dataset is split into three sets:

Training set: 9867 jpg images
Validation set: 3431 jpg images
Test set: 1501 jpg images
The labels are represented as integers from 0 to 10, corresponding to the 11 food categories. The jpg file names follow the format '[label]_[id].jpg', where 'label' is the category label, and 'id' is the image identifier.

![image](https://github.com/Sajidcodes/ImageCLS/assets/101083684/1e87a055-bb65-4867-983d-ff2135f8845a)


# Evaluation Metric
The evaluation metric for this challenge is Categorization Accuracy.

# Food for thought
To enhance your model's performance, consider the following hints:

![image](https://github.com/Sajidcodes/ImageCLS/assets/101083684/eeb9923d-2582-4269-bc8d-fe39b307f19e)

Tune hyperparameters and change optimizers: Experiment with different settings.
Design more complex models: Explore architectures suitable for image classification.
Cross validation or resplit train/validation sets: Optimize your model's generalization.
Data augmentation (optional): Use torchvision.transforms to generate diverse images. You can also manually modify torch.utils.Dataset to create linear combinations of two images by changing the returned images and labels.
Feel free to explore these hints to improve your model's accuracy and enhance your learning experience. Good luck!
