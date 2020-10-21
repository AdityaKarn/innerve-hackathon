# innerve-hackathon

This project is for the igdtu data science hackathon 2020

## Project : Blind People Helper

### What it does?

Main objective is two things : Lane detection and object recognition.

Lane detection is done through two methods:
  1. OpenCV houghes transformation 
  2. Using CNN
  
Object detection is done through a standard implementation of the YOLO algorithm.

### How to run?

1. 
2. CNN lane detection :
  
  Add validation values from dataset_labeller/val_labels to your google drive
  run Untitled10.py in google colab
  Remember to upload model_1.h5 to your runspace (can be found in the respective folder)
  
3. YOLO implementation
  
  Download weights from [https://pjreddie.com/media/files/yolov3.weights](here)
  Add images to your gdrive/val2017/
  Add weights and everything in the files folder to your gdrive/files/
  Run the ipynb in google colab
  
