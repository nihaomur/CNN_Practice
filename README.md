# CNN Practice:
In this repository, I practiced building *CNN* models and later applied pre-trained models from the Keras API for *Transfer Learning*.

## [Minst](Minst.ipynb):
Constructed a convolutional neural network for predicting the Keras-built MNIST dataset. Explored the use of image augmentation techniques, but observed a decrease in training accuracy for digits. Image augmentations, such as flipping, led to a loss of original discernible features.

## [Cat Dog Classify](Cat_Dog_Classify.ipynb):
Utilized the pre-trained *ResNet50* model to classify cat and dog images, achieving an accuracy of 97.06%.

## [Mango Level Classify](Mango_Level_Classify.ipynb):
Performed *data augmentation* on the dataset and trained using three pre-trained models: *Xception*, *EfficientNet*, and *EfficientV2B2*. Successfully addressed the mango level classification problem with accuracy of 85.25%.
