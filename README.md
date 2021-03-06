# Face-Spoofing-Detection
Face Spoofing Detection Using Deep Learning.
---
## Description
A deep-learning pipeline capable of spotting fake vs legitimate faces and performing anti-face spoofing in face recognition systems. It is built with the help of Keras, Tensorflow, and OpenCV. A sample dataset is uploaded in the sample_dataset_folder.

## Method
The problem of detecting fake faces vs real/legitimate faces is treated as a binary classification task. Basically, given an input image, we’ll train a Convolutional Neural Network capable of distinguishing real faces from fake/spoofed faces. There are 4 main steps involved in the task:
 1. Build the image dataset itself.
 2. Implement a CNN capable of performing spoofing detector(Livenessnet).
 3. Train the face spoofing detector network.
 4. Create a Python + OpenCV script capable of taking our trained spoofing detector model and apply it to real-time video.
 5. Create a webplatform to access the spoofing detection algorithm in an interactive manner.

## Contents of this repository
1. sample_liveness_data : contains the sample dataset.
2. Face Liveness Detection -Saketh.pptx : A couple of slides that will give you information on th project and our motivation.
3. demo.py : Our demonstration script will fire up your webcam to grab frames to conduct face liveness detection in real-time.
4. deploy.prototxt : Support file for pretrained face detector. 
5. le.pickle : Our class label encoder.
6. liveness.model : The liveness model file.
7. livenessnet.py : The python file containing the model.
8. res10_300x300_ssd_iter_140000.caffemodel: Pretrained face detector.
9. train_liveness.py: The python script to train the model.

## Working flow
![Untitled Diagram](https://user-images.githubusercontent.com/67184408/113248755-2fa88b00-92db-11eb-81fa-3f7a87c1258f.jpg)

## Further Scope
1. Let’s imagine we want to implement a facial recognition door opener. The system would work well to distinguish between known faces and unknown faces so that only authorized persons have access.
2. Another way that innovators are looking to implement facial recognition is within subways and other transportation outlets. They are looking to leverage this technology to use faces as credit cards to pay for your transportation fee.

