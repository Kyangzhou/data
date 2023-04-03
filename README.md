## Introduction

This is an implementation of submitted paper:



## Methodology

The basic outline of the method is as follows.We use yolov5 to detect rice panicles in the field, and use the trained detection model and combine Deepsort for rice panicle tracking. We also use the resnet50 model to classify whether the detected and tracked rice panicles are vigorous flowering or not.
- Using yolov5 to detect rice panicles
- Using yolov5+Deepsort to track rice panicles
- Using resnet50 to classify the panicles

 ## Results
 - The panicle detection results are in the floder of yolov5/images.
 
 - The panicle tracking results are in our releases named  track.zip, in the floder of inference.
 
 - The panicle classification resulst are in the floder of ResNet/test.
 
## Models
Our panicle detection model is in our releases named Pdetection.pt.

Our panicle classification model is in our releases named resnet50vf.pth.

