# Automated Transceiver Hot-swap Mechanism

## Introduction
During my 16-weeks internship I was assigned under X-File team. The X-Files team at HPE works on developing and customizing new transceivers and then enabling them on new and/or existing shipping products by running a variety of margin tests. The X-Files program is a long-term program in which new types of transceivers and/or new supplier for current transceivers are being evaluated, qualified and added as part of the overall accessories for HPE products.

## Week 1- 8 
### Creation of automation Script
The automation script mainly consists of few different functionalities:

1.	Calibration – this involves calculating the maximum insertion length and the remove position length of each actuator and provides an array with each value for the specified port by the user.

2.	Perform multiple hot swaps defined by the user – this requires a user input for how many times the hot swap should take place.

3.	Performing a check – this involves performing a check with the connected console through telnet. Check if the link is up (Transceiver is connected), and check if the link is down. (Transceiver is disconnected)

### Implementing a website
After the completion of the automation script, the script was tested using a software called iTest. iTest is a software application primarily used for creating, managing, and conducting various types of tests and assessments. It is often employed in training organizations and businesses to streamline the process of test creation and administration. To make this more user friendly and due to the constraint of  the RAM required to run complex tasks, I was tasked to implement a website. 

![alt text](https://github.com/sufi4414/HPE-Project/blob/main/website-1.png?raw=true)
![alt text](https://github.com/sufi4414/HPE-Project/blob/main/website-2.png?raw=true)

## Week 9-12
During Weeks 8-12, my assignment involved creating an automation script using Python. The project incorporated multiple files named 'ebert,' each containing dimensions and details of a graph resembling an eye. The objective was to assess whether the eye met IEEE standards' criteria. Refer to the figure for a visual representation generated from the 'ebert' file. Notably, this automation script is primarily designed for graphs with a single eye, which are generated only by 25G and 100G transceivers.

![alt text](https://github.com/sufi4414/HPE-Project/blob/main/image.png?raw=true)

## Week 13-16
In the subsequent weeks, following the completion of the automation script for 25G and 100G, I was assigned the task of automating a script for 50G transceivers. This project required a distinct script due to the fact that 50G XVCR (XVCR – Transceivers) involves three Eyes. The 'ebert' file contains details of a single graph and does not encompass the values for the other two eyes. Refer to the figure for a visual representation of the graph plotted by the 50G XVCR. I received multiple images (jpgs) of a 50G graph, each including the three Eye widths and height. This project involved my acquisition of skills in Computer Vision, Image Processing, and OCR techniques.

![alt text](https://github.com/sufi4414/HPE-Project/blob/main/image-2.png?raw=true)

## Skills learned
Some of the technical skills that I picked up during my whole internship journey was:
1.	Python
2.	Java Script
3.	iTest software
4.	Vue
5.	Node.js
6.	HTML
7.	CSS
8.	Postgres SQL
9.	Optical Character Recognition (OCR)
10.	Computer Vision
11.	Image Processing
12.	Automation scripting

Non-technical skills:
1.	Critical thinking
2.	Problem solving skills
3.	Teamwork
4.	Time management
5.	Presentation skills
