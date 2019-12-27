---
layout: default
---

<p align="center">
<img src="profile_pic.png" title="profile_pic" width="300" height="350"/>
</p>

I consider myself as Computer Vision and Deep Learning researcher. But, I also love to do projects that are of interest to me irrespective of its domain.  

I am a graduate student at University of California, San Diego (UCSD) specialising in Robotics under the department of Electical and Computer Engineering. I am passionate and interested to work on real life problems in the field of Computer Vision, Deep Learning and Robotics.

Before joining UCSD as a Master's student, I worked at Helwett Packard Enterprise (HPE) as System/Software Engineer for an year. I was part of the security team of HPE "OneView" - Server management software. Previous to it, I also interned at HPE for 6 months. 

I got my undergraduate Bachelor's in Engineering degree from Sri Jayachamarajendra College of Engineering, India in 2018. My major was Electronics and Communication Engineering. I interned as Computer Vision researcher at VigyanLabs Pvt Ltd, India during my penultimate semester.

## Github links
* Open source Python Package to download, validate and upload Certificate Revocation Lists (CRL's) to HPE OneView. [Click_here](https://github.com/HewlettPackard/oneview-python-samples/tree/master/crl_helper)
* Repository link for all my projects - [Click_here](https://github.com/sushruthn96)

## My projects
### Image Captioning using Neural Networks
Developed a Deep learning model to generate textual description of given image. Used Resnet-152 based CNN model (Encoder) to extract features from training images. These features were feeded into an LSTM network (Decoder) to sequentially generate captions of images. This project was based on "Show and tell" model.

Various experiments for improving the model efficiency based on optimizers, GloVe word embeddings, LSTM hidden layer feature size , types of Decoder models (RNN, GRU, LSTM) were carried out. [Link_to_project](https://github.com/sushruthn96/Image_Captioning_ML_IP)

### Automated energy meter reading using machine learning and image processing.
Devised a system which automatically detected the readings of different energy meters. Energy meters like needle based meters and digital meters which had number displays were considered.

To classify meters based on needles and digital displays , a CNN based model  using a custom dataset was developed. Then, for needle-based meters, image preprocessing techniques like edge detection algorithms, Hough line transforms and some trigonometric functions were used to find the readings. On the other hand, Chars74k dataset was used to train a CNN based classifier which in turn was used to detect the numbers in digital display.

Also a GUI interface in Python using Tkinter library for displaying real-time detection of energy meter readings was developed. This project comes a long way in helping to automate the readings of energy meters which cannot be taken out in time critical applications. [Link_to_project](https://github.com/sushruthn96/AMR-with-CV)

### Multi Object detection and localization using SSD
Implemented single shot detector (SSD) detector network to detect and localize objects all at once in a given image. VGG-16 architecture was used as the base network on which extra convolution layers were added to detect higher level features and identify it. NMS algorithm was used at the end to get the relevant bounding boxes.

The loss function was a combination of both classification and regression head of the netowrk. Various experiments for improving the model accuracy based on optimizers, batch size, learning rate and momentum were carried out. Finally a random video was used to test the model efficency. [Link to project](https://github.com/sushruthn96/multi_obj_detection_ssd) 

### Traffic guidance system using Computer Vision
The project aims to automatically turn off the vehicle when the traffic signal becomes red and turn it on when the signal shows green. Further the system varies the speed of the vehicle based on the traffic signs which indicate speed limit. Raspberry Pi was used on a 4 wheeled bot to simulate the system.

To start and stop the vehicle concepts such as CLAHE, Hough circle transform and HSV color transforms were used. Google Vision API was used to detect the traffic speed limit and the subsequent speed control was achieved through the Raspberry Pi interface to the 4 wheeled bot. [Link_to_project](https://github.com/sushruthn96/Automated_Traffic_Guidance_System)

### MNIST dataset classification using CNN
MNIST classification and prediction model was trained using various custom architectures. Maximum accuracy of around 97.2% was obtained. [Link_to_project](https://github.com/sushruthn96/Digit_classification_using_CNN)

###  PID controller for Pluto drone
Participated in a national level robotics competition named "E-yantra" conducted by IIT Bombay, India. We were given the challenge to make a quadcopter follow a land based bot and navigate smoothly to its destination. ROS was used to communicate with the quadcopter from our workstation. PID control algorithms (for stabilizing and flying the quadcopter) were developed in python.

### Biomedical feedback using Wireless sensor nodes
As part of Texas Instruments India Innovation Challenge Design Contest where around 2000 different ideas were submitted by students cutting across different colleges , we developed a wearable module based on CC3200 microcontroller which measures real-time health parameters like heart rate, temperature and blood oxygen levels of a patient which can then be sent to the doctor’s smartphone using Wireless Sensor Node (WSN) technology via a centralized database. In addition, an alert message in case of abnormal health parameters is sent to the doctor’s smartphone. This way, remote monitoring of patients can be enabled and the archaic file system can be completely made obsolete. Our prototype module made the cut into the top 30 startup ideas to be incubated by Indian Institute of Management Bangalore (IIMB) and an initial monetary funding to the tune of 3 Lakh rupees was provided by Texas Instruments for fabricating the wearable module. [Link_to_project_video](https://youtu.be/V2Wcln0M9FM)

### Supermarket billing software
Built a basic version of supermarket billing software using Swings,Applets and multithreading in Java to generate bills based on the items purchased. [Link_to_project]()

### Grab the garb
As part of a 24 hour hacakthon conducted by Tricon Infotech, India, we developed an android app which helps in garbage collection management. It makes the garbage collection system more transparent between the residents and the muncipal authority. [Link_to_project](https://github.com/sushruthn96/grab_the-garb)

