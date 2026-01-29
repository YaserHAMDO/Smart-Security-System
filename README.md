# Smart Security System

## Overview
The Smart Security System is an IoT-based solution designed to secure commercial spaces.<br>
The system uses an ESP8266 microcontroller, LCD display, keypad, alarim and motion sensors all integrated with Firebase for real-time data exchange with an Android app specifically designed for this project.

## Techniques Used
- Android Studio<br>
- Firebase<br>
- Electronic Components: ESP8266, LCD, Keypad, Alarim, Motion Sensors, Relay, Battery, Charger and Voltage regulator.

## Key Features
-**Password Protection:** The system requires a correct password entry within 5 seconds to disarm. If the password is incorrect or not entered, the alarm triggers, sending notifications and SMS alerts to the owner's phone.<br>
<br>
-**Remote Control:** The system can be paused or activated remotely through the Android app, which also allows changing settings like the password or delay time.<br>
<br>
-**Real-time Alerts:** Immediate notifications and SMS alerts are sent if the alarm is triggered.<br>
<br>
-**Firebase Integration:**  Firebase manages system data, enabling smooth communication between hardware and the Android app.<br>


## How It Works
When entering the commercial space, the owner must input a password on the keypad. The system verifies this password against the Firebase database. If the password is correct, the system disarms; otherwise, if the password is incorrect or not entered within the time limit, the alarm is triggered, and notifications and SMS alerts are sent. The system can also be controlled remotely through the Android app, allowing the owner to pause the alarm, adjust settings, and manage the system.


## Images

System Hardware Images:<br>

<p align="left">
  <img alt="a" src="https://github.com/user-attachments/assets/6aeb614e-e3d1-4f14-bd3f-8a5a50d4a9f1" width="30%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="b" src="https://github.com/user-attachments/assets/37fc3e66-ea3a-4c82-9d78-bf5ab77fa9e7" width="30%">
</p>

<p align="left">
  <img alt="c" src="https://github.com/user-attachments/assets/f43d50a8-3d25-4028-925e-ed1d3cce129a" width="30%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="d" src="https://github.com/user-attachments/assets/be7b3f7e-f99f-42b8-90e4-a6b510403aba" width="30%">
</p>



&nbsp;
&nbsp;


Android App Screenshot:
<p align="left">
  <img alt="f" src="https://github.com/user-attachments/assets/54351803-c739-4ae5-a96d-511bd022a20a" width="40%">
</p>
&nbsp;
&nbsp;

