## Academic projects


### Modernization and GDP
Analyzed GDP as an indicator of socio-economic factors of a country. Data analysis and visualization through scatter, bubble and box plots using Pandar, matplotlib was carried out. [[code]](https://github.com/hehuntle/ECE_143_PROJECT) [[presentation]](https://docs.google.com/presentation/d/e/2PACX-1vRRaKvQXxxximydtkGFd5Wt3vjgJn7gqh-Dbdp6bCiD3yyaEyz_xFFDoPII9xedHjYMPlM5HW9tmxPu/pub?start=false&loop=false&delayms=3000)

### Image Captioning using Neural Networks <span style="font-size:smaller;"> (2019) </span>
Developed a Deep learning model to generate textual description of given image. Used Resnet-152 based CNN model (Encoder) to extract features from training images. These features were feeded into an LSTM network (Decoder) to sequentially generate captions of images. This project was based on "Show and tell" model.

Various experiments for improving the model efficiency based on optimizers, GloVe word embeddings, LSTM hidden layer feature size , types of Decoder models (RNN, GRU, LSTM) were carried out. [[code]](https://github.com/sushruthn96/Image_Captioning_ML_IP) [[report]](https://github.com/sushruthn96/Image_Captioning_ML_IP/blob/master/Image_captioning_report.pdf)

### Automated energy meter reading using machine learning and image processing <span style="font-size:smaller;"> (Undergrad thesis 2018) </span>
Devised a system which automatically detected the readings of different energy meters. Energy meters like needle based meters and digital meters which had number displays were considered.

To classify meters based on needles and digital displays , a CNN based model  using a custom dataset was developed. Then, for needle-based meters, image preprocessing techniques like edge detection algorithms, Hough line transforms and some trigonometric functions were used to find the readings. On the other hand, Chars74k dataset was used to train a CNN based classifier which in turn was used to detect the numbers in digital display.

Also a GUI interface in Python using Tkinter library for displaying real-time detection of energy meter readings was developed. This project comes a long way in helping to automate the readings of energy meters which cannot be taken out in time critical applications. [[code]](https://github.com/sushruthn96/AMR-with-CV) [[report]](https://github.com/sushruthn96/AMR-with-CV/blob/master/finalreport.pdf)

### Biomedical feedback using Wireless sensor nodes (2017)
As part of Texas Instruments India Innovation Challenge Design Contest where around 2000 different ideas were submitted by students cutting across different colleges , we developed a wearable module based on CC3200 microcontroller which measures real-time health parameters like heart rate, temperature and blood oxygen levels of a patient which can then be sent to the doctor’s smartphone using Wireless Sensor Node (WSN) technology via a centralized database. In addition, an alert message in case of abnormal health parameters is sent to the doctor’s smartphone. This way, remote monitoring of patients can be enabled and the archaic file system can be completely made obsolete. Our prototype module made the cut into the top 30 startup ideas to be incubated by Indian Institute of Management Bangalore (IIMB) and an initial monetary funding to the tune of 3 Lakh Indian rupees was provided by Texas Instruments for fabricating the wearable module. [[video]](https://youtu.be/V2Wcln0M9FM)

### Traffic guidance system using geometric computer vision <span style="font-size:smaller;"> (2016) </span>
The project aims to automatically turn off the vehicle when the traffic signal becomes red and turn it on when the signal shows green. Further the system varies the speed of the vehicle based on the traffic signs which indicate speed limit. Raspberry Pi was used on a 4 wheeled bot to simulate the system.

To start and stop the vehicle concepts such as CLAHE, Hough circle transform and HSV color transforms were used. Google Vision API was used to detect the traffic speed limit and the subsequent speed control was achieved through the Raspberry Pi interface to the 4 wheeled bot. [[code]](https://github.com/sushruthn96/Automated_Traffic_Guidance_System)

### Grab the garb (2017)
As part of a 24 hour hacakthon conducted by Tricon Infotech, India, we developed an android app which helps in garbage collection management. It makes the garbage collection system more transparent between the residents and the muncipal authority. [[code]](https://github.com/sushruthn96/grab_the-garb)

###  PID controller for Pluto drone (2016)
Participated in a national level robotics competition named "E-yantra" conducted by IIT Bombay, India. We were given the challenge to make a quadcopter follow a land based bot and navigate smoothly to its destination. ROS was used to communicate with the quadcopter from our workstation. PID control algorithms (for stabilizing and flying the quadcopter) were developed in python. [[code]](https://github.com/sushruthn96/pid_controller_for_a_drone)