---
layout: single
title: "Academics"
permalink: /academics/
author_profile: false
header:
  overlay_image: /header-banner.jpg
  overlay_filter: 0.5
---

{% include base_path %}

# Academic projects showcase

Projects developed by undergrad students using sensors, neural networks, and microcontrollers. All in a closed-loop, low-power, and low-resource footprint decision-making system.

---

## Embedded Perception-Language-Action Model for Robotics

The goal of this project is to develop an Embedded Perception-Language-Action Model using ASR, LLM, and LiDAR for SLAM-based action planning and control in uncertain dynamic environments. The ROS 2 package for voice-controlled robot navigation and interaction includes voice feedback and environment awareness. The system utilises LiDAR (with the option of incorporating a camera at a later stage) for SLAM and world model construction, and receives motion instructions via voice commands. The voice feedback system utilises Text-to-Speech (TTS) technology. It employs a verification process to ascertain the feasibility of a requested action, as determined by the SLAM-based world model. If the action is deemed unfeasible, the system provides appropriate feedback to the user. Subsequently, the robot autonomously initiates navigation and driving commands.

**Team:**
- Maximilian Werzinger - [werzingerma89360@th-nuernberg.de](mailto:werzingerma89360@th-nuernberg.de)
- Christopher Witzl - [witzlch88229@th-nuernberg.de](mailto:witzlch88229@th-nuernberg.de)
- Felix Rittmaier - [rittmaierfe88977@th-nuernberg.de](mailto:rittmaierfe88977@th-nuernberg.de)

![Perception-Language-Action Model](/images/academics/perception-language-action.jpg)

---

## TinyML Flight Mode Detector

The goal of this project is to develop a microcontroller that can detect the different flight modes during the flight of a glider/sailplane. During the duration of one flight, the plane might be in one of the standard flight modes/phases: Pre take-off, Take-off, ..., Landing, Landed. The microcontroller should leverage a machine learning model that is trained to classify these flight modes by relying only on IMU data as well as the current air pressure. The IMU module measures acceleration and gyroscopic rotation in three axis whilst the pressure sensor measures the barometric pressure of the surrounding air (lower pressure means higher altitude). The project used an Arduino Nano 33 BLE Sense with a LSM9DS1 (IMU sensor), and a LPS22HB (barometer).

**Team:**
- Denis Engelhardt - [engelhardtde103270@th-nuernberg.de](mailto:engelhardtde103270@th-nuernberg.de)
- Nils Weber - [weberni76153@th-nuernberg.de](mailto:weberni76153@th-nuernberg.de)

![Flight Mode Detector 1](/images/academics/flight-mode-1.jpg)
![Flight Mode Detector 2](/images/academics/flight-mode-2.jpg)
![Flight Mode Detector 3](/images/academics/flight-mode-3.jpg)

---

## Public Transport Utilisation via Minimally Invasive Sensing Systems

The goal of this project is to develop a microcontroller that can detect the different flight modes during the flight of a glider/sailplane. During the duration of one flight, the plane might be in one of the standard flight modes/phases: Pre take-off, Take-off, ..., Landing, Landed. The microcontroller should leverage a machine learning model that is trained to classify these flight modes by relying only on IMU data as well as the current air pressure. The IMU module measures acceleration and gyroscopic rotation in three axis whilst the pressure sensor measures the barometric pressure of the surrounding air (lower pressure means higher altitude). The project used an Arduino Nano 33 BLE Sense with a LSM9DS1 (IMU sensor), and a LPS22HB (barometer).

**Team:**
- Denis Engelhardt - [engelhardtde103270@th-nuernberg.de](mailto:engelhardtde103270@th-nuernberg.de)
- Nils Weber - [weberni76153@th-nuernberg.de](mailto:weberni76153@th-nuernberg.de)

![Public Transport 1](/images/academics/public-transport-1.jpg)
![Public Transport 2](/images/academics/public-transport-2.jpg)

---

## Conductor ML

