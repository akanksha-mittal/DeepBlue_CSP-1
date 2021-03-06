# YOLO-Object-Detection
## Description
The project involved building an API that performs object detection on an image. The API takes an image as input and returns a response JSON which has all the bounding boxes of the captured items on the image and their coordinates.

**Object Detection Algorithm used:** YOLO v2 (aka YOLO 9000)

**Object Detection Library used:** Darkflow

**Python Backend Framework used:** Flask

## What is YOLO v2 (aka YOLO 9000)
YOLO9000 is a high speed, real time detection algorithm that can detect on OVER 9000! (object categories). It was originally written in a deep learning framework called 'Darknet'. Darknet was written in C language. To make it user-friendly, a tensorflow version of it called as 'Darkflow' was created.

## Step1 - Requirements
- Python 3.5 or 3.6
- Tensorflow (tutorial GPU verions https://www.youtube.com/watch?v=RplXYjxgZbw&t=91s)
- openCV (https://www.lfd.uci.edu/~gohlke/pythonlibs/)

## Step2 - Download the Darkflow repo
https://github.com/thtrieu/darkflow

Extract the files somewhere locally.

## Step3 - Build the library
Open an cmd window and type python setup.py build_ext --inplace

## Step 4 - Download a weights file
Download the YOLOv2 608x608 weights file here (https://pjreddie.com/darknet/yolo/)

NOTE: Create a folder named as 'bin' and put the wights file in it.




# API SCREENSHOTS

## 1. Intro upload window 

![screenshot 27](https://user-images.githubusercontent.com/23147497/39966783-1569b6a6-56cf-11e8-9891-938ff4bd2de9.png)

![screenshot 28](https://user-images.githubusercontent.com/23147497/39966790-2c47158a-56cf-11e8-905a-da90d6c457d7.png)

![screenshot 29](https://user-images.githubusercontent.com/23147497/39966797-3ac5e2c6-56cf-11e8-9530-48c57eab0c92.png)

## 2. Response

![screenshot 32](https://user-images.githubusercontent.com/23147497/39966803-4739051a-56cf-11e8-8942-85eab2bbd758.png)

## 3. Responses to other test images

![screenshot 33](https://user-images.githubusercontent.com/23147497/39967056-eaa1fa06-56d2-11e8-8dfc-be0273aa5854.png)

![screenshot 34](https://user-images.githubusercontent.com/23147497/39967058-ed8af3e4-56d2-11e8-96fd-79f50c6ff3cc.png)

![screenshot 35](https://user-images.githubusercontent.com/23147497/39967059-f3c2ea78-56d2-11e8-8f59-70aebb0598ba.png)

![screenshot 36](https://user-images.githubusercontent.com/23147497/39967060-f6296f1c-56d2-11e8-8a5f-894baa3bcc3b.png)

![screenshot 37](https://user-images.githubusercontent.com/23147497/39967064-0080b038-56d3-11e8-9433-655313a2a174.png)

![screenshot 38](https://user-images.githubusercontent.com/23147497/39967065-02814082-56d3-11e8-8b61-e8a6d977cbe9.png)


