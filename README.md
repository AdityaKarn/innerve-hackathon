# innerve-hackathon

This project is for the igdtu data science hackathon 2020

## Project : Path detection for visually impaired

### What it does?

Main objective is two things : Lane detection and object recognition.

Lane detection is done through two methods:
  1. OpenCV houghes transformation 
  2. Using CNN
  
Object detection is done through a standard implementation of the YOLO algorithm.

### Overview 

#### Lane detection using Hough Transformation
* Used openCV for producing a lane detector. Inherent techniques used were Canny detection and Hough transforms.
* Used Convolutional Neural Networks to work upon the limitations of the openCV model.
* Used the standard YOLO algorithm for the implementation of the object detectors. 
> You can view [harshit's repo to know more](https://github.com/TheGupta2012/RAAHI).


#### Lane detection using CNN
* Used a custom built openCV app to label frames of the dataset (a valid lane to go through)
* Made a sequential CNN that learns the dataset
* Predicts a valid path and direction to go.

![example](https://raw.githubusercontent.com/AdityaKarn/innerve-hackathon/master/CNN_lane_detection/cnn1.jpg)

#### Object detection using the YOLO algorithm
* Implemented the YOLO algorithm to detect object on the streets
* Detected various class of objects ranging from people , car and animals
* Used a very deep Darknet-53 model to predict the same

![example](https://raw.githubusercontent.com/AdityaKarn/innerve-hackathon/master/YOLO/yolo1.png)

### How to run?

1. OpenCV lane detection : 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Run the ipynb in colab

2. CNN lane detection :
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Add validation values from dataset_labeller/val_labels to your google drive
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  run Untitled10.py in google colab
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Remember to upload model_1.h5 to your runspace (can be found in the respective folder)
  
  
3. YOLO implementation
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Download weights from [here](https://pjreddie.com/media/files/yolov3.weights)
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Add images to your gdrive/val2017/
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Add weights and everything in the files folder to your gdrive/files/
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Run the ipynb in google colab
  
