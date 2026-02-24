# Transfer-Learning
template to build a custom model using transfer learning

image-classifier.ipynb shows a template to easily build a custom model
for Image Classification task using Transfer Learning approach on
any given dataset 

Inputs: 

[1] train.zip: zipped folder containing images to train the model
After unzipping, the 'train' folder should have one directory for each class
e.g. train/class1 (images for class1) train/class2 (images for class2) and so on..

[2] test.zip: test images to run predictions and check model output

At the beginning of the notebook, you need to define two variables

num_classes: for your machine learning image classification task
class_labels: names of categories to classify given images into

Note: class_labels should match with the folder names in train.zip directory
