# 🚗 ELI-050 - Line Follower Robot using PID Control🚗

## 📋 Project Overview
This project implements a line-following robot that uses a PID (Proportional-Integral-Derivative) control algorithm to follow a black line on a white surface. The robot utilizes sensors to detect the line and adjusts its motors' speed to stay on track, ensuring smooth and accurate movements.

## ⚙️ Components
* Arduino 
* DC Motors 3A 6V
* 3D printed car
* Jumper Wires and Connectors
***

## Software Requirements

- Arduino IDE or PlatformIO
- Libraries: 
  - [PID_v1](https://github.com/br3ttb/Arduino-PID-Library) (for Arduino)
  - [QTRSensors](https://github.com/pololu/qtr-sensors-arduino) (for line sensors)

## PID Control Explanation
PID control is used to maintain the robot's position on the line by calculating an error value as the difference between the desired position (centered on the line) and the actual position (detected by the sensors). The control algorithm adjusts the motor speeds based on three terms:
- **Proportional (P)**: Corrects errors based on the current deviation.
- **Integral (I)**: Corrects past errors by accumulating error over time.
- **Derivative (D)**: Reacts to the rate of error change, smoothing the robot's movement.

The PID formula used is:

Output = (Kp * error) + (Ki * integral) + (Kd * derivative)


Where:
- `Kp` is the proportional gain.
- `Ki` is the integral gain.
- `Kd` is the derivative gain.

You can fine-tune these parameters to optimize the robot's performance.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/jjvgomes14/ELI-050.git

## Authors

* Diego G. H. Vaulliamo - 
* João Victor G. Prado - jjvgomes14@gmail.com
* Cleuder Nathan C. Garcia -
* Pedro Augusto T. Ferreira - 

[Centro Universitário FEI, São Bernardo](https://portal.fei.edu.br/)

 


