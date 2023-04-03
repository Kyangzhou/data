## Introduction

This is an implementation of submitted paper:



## Methodology

The basic outline of the method is as follows.We use yolov5 to detect rice panicles in the field, and use the trained detection model and combine Deepsort for rice panicle tracking. We also use the resnet50 model to classify whether the detected and tracked rice panicles are vigorous flowering or not.
- Using yolov5 to detect rice panicles
- Using yolov5+Deepsort to track rice panicles
- Using resnet50 to classify the panicles
