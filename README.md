# rise-and-run-iot-app

## Project Title

Rise&Run: An IoT-Integrated Autonomous Robotic Alarm System that Encourages Physical Activity Upon Waking Up

## Description

Rise&Run is a multi-platform ecosystem designed to prevent oversleeping and encourage physical activity.

__Autonomous IoT Rover Alarm__
- Drives away when the alarm triggers, keeping it out of reach.
- Requires the user to perform a pre-set number of exercises to deactivate.
  
__Cross-Platform Mobile App__
- Allows users to set alarms, customize difficulty, track progress, and receive notifications.

__Centralized Web Dashboard__
- Displays "Wake-up Health" data, streaks, and optional social accountability alerts.
- Provides debugging logs (battery, Wi-Fi signal strength) for the IoT device.


## Technologies Used

__Frameworks and Programming Languages__

- Flutter
-  Dart

__IoT Devices__ 

- Makerlab ESP32 CAM 4WD Smart Robot Car Kit

- Ultrasonic Distance Sensor HC-SR04 Module Circuit Board 

- MPU6050 Accelerometer and Gyroscope Module

__Cloud Computing Integration__

- 

## Features

Autonomous Obstacle Avoidance: Uses on board sensors to "run away" from the user and avoid getting stuck in corners or under furniture.

Kinetic Deactivation (Rep Counting): The alarm only shuts off once the built-in accelerometer detects a specific number of "reps" (e.g., 10 overhead presses).

"Chaos Mode" Configuration: Users can customize the robot’s escape speed and the difficulty of the exercise via the mobile app.

Social Accountability: If the user fails to catch the alarm within a 5-minute window, the system automatically posts a "Lazy Alert" to the web dashboard visible to friends or roommates also using the app. This is off by default to respect  privacy, but can be turned on by the user if they require more accountability.

Smart Scheduling: Integration with mobile calendars to automatically set alarms based on the first class of the day.

## Installation Instructions

Tutorial taken from https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

1. On GitHub, navigate to the main page of the repository.
2. Above the list of files, click  <>Code.
3. Copy the URL for the repository.
4. Change the current working directory to the location where you want the cloned directory.
5. Type git clone, and then paste the URL you copied earlier.
6. Press Enter to create your local clone.

## Setup

__Setting up the robot__
1. Turn on the robot unit.
2. Link the robot unit to the application using bluetooth.
3. Wait for the application to indicate that connection was successful.
