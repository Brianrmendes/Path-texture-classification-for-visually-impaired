# Path-texture-classification-for-visually-impaired

The primary sensory organ of a human is his eyes. One glimpse around us is enough to make us realize that most of the information in our environment is visual. But not all are blessed with the power to see. There are those who are Visually/Partially impaired. Blind people do lead a normal with their own style of doing things. But, they definitely face troubles due to inaccessible infrastructure and social challenges. The biggest challenge for a blind person, particularly one with a total loss of vision, is to navigate around places.


To help the impaired people, we designed a model that detects the different surface regions using the Convolutional Neural Network with high accuracy in order to help them classify the path they are walking on. 

The dataset consists of three textures namely Concrete, Grassy and Muddy. We have trained on two deep learning models which are :- Faster R-CNN Inception V2 and Faster R-CNN ResNet50.

We used a pre-trained model on our dataset thereby applyinh transfer learning.

Data augmentation was done to increase the images in the dataset. The graphical annotation tool called labelimg was used to label the bounding boxes of the objects in the image. We used Tensorflow v1.14 as the models that we selected were compatible with this version.

The loss graphs were plotted with the Faster R-CNN Inception v2 model giving a loss less than 0.2...



