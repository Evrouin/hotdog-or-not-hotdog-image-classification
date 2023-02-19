# Binary Image Classification with TensorFlow using Inception ResNet V2

This is a binary image classification project that uses a convolutional neural network (CNN) to detect whether an image is a "hotdog" or "not hotdog." The project utilizes transfer learning to fine-tune a pre-trained Inception ResNet V2 model for image classification.

## Dataset 
The [dataset](https://www.kaggle.com/datasets/thedatasith/hotdog-nothotdog) comprises `4,642 images` in total, split evenly between "hotdog" and "not hotdog" categories, with `2,121 images` for training and `200 images` for testing.

## Model
The project uses a pre-trained Inception ResNet V2 model as the base model, with a dense layer of 2 units added for binary classification. The model was fine-tuned for 50 epochs on the training set with a batch size of 32.

The trained model achieved `94.25%` accuarcy and `0.1438` loss on the test set.

The project was developed using Google Colab, a free cloud-based platform that provides easy access to GPUs and TPUs, making it ideal for machine learning projects.

## Sample Results
![download (1)](https://user-images.githubusercontent.com/72487125/219941250-0a6b8a86-7f70-4e1a-aeb3-697033a2bded.png)
