# tensorflfow-classifiers
## Boxes
This repository current contains a customized classifier which is able to detect boxes in image/video, or live stream via tensorflow object detection api

![capture](https://user-images.githubusercontent.com/42654960/55675930-0a254a00-5898-11e9-9b4c-b4990371b288.PNG)


The frozen interface graph file can be downloaded via the dropbox link, and this is all you need to detect boxes(by using this as your classifier)

If you are interested in the labeled images and the csv file we used, you can go into the 'images and csv file' folder to check the images we used.
If you want to download the entire folder and add more images, feel free to do so. However, please rememer that the xml file contains the path
of the xml file in my computer, which may be different from yours. Please be aware of that.

The architecture we used to train our own classifier is faster_rcnn_resnet_101. You can download it from the model zoo provided by tensorflow 
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md.

We are currently labeling and adding more classes into this classifier to finally be able to detect all indoor objects. 
