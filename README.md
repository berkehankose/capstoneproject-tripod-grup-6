[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/5mCoF9-h)
# TOBB ETÜ ELE495 - Capstone Project

# Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Video Demo](#usage)
- [Screenshots](#screenshots)
- [Acknowledgements](#acknowledgements)

## Introduction
This project involves creating an autonomous parking vehicle using a JetBot equipped with a Jetson Nano. The JetBot will independently locate its assigned parking spot and park there without crossing any red lines on the platform. For every violation, it will send a penalty point to a mobile app that keeps track of the total penalty points. Each group is given a specific parking space identified by a license plate number. The JetBot starts from a random position and must park within three minutes without touching the red lines. After parking, a completion notification will be sent to the mobile app, and if no parking space is available, the system will inform the app. While carrying out the project, software such as image processing, artificial intelligence and mobile development were used.

![S8374b6d2789f4a61bca6abbf57b5ea3dK jpg_640x640Q90 jpg_](https://github.com/user-attachments/assets/af9d4acc-5c85-47eb-8595-96dfc061a3b9)


## Features
-Hardware
  - Jetbot AI Kit     (https://www.waveshare.com/product/jetbot-ai-kit.htm)
  - MicroSD Card      (https://shorturl.at/YlJxm)
  - 3 x 18650 Battery (https://shorturl.at/T4GhL)
  - Wifi Adapter      (https://shorturl.at/vJibp)
- Applications
  - Operating System and packages
  - Python 3.x
  - JetBot SDK
  - OpenCV
  - Flask
  - Torch
- Services
  -Android Mobile App

## Installation
!! You must have minimum nvidia jetson nano jetpack:jp41 version for installation !!

Commands you need to execute to start the python application.
you need to execute this commands in the min jp41 jetbot docker container
```bash
#  commands
git clone https://github.com/ELE495-2324Summer/capstoneproject-tripod-grup-6/tree/main
cd capstoneproject-tripod-grup-6
cd code
python3 main.py
```
after this bash commands flask server will be running on the jetbot with jetbot's ip

For sending plate number to flask server we will use an Android mobile application. You can use APK directly or you can modify the app code and build on Android Studio IDE.


## Usage
Run the python script from jetbot and send parking command with number plate from mobile app. Your phone and Jetbot should be in the same network!
![WhatsApp Image 2024-07-16 at 03 44 06](https://github.com/user-attachments/assets/7a4164fd-1abc-4eaf-ac27-87316e012eb2)
![WhatsApp Image 2024-07-16 at 03 44 05](https://github.com/user-attachments/assets/39982023-6cb7-459f-9d17-6e9c565d4ab5)


## Video Demo
You can find a video that shows jetbot parking to number 4 via mobile application command.
https://www.youtube.com/watch?v=vKzyPDBvfdU


## Acknowledgements
Give credit to those who have contributed to the project or provided inspiration. Include links to any resources or tools used in the project.

[Contributor 1](https://github.com/cangerek06)
[Contributor 2](https://github.com/berkehankose)
[Resource 1](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-2gb-devkit)
[Resource 2](https://www.waveshare.com/wiki/JetBot_2GB_AI_Kit)
[Resource 3](https://jetbot.org/master/index.html)
[Resource 4](https://developer.nvidia.com/embedded/learn/jetson-nano-2gb-devkit-user-guide)
