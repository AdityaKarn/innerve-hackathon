# innerve-hackathon

This project is for the igdtu data science hackathon 2020

## Project : Path detection for visually impaired

### What it does?

Main objective is two things : Lane detection and object recognition.

Lane detection is done through two methods:
  1. OpenCV houghes transformation 
  2. Using CNN
  
Object detection is done through a standard implementation of the YOLO algorithm.

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
  
