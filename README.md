# Mini-Project-Driver Drowsiness Detection System

## Overview
This project aims to develop a Driver Drowsiness Detection System to enhance road safety by detecting and alerting drowsy or sleeping drivers. The system utilizes Eye Blinking Sensor Goggles, an Arduino NANO Board, and LED-based visual alerts to monitor the driver's eye behavior and initiate appropriate responses in real-time.

## System Components

### 1. Driver's Eye
The system begins with the driver's eye, where the Eye Blinking Sensor Goggles are worn.

### 2. Eye Blinking Sensor
The Eye Blinking Sensor serves as the primary input device for the system. It uses infrared (IR) technology to emit and detect IR waves reflected by the driver's eyes.

### 3. Arduino NANO Board
The output from the Eye Blinking Sensor is transmitted to an Arduino board. The Arduino processes the data and makes real-time decisions based on the driver's eye behavior.

### 4. Drowsy Driver Alert and Prevention
This block represents the system's response to the driver's eye behavior.

#### 4.1 Scenario 1 - Eye Closure for 2 Seconds
If the driver's eyes are closed for 2 seconds, it triggers an alert. The buzzer sounds to provide an auditory warning, and a green LED is activated to give a visual alert to other vehicles.

#### 4.2 Scenario 2 - Eye Closure for More Than 2 Seconds
If the driver falls asleep and their eyes remain closed for more than 2 seconds, it triggers a more urgent alert. The buzzer continues to sound for persistent audio warning, a red LED is activated to indicate an immediate need for action, and the system initiates a gradual reduction in vehicle speed to prevent accidents.

### 5. LED Installation
This block emphasizes the unique LED-based approach for visual alerts.

#### 5.1 Green LED
The green LED provides a clear visual alert to other vehicles when the driver's eyes are closed for 2 seconds.

#### 5.2 Red LED
The red LED complements the warning system for a more severe alert when the driver's eyes are closed for an extended period.

## System Operation
The system combines the Eye Blinking Sensor, Arduino processing, and LED-based alerts to detect and respond to a drowsy or sleeping driver. It provides a multi-modal alert mechanism to enhance road safety and prevent accidents by effectively communicating the driver's state to drivers and other road users.

## Cost-Effectiveness and Practicality
The block diagram illustrates how these components work together to ensure driver safety and is both cost-effective and practical in comparison to more complex solutions.

## Contributors
- [Pravallika Oggu](https://github.com/Pravallika0)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

You can further customize this README file according to your project's specific details and requirements.
