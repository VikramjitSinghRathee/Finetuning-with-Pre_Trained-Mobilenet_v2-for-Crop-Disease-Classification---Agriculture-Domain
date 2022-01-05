# Project Info
This is a deep learning project in the field of agriculture. 

Each year, farmers suffer economic losses and crop loss as a result of different illnesses. **We will utilize mobilenet_v2 Convolutional Neural Network which is pre-trained on the ImageNet dataset and Finetune it with plant disease image dataset**. The goal is to classify images and develop an app/mobile app that will allow farmers to snap a picture of a plant and the app will determine whether the plant has a disease or not. 

Here we'll be doing potato disease classification.
- Dataset consist of **leaf images** from healthy potato plants and diseased potato plants (Early blight and Late blight)
- 3 classes
  - Early blight, Late blight, Healthy

This project's technology stack will include the following:
- Tensorflow with Keras API
- TF dataset
- Data Augmentation
- mobilenet_v2 model pre-trained on the ImageNet dataset.
- Tensorflow Lite (Useful for mobile dev)
