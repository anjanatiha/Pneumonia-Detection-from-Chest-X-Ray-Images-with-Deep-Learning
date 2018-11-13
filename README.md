# Pneumonia Detection from Chest X-Ray Images using Transfer Learning                                          
*************************************************************************************************************************************
##### Domain             : Computer Vision, Machine Learning
##### Sub-Domain         : Deep Learning, Image Recognition
##### Techniques         : Deep Convolutional Neural Network, ImageNet, Inception
##### Application        : Image Recognition, Image Classification, Medical Imaging
*************************************************************************************************************************************
### Description
1. Detected Pneumonia from Chest X-Ray images by retraining pretrained model “InceptionV3” with 5856 images of X-ray (1.15GB).
2. For retraining removed output layers, freezed first few layers and Fine-tuned model for two new label classes (Pneumonia and Normal).
3. Attained testing accuracy 83.44% and loss 0.42.
*************************************************************************************************************************************
### Flower Dataset:
###### Number of Class: 2
###### Number of Images: Total: 5856, Training: 5216, Validation: 320, Testing: 320
###### Dataset Size: Total: 1.15 GB, Training: 1.07 GB, Validation: 42.8 MB, Testing: 35.4 MB
###### Base Model: InceptionV3
###### Optimizers: Adam
###### Loss Function: categorical_crossentropy
<!---
###### Number of Epochs: 8
###### Training Time (Approx.): 2 Hours
-->
###### Metrics (Accuracy): Testing: 83.44%
###### Metrics (Loss): Testing: 0.42
*************************************************************************************************************************************
##### Languages   : Python
##### Tools/IDE   : Anaconda
##### Libraries   : Keras, TensorFlow, Inception, ImageNet
*************************************************************************************************************************************
##### Duration   : October 2018 - Current
##### Current Version  : v1.0.0.0
##### Last Update      : 11.08.2018
*************************************************************************************************************************************


