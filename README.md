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
<pre>
<b>Dataset Details</b>
Dataset Name            : Chest X-Ray Images (Pneumonia)
Number of Class         : 2
Number/Size of Images   : Total      : 5856 (1.15 Gigabyte (GB))
                          Training   : 5216 (1.07 Gigabyte (GB))
                          Validation : 320  (42.8 Megabyte (MB))
                          Testing    : 320  (35.4 Megabyte (MB))

<b>Model Parameters</b>
Machine Learning Library: Keras
Base Model              : InceptionV3
Optimizers              : Adam
Loss Function           : categorical_crossentropy

<b>Training Parameters</b>
Batch Size              : 64
Number of Epochs        : 50
Training Time           : 3 Hours

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<!--<b>Validation</b>-->
<b>Testing</b>
Accuracy                : 83.44%
Loss                    : 0.42
<!--Precision               : -->
Recall                  : 94% (highest)
<!--Specificity             : -->
</pre>

##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Detection-of-Pneumonia-from-Chest-X-Ray-Images/blob/master/demo/sample/sample.png>
</kbd>

*************************************************************************************************************************************
##### Languages   : Python
##### Tools/IDE   : Anaconda
##### Libraries   : Keras, TensorFlow, Inception, ImageNet
*************************************************************************************************************************************
##### Duration   : October 2018 - Current
##### Current Version  : v1.0.0.0
##### Last Update      : 11.20.2018
*************************************************************************************************************************************


