# rise-and-run-iot-app

Project Title: Rise&Run: An IoT-Integrated Autonomous Robotic Alarm System that Encourages Physical Activity Upon Waking Up

Description: 
Rise&Run is a multi-platform ecosystem designed to prevent oversleeping and encourage physical activity.

Autonomous IoT Rover Alarm
- Drives away when the alarm triggers, keeping it out of reach.
- Requires the user to perform a pre-set number of exercises to deactivate.
  
Cross-Platform Mobile App
- Allows users to set alarms, customize difficulty, track progress, and receive notifications.

Centralized Web Dashboard
- Displays "Wake-up Health" data, streaks, and optional social accountability alerts.
- Provides debugging logs (battery, Wi-Fi signal strength) for the IoT device.


Technologies Used: Flutter, Dart, IoT, Cloud Computing (mention the cloud platform you’re using).

Features:
Autonomous Obstacle Avoidance: Uses on board sensors to "run away" from the user and avoid getting stuck in corners or under furniture.

Kinetic Deactivation (Rep Counting): The alarm only shuts off once the built-in accelerometer detects a specific number of "reps" (e.g., 10 overhead presses).

"Chaos Mode" Configuration: Users can customize the robot’s escape speed and the difficulty of the exercise via the mobile app.

Social Accountability: If the user fails to catch the alarm within a 5-minute window, the system automatically posts a "Lazy Alert" to the web dashboard visible to friends or roommates also using the app. This is off by default to respect  privacy, but can be turned on by the user if they require more accountability.

Smart Scheduling: Integration with mobile calendars to automatically set alarms based on the first class of the day.

Installation Instructions: Instructions on how to clone and run the app locally (for others or future you).

Setup: Instructions for setting up IoT devices and cloud services.
