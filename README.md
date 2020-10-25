README.md

object detection work with opencv =>


1) Download and install Python 3.6 from official Python Language website
https://www.python.org/downloads/release/python-360/

2) Install the following dependencies via pip:

i. TensorFlow

pip3 install tensorflow==1.13.1

ii. OpenCV

pip3 install opencv-python

iii. Keras

pip3 install keras==2.2.4

iv. Numpy

pip3 install numpy==1.16.1

v. ImageAI

pip3 install imageai --upgrade


3) First we have to put all the files in one folder of our current directory.
 Download the RetinaNet model file that will be used for object detection via this link -  https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5
 Also add this file. These all file which we use should be in only one folder.
 
 
4) Then run that FirstDetection.py and you will get some output like this,
person : 55.8402955532074

person : 53.21805477142334

person : 69.25139427185059

person : 76.41745209693909

bicycle : 80.30363917350769

person : 83.58567953109741

person : 89.06581997871399

truck : 63.10953497886658

person : 69.82483863830566

person : 77.11606621742249

bus : 98.00949096679688

truck : 84.02870297431946

car : 71.98476791381836


After then you have to check the result in your folder you will get another picture with object detection.
That's all.
 