The core idea behind ConductorML is to use the onboard IMU (accelerometer and gyroscope) of the Arduino Nano 33 BLE to recognise hand gestures performed by the user. The project draws inspiration from and builds upon the Magic Wand repository by Peter Warden.

Instead of using raw accelerometer and gyroscope data directly for gesture classification, the system estimates the device's orientation by integrating gyroscope data over time. It then tracks orientation changes to approximate gesture movement. Using recent motion history, a 2D stroke representation of the gesture is extracted and rasterised into an image.

These 2D images are then classified into gesture categories by a small convolutional neural network, implemented using TensorFlow Lite for Microcontrollers. The model runs directly on the Arduino Nano 33 BLE's onboard neural processing unit, enabling efficient, real-time inference on embedded hardware. The classification result is transmitted to a central computer and displayed in a custom-built web interface. This interface not only visualises the recognised gestures but also maps them to playback triggers and volume changes for different sections of the digital orchestra—enabling intuitive, real-time control through gesture alone.

**Team:**
- Eleonora Schubert - [schubertel75720@th-nuernberg.de](mailto:schubertel75720@th-nuernberg.de)
- Kristoph Kolert - [kolertkr103269@th-nuernberg.de](mailto:kolertkr103269@th-nuernberg.de)
- Tan Phat Nguyen - [nguyenta100556@th-nuernberg.de](mailto:nguyenta100556@th-nuernberg.de)
- Robin Feldmann - [feldmannro80685@th-nuernberg.de](mailto:feldmannro80685@th-nuernberg.de)

![Conductor ML 1](/images/academics/conductor-ml-1.jpg)
![Conductor ML 2](/images/academics/conductor-ml-2.jpg)
![Conductor ML 3](/images/academics/conductor-ml-3.jpg)
![Conductor ML 4](/images/academics/conductor-ml-4.jpg)
![Conductor ML 5](/images/academics/conductor-ml-5.jpg)
![Conductor ML 6](/images/academics/conductor-ml-6.jpg)

---

## SpotiMotion - Inertial motion controller for Spotify

Embedded neural network algorithm design for inertial motion understanding and closed-loop control. SpotiMotion is a project that allows interaction with Spotify using gesture recognition with TinyML and an Arduino Nano 33 BLE board.

A machine learning model was trained using EdgeImpulse to recognize gestures from the Arduino. The gestures are recognized using the accelerometer and gyroscope sensors from the board. The detected gesture is then sent to a connected computer running a Python script that controls Spotify (using the SpotiPy library) over their API.

**Team:**
- Lea Schaab - [schaable79981@th-nuernberg.de](mailto:schaable79981@th-nuernberg.de)
- Timo Maußner - [maussnerti75065@th-nuernberg.de](mailto:maussnerti75065@th-nuernberg.de)
- Jonas Reif - [reifjo96249@th-nuernberg.de](mailto:reifjo96249@th-nuernberg.de)

![SpotiMotion](/images/academics/spotimotion.jpg)

---

## Camera-LiDAR fusion for embedded depth estimation

Embedded neural network algorithm design for LiDAR and CMOS camera fusion embedded on a mobile robot platform—a tool to enhance planning and kinematic control of wheeled mobile robots.

The project uses 2D lidar or 2D lidar depth data with camera images to generate accurate depth information. This is done using a depth estimation model (such as MiDAS or Depth-Anything V2), which can (more or less) estimate the depth or relative depth between objects in an image. These estimates are then calibrated with the lidar data to obtain more accurate depth information from the image.

The project uses ROS2 to process the sensor data and for communication between the individual program parts, as well as Python code to fuse the generated depth estimates, the lidar and the camera. The project's goal is to accurately estimate 3D distance data even when no 3D sensors are present, thus making expensive 3D lidar systems redundant in certain applications.

**Team:**
- Maximilian Werzinger - [max.werzinger@franken-online.org](mailto:max.werzinger@franken-online.org)
- Christopher Witzl - [christopher.witzl@gmx.de](mailto:christopher.witzl@gmx.de)

![Camera-LiDAR Fusion](/images/academics/camera-lidar-fusion.jpg)

