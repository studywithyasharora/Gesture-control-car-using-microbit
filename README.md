# 🚗 Gesture Controlled Car using micro:bit and L298N
📌 Overview

This project demonstrates a gesture-controlled robotic car built using the micro:bit, L298N motor driver, and a 2S (7.4V) Li-ion battery pack. The car moves based on tilt gestures detected by the accelerometer of the transmitting micro:bit.

The system uses wireless communication between two micro:bits:

One micro:bit acts as the gesture controller (transmitter)

The second micro:bit acts as the car controller (receiver)

The robot responds to hand tilts in real-time for forward, backward, left, and right movements.

🛠️ Hardware Used

🧠 micro:bit (2 units)

🔴 L298N Motor Driver

🟡 2 DC Yellow Gear Motors

🔋 2S Li-ion Battery (7.4V)

🚗 Robot Chassis

Jumper Wires

⚙️ Working Principle
🎮 Transmitter (Controller micro:bit)

Uses built-in accelerometer

Detects tilt direction

Sends movement commands wirelessly via micro:bit radio

🤖 Receiver (Car micro:bit)

Receives radio signal

Controls L298N motor driver

Drives motors based on received gesture command

🧭 Gesture Controls
Gesture	Movement
Tilt Forward	Move Forward
Tilt Backward	Move Backward
Tilt Left	Turn Left
Tilt Right	Turn Right
Flat Position	Stop
🔋 Power System

Motors powered by 2S (7.4V) battery

L298N drives motors

micro:bit powered separately for stable operation

Common ground between micro:bit and L298N

This setup ensures:

Stable voltage

Better torque

Reduced voltage drop

Longer battery life compared to single-cell setup

🚀 Features

Wireless gesture control

Real-time response

Smooth motor control using L298N

Efficient 2S battery power system

Simple and scalable design

📈 Applications

Robotics learning projects

STEM education

Embedded systems practice

Wireless communication experiments

Beginner-friendly automation project

🎯 Future Improvements

Speed control using PWM

Obstacle detection integration

Battery voltage monitoring

Mobile app interface

4WD upgrade support

💡 Conclusion

This project demonstrates an effective implementation of wireless gesture-based robot control using micro:bit and L298N. It combines embedded systems, wireless communication, and motor control into a compact educational robotics platform.
