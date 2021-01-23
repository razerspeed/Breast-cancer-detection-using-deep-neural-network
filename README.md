# Breast-cancer-detection-using-deep-neural-network

This is a self case study to find mitosis cell in images using deep learning techniques.

First unet.ipynb file is run which create a image segmentation model using dataset 1
using this model we find the segmented images for dataset 2

Then using the seg2bounding_box1.ipynb file we convert the segmented image to get the bounding box coordinate. It create the file annotation.txt

Using the file we train our Faster RCNN model using the frcnn.ipynb file.
First RPN model is trained and then the whole model is trained just like the original paper.


The Faster RCNN code is inspired from https://github.com/yhenon/keras-frcnn/

Medium article link https://medium.com/analytics-vidhya/breast-cancer-detection-using-deep-neural-network-6691a472d7a7