---

## Event-based camera-LiDAR fusion for clustering-based depth estimation

This project addresses the challenge of estimating depth using a single DVS (Dynamic Vision Sensor) camera and a 2D LiDAR. While DVS cameras capture changes in light rather than full images, they lack native depth information.

Most existing solutions rely on two DVS cameras for stereo depth estimation. Still, this project introduces a more cost-effective approach by using a 2D LiDAR instead, eliminating the need for expensive 3D LiDAR systems.

Built using ROS2 for communication and data processing, the system can run on various platforms, including wheeled robots with Jetson Nano or similar hardware.

Since 2D LiDAR measures depth in a single plane, a custom clustering algorithm was developed to estimate the depth of objects outside this plane, such as a person's arms.

The fusion algorithm aligns the LiDAR's measurements with dynamic events from the DVS, creating a unified point cloud, that can be visualized in real time.

This approach enhances depth perception for robotics and other applications while maintaining affordability.

**Team:**
- Annika Igl - [aiglgg@web.de](mailto:aiglgg@web.de)
- Timo Kapellner - [timo.kapellner@gmail.com](mailto:timo.kapellner@gmail.com)

![Event-based Camera-LiDAR](/images/academics/event-camera-lidar.jpg)

---

## Embedded inertial data fusion neural network for gamepad development

Embedded neural network algorithm design for fusing and processing inertial data on a TinyML Arduino Nano BLE board. Motion processing was used to control a game.

**Team:**
- Philipp Kremling - [kremlingph95027@th-nuernberg.de](mailto:kremlingph95027@th-nuernberg.de)
- Igor Bodyagin - [bodyaginig67371@th-nuernberg.de](mailto:bodyaginig67371@th-nuernberg.de)

![Gamepad](/images/academics/gamepad.jpg)

---

## PlantControlling - Optimizing plant growth with Embedded Fuzzy Logic Control

Embedded fuzzy logic controller design for fusing and processing humidity and light data for controlling a water pump on a TinyML Arduino Nano BLE board.

**Team:**
- Laurin Müller - [muellerla89125@th-nuernberg.de](mailto:muellerla89125@th-nuernberg.de)
- Marco Tong - [tongma89472@th-nuernberg.de](mailto:tongma89472@th-nuernberg.de)

![Gamepad 1](/images/academics/plant-1.jpg)
![Gamepad 2](/images/academics/plant-2.jpg)

---

## SPICEnet Neural Network Porting on iOS

