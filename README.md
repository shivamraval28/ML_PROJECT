# ML_PROJECT
Object Detection based on Mask R-CNN 

Object detection is an in-demand computer vision approach that detects and distinguishes a particular object from an image frame. Object detection encompasses a wide variety of techniques that are used for it such as image processing, pattern recognition, medical imaging, image annotation, vehicle counting, activity classification and more. Real-time object detection is quite a task as it can be difficult to detect an object for reasons like the object can look different from different angles in different images, size of the object is too small, poor image resolution or sometimes it can be blended and mixed with the background. There are numerous models and methods available in the Computer Vision discipline for the same purpose.

In this project, I tried to achieve mask of the object using pre-trained COCO model by providing bounding box input. Among all the techniques namely Region Bases Convolution Neural Network (R-CNN), Fast R-CNN, Faster R-CNN, Mask R-CNN, Single Shot Detector (SSD), and YOLO (You Only Look Once), I am going to applying Mask R-CNN for instance segmentation on the dataset. I have chosen Mask R-CNN because of having higher accuracy rates as well as better performance. I have trained the model 10 times to get much as accuracy as possible. My model successfully achieved 70% accuracy.

The project is an application based on the work that has been done on Mask R-CNN where the model source code was pre-trained on FPN and ResNet101 and also has the pre-trained weights for MS COCO adn the training code for MS COCO. The below URL provides the location of the M R-CNN

URL: https://github.com/matterport/Mask_RCNN/tree/master/mrcnn

