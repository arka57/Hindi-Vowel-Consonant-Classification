## Task: In a given image of an hindi alphabet classify the vowel and consonant

The goal is to identify the vowel and the consonant of each character image using Convolutional Neural Networks and its variations. The model was developed in such a way that given an image of hindi alphabet it will classify both the vowel and consonant present in it. 

After trying various variations of vanilla CNN,ResNet50 and VGG16 it was found that ResNet50 gave comparatively better result though with considerable overfitting happening

In all the standard CNN models the convolution part was pre-trained and the fully connected part was specifically designed to cater to the problem to classify both the vowel and consonant. The models were trained for 16 epochs using ADAM optimizer

Accuracy Metrics
| Model        | Training Accuracy | Testing Accuracy |
|--------------|-------------------|------------------|
| Vanilla CNN  |                   |                  |
| VGG16        | 40.53             | 37.70            |
| ResNet50     | 64.29             | 58.40            |
