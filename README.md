# MaRS-Model

# Abstract

Eyes of skulls that stare right at you and follow your movement. You will use image processing to detect a person and use robotic eyes to follow them.

# Team Members

<li>Shubham Sharele</li>
<li>Ujwal Gupta</li>
<li>Yash Jain</li>
<li>Yash aggarwal</li>

# Mentors

<li>Mohit Gupta</li>
<li>Prashant Shekhar Singh</li>

# Pre-Requisites
 
 <b>Hardware:</b>
<ol>
<li>Arduino UNO</li>
<li>1 Servo motor MG995</li>
<li>3 High Torque Stepper Motors</li>
<li>12V DC Power Adapter</li>
<li>Jumper Wires</li>
<li>LM317T Voltage Divider</li>
<li>Resistors</li>
<li>Breadboard</li>
<li>DST</li>
<li>Hollow Circular Rod</li>
<li>Motor Mount</li> 
<li>Camera for image processing</li>  
</ol>

 <b>Software:</b>
 
•	Arduino
•	Open-cv
• IP Webcam

# Working and Basics
Basically, the mobile camera sends video frames to OpenCV running on a PC using IP Webcam. If OpenCV detects a light it will track it and calculate its center's X,Y coordinates. The coordinates are then passed on to the Arduino via a serial USB connection. The Arduino controls the movement of the webcam with the help of 4 pan/tilt servos to follow the detected face.On servos skulls are mounted and in there eys led's are fixed. When they rotates the skull appears as they are staring towards the person. 


# Inferance
This project is good combination of open-cv and arduino. 
