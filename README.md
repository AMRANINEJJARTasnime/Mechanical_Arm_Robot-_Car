# Mechanical Arm Robot Car
![11111](https://github.com/user-attachments/assets/950fb666-e6f4-47c3-a91d-c6c1bea3f506)

## Project Overview
This project integrates a 4DOF mechanical arm with a smart car to create a versatile robotic platform. The robotic arm, mounted on a robust chassis, can perform a variety of tasks while the car moves autonomously using an ultrasonic sensor to detect its surroundings.

## Main Features

- **Pick and Place Functionality**:  
  The robot arm is capable of picking up and placing objects with precision, controlled via either a mobile app or a game controller, providing versatile control options.
  
- **Sequence Learning**:  
  The robot can learn and record sequences of movements to repeat specific actions automatically, improving its automation capabilities for repetitive tasks.

- **Autonomous Object Carrying**:  
  Designed to autonomously transport objects from one point to another, ensuring hands-free operation.

- **Obstacle Avoidance**:  
  Integrated with sensors, the robot can detect and avoid obstacles, enabling safe movement and preventing collisions.

- **Follow Mode**:  
  The robot can follow a pre-defined path or user-specified route, enhancing its usability across different scenarios.

## Learning Outcomes

- **Robotic Kinematics**:  
  Developed a strong understanding of robotic kinematics, including the movement and positioning of joints and arms, essential for precise object manipulation.

- **Motor and Servo Control**:  
  Gained practical experience in controlling motors and servos using Arduino technology, improving hardware programming capabilities.

- **Arduino Programming**:  
  Improved proficiency in Arduino programming, enabling the integration of various components such as sensors and motors into the robotic system.

- **Automation Techniques**:  
  Learned how to implement automation features like recording and repeating sequences of movements, contributing to a deeper understanding of autonomous robotic systems.

- **Sensor Integration**:  
  Acquired experience in integrating sensors for obstacle detection and navigation, improving the robot’s ability to function effectively in dynamic environments.

- **Problem-Solving**:  
  Enhanced problem-solving abilities through debugging and optimizing the robot's performance during design and testing.

- **Team Collaboration**:  
  Strengthened teamwork and collaboration by working closely with peers to design, assemble, and program the robot.

## Technical Specifications
- **Working Voltage**: 5V
- **Input Voltage**: 7-12V
- **Max Output Current**: 3A
- **Max Power Dissipation**: 25W
- **Motor Speed**: 63 RPM at 5V
- **Motor Drive**: TB6612
- **Ultrasonic Detection Angle**: <15 degrees
- **Ultrasonic Detection Range**: 2cm-400cm
- **Bluetooth Control Range**: 20-50 meters

## Assembly
1. **Assembling the Mechanical Arm**: The arm was assembled to ensure full range of motion for all 4 degrees of freedom.
2. **Mounting on Mobile Base**: The mechanical arm was installed on a mobile base equipped with wheels and a motor system.
3. **Integration with Sensors and Controllers**: Ultrasonic sensors and Bluetooth modules were integrated for navigation and control.

![github](https://github.com/user-attachments/assets/9f01703b-05e7-4ff2-a290-7a1b519bc005)


## Programming
The robot is programmed in **C language** using the **Arduino** platform. The code handles movement commands, sensor data processing, and communication with external controllers (Bluetooth and PS2).


## Kinematic Model
The kinematics of the robot were modeled using DH parameters to define the relative motion of each joint, ensuring accurate arm positioning and movement.

## Contributors
- AIT EL CADI Shadia
- M'HIFED Zineb
- AMRANI NEJJAR Tasnime
