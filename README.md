# Line-Following Robot using Arduino

This project demonstrates a simple **line-following robot** built with Arduino, IR sensors, and DC motors. 
The robot can detect a black line on a white surface and follow it automatically.

## Features
- Detects black line on white surface
- Moves automatically along the path
- Demonstrates basic robotics and automation concepts

## Components Used
- Arduino Uno
- L298N Motor Driver
- 2 DC Motors + Wheels
- 2 IR Sensors
- Robot Chassis
- Battery Pack

## How It Works
- IR sensors detect contrast between black line and white surface.
- Arduino reads the sensor signals and decides motor actions:
    - Left sensor detects black → turn left
    - Right sensor detects black → turn right
    - Both sensors detect black → move straight
- Robot follows the line automatically

## Demo / Video
A short video/demo will be added soon.

## Applications / Learning Outcome
- Smart factories (robots following floor lines)
- Autonomous delivery bots
- Foundation for learning self-driving robots
