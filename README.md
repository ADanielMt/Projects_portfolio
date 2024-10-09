
## About Me

### Name
Alejandro Daniel Matías Pacheco

### Education
* Mechatronics Engineer
* MSc in Artificial Intelligence

### Overview
Hello, my name is Daniel Matías, I am a former Mechatronics engineer, passionate about software development, electronics and aerospace. My goal is to develop embedded software projects and apply machine learning and data science in aerospace or biomedical areas. My hobbies are STEM outreach and astrophotography. I have finished the master in Artificial Intelligence program, wating to get my degree. Currently, I work at GE Aerospace in Analytics area.

### Contact
- Email: danielma65.@gmail.com
- LinkedIn: [Alejandro Daniel Matías Pacheco](https://www.linkedin.com/in/daniel-mat-pac/)

## Data science and embedded programming Portfolio ##

## [YOLOv8 based autonomous landing system for Tello MAV](https://github.com/ADanielMt/MAV-Autonomous-Landing-Tello-YOLO-ROS)
This repository contains the step by step, scripts and demonstrative videos of an autonomous landing system for a Micro Aerial Vehicle, also know ans micro drones. In this project You Only Look Once version 8 (YOLOv8) detector is used to identify a QR landing marker. A Multi-Layer Perceptron (MLP) is trained to estimate the relative height between the MAV and the moving platform. A Proportional-Integral (PI) controller calculates and sends control commands to the MAV for landing, using Robot Operating System (ROS) as an interface. The landing is performed on a mobile platform.

## [Control of Active Upper Limb Prosthesis Using Artificial Intelligence and Force Feedback](https://github.com/ADanielMt/EMG_real_time_Neural_Network_classifier_hand_prosthesis)
This repository contains the files used to control an active robotic hand prosthesis using EMG signals. The signals are acquired using an EMG MYO Armband from Thalmic Labs and a Raspberry Pi 3B+. The data acquired is stored and feature extraction is performed. Then, real time classification of hand movements and grasps is done using a pre-trained neural network. The result of the classification is codified and sent to a master microcontroler named "MicroRDR" (ATMega328P), which decodes the result and sends a signal to two slave microcontrollers, MicroPLM and MicroIMA. Those microcontrollers contains specific routines to control the fingers of an active robotic hand prosthesis. The microcontrollers also receive signals of support sensors (Motors angular positions, Force Sensing Resistors - FSR, Limit Switch). Using this information, the microcontrollers controls the motors so the robotic hand prosthesis actively reachs the desired position (the hand movement classified by the Neural Network Model).

## [Design, construction and control of an automated feeding robotic arm for people with disabilities](https://github.com/ADanielMt/Feeder_Robotic_Arm)
Codes in C++ used to control an automated feeding robotic arm for people with disabilities, using an arduino board and a user interface made with Unreal Engine. This robotic arm is controlled using Direct and Inverse Kinematics to reach a desired position, also, some trajectories used to feed a person are implemented as a machine state routine.

## [Feature Extraction and Training/Test of a Neural Network for EMG signals classification](https://github.com/ADanielMt/EMG_train_NN)
Scripts used to extract, train and test (offline test) a Feedforward Neural Network with EMG signal of the upper limb. This project is the base bone of the Prostesis Control. The scripts are implemented in python and they were ran in a Raspberry Pi 3B in order to adquire EMG signals and perform feature extraction in real time. The train and test scripts are Ran offline in the raspberry.

## [Lactose/Whey price prediction using ARIMA models](https://github.com/ADanielMt/Price_prediction_ARIMA)
Implementation of ARIMA model for Lactose and Whey price prediction. Self implemented and library aided versions. Data preprocessing is performed to order the data and join equivalent columns. 

## [Titanic survivors prediction](https://github.com/ADanielMt/Titanic_prediction)
Implementation of a model to predict which passengers survived to the Titanic accident. Data preprocessing is done in order to clean the data and improve the performance of the k-means clustering algorithm.

### Others
* Data engineering and data science for supply chain. GE Aerospace.
* Python projects automation in Dataiku and using server crontabs. GE Aerospace.
* Data visualization with Spotfire. GE Aerospace.
* Server apps containers management. GE Aerospace.
* Analytics engineer for GE Aerospace.





