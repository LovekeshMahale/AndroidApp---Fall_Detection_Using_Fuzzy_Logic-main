# Android Application for Fall Detection and Alert System Using Fuzzy Logic (Simulink)
This project demonstrates a fall detection system that leverages fuzzy logic within Simulink (MATLAB) to simulate an Android application. The app is designed with the following features:

## Features
### 1. Accelerometer Data Monitoring
- Continuously track accelerometer data while the app is active to detect falls based on the readings.

### 2. Audio Recording and Sound Level Measurement
- Automatically activate the phone's microphone upon detecting a fall to record audio and assess the sound level.
  
### 3. Estimate Danger Level Using Fuzzy Logic
- Utilize fuzzy logic to evaluate sound levels (Low, Medium, High) and accelerometer data (Low, Medium, High), determining the danger level (Low, Medium, High) based on these inputs.

### 4. Alert System with Audio and Location:
- If a high danger level is detected, send an alert to a designated phone via TCP/IP or UDP, including the recorded audio and the phone’s GPS location.

### 5. Buzzer Activation:
- Trigger a buzzer sound on the phone if the danger level is assessed as Medium or High, with the sound intensity proportional to the detected danger level.

## Course Context:

This project was developed as part of the Control Systems course at the Indian Institute of Technology Gandhinagar (IIT Gandhinagar), under the guidance of [Prof. Nithin V. George](https://www.iitgn.ac.in/faculty/ee/fac-nithin).
