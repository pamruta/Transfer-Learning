# Transfer-Learning

Template to build a custom image classification model using transfer learning

image-classifier.ipynb allows to quickly build a custom model 
using Transfer Learning method on any dataset, for an image classification task

## Inputs: 

[1] train.zip: upload a zipped folder containing images to train the model.
After unzipping, the 'train' folder should have one directory for each class
e.g. train/class1 (images for class1), train/class2 (images for class2) and so on..

[2] test.zip: test images to run predictions and check model output

At the beginning of the notebook, you need to define two variables:

num_classes: how many categories images should be classified into

class_labels: names of categories

Note: class_labels should match with the folder names in train.zip directory