The project focused on porting an open-source neural network called [SPICEnet](https://pypi.org/project/spicenet/) to a mobile setup. The [Sensorimotor Processing, Intelligence, and Control at the Edge Network](https://github.com/th-nuernberg/spicenet) is a novel, lightweight neural network designed for sensor fusion and control, inspired by biological neural computation mechanisms. The project aimed to develop a mobile demonstrator codebase with a graphical user interface (GUI) that allows for extensive network parameterisation, selection of input sources, and visualization of network elements. The application was designed to be portable across different operating systems, specifically Android and iOS.

**Team:**
- Omar Ashour - [omar.ashour963@gmail.com](mailto:omar.ashour963@gmail.com)

![SPICEnet iOS](/images/academics/spicenet-ios.jpg)

---

## Spikeball Camera-based Detection and Understanding

The project aims to track the ball in a roundnet game using ML-supported object recognition. More precisely, the goal is to determine whether the ball bounces off the net at the permitted angle. Two approaches were trialled for this: YOLOv8 and FOMO (Feature Optimised Mobile Object detection) from Edge Impulse. For the deployment, the entire system was run on an NVIDIA Jetson Nano. The aim was to bundle all processing steps - from camera integration to classification - on the device and make them executable in real-time.

**Team:**
- Michael Harter - [hartermi98624@th-nuernberg.de](mailto:hartermi98624@th-nuernberg.de)
- Laurin Kerntke - [kerntkela84836@th-nuernberg.de](mailto:kerntkela84836@th-nuernberg.de)
- Jan Staubringer - [staubringerja98627@th-nuernberg.de](mailto:staubringerja98627@th-nuernberg.de)

![Spikeball Detection](/images/academics/spikeball.jpg)

---

## Embedded Bee Tracking for Plants

The goal of Bee Tracking for Plants is to track and count bees visiting a plant using TinyML on an Arduino Nano 33 BLE Sense with an OV7675 camera module. The neural network running on the TinyML board can distinguish between flowers/plants and bees/insects, and count the detected bees/insects. The deployment is weather-resistant housing for outdoors and uses a colour that is neutral for bees. It has a reliable power source for extended operation and data storage for detection counts and logging.

**Team:**
- Jonathan Pohl - [pohljo85440@th-nuernberg.de](mailto:pohljo85440@th-nuernberg.de)
- Laura Diolosa - [diolosala85070@th-nuernberg.de](mailto:diolosala85070@th-nuernberg.de)

![Bee Tracking](/images/academics/bee-tracking.jpg)

---

## Inertial Pong Game

This project combines a classic Pong game with modern embedded machine learning (TinyML). The goal is to control a Pong game not with a keyboard, but with movements detected by an Arduino Nano 33 BLE Sense board using motion sensors (acceleration, gyroscope, magnetometer).

**Team:**
- Beatrice Tichy - [tichybe71463@th-nuernberg.de](mailto:tichybe71463@th-nuernberg.de)
- Leonhard Haselbek - [haselbekle100200@th-nuernberg.de](mailto:haselbekle100200@th-nuernberg.de)

![Inertial Pong](/images/academics/inertial-pong.jpg)

---

## Embedded Playing Cards Detector

This project implements an AI-powered playing card classification on an Arduino Nano 33 BLE Sense Lite microcontroller and an OV7675 Camera Module. For the training process, the project used the Edge Impulse platform with an object detection pipeline.

**Team:**
- Christoph Nickel - [nickelch84657@th-nuernberg.de](mailto:nickelch84657@th-nuernberg.de)
- André Fürch - [fuerchan84463@th-nuernberg.de](mailto:fuerchan84463@th-nuernberg.de)

![Playing Cards Detector](/images/academics/playing-cards.jpg)

---

## Inertial and Biosignals Fusion for VR Simulations

This project implemented a data fusion algorithm, based on the Madgwick filter, for IMU data of an Arduino BLE 33 with the data of an EMG electrode set in order to improve hand movement understanding. Such technologies could, for example, be used in VR and robotic tele-operation scenarios.

**Team:**
- Eric Beers - [beerser92280@th-nuernberg.de](mailto:beerser92280@th-nuernberg.de)
- Cedric Miss - [missce92375@th-nuernberg.de](mailto:missce92375@th-nuernberg.de)

![VR Biosignals 1](/images/academics/vr-biosignals-1.jpg)
![VR Biosignals 2](/images/academics/vr-biosignals-2.jpg)

---

## Classification of Door Closure States Using TinyML

This project presents a TinyML-based system for classifying door closure states using vibration data collected by a microcontroller. The primary objective was to accurately detect and distinguish between different door actions, such as "door open" and "door closed", by training a neural network directly on embedded hardware. The initial objective was to detect not only basic door states but also the precise position of the lock cylinder, which could be beneficial for firefighting operations.

**Team:**
- Peter Filipp - [filipppe78848@th-nuernberg.de](mailto:filipppe78848@th-nuernberg.de)
- Yannick Kern - [kernya84822@th-nuernberg.de](mailto:kernya84822@th-nuernberg.de)
- Lukas Wißmeyer - [wissmeyerlu80194@th-nuernberg.de](mailto:wissmeyerlu80194@th-nuernberg.de)
- Burak Toptas - [toptasbu84460@th-nuernberg.de](mailto:toptasbu84460@th-nuernberg.de)

![Door Closure 1](/images/academics/door-closure-1.jpg)
![Door Closure 2](/images/academics/door-closure-2.jpg)
![Door Closure 3](/images/academics/door-closure-3.jpg)