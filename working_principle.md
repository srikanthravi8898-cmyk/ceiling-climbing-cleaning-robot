# Working Principle

## 1. Overview

The Ceiling-Climbing Cleaning Robot is designed to move along ceiling surfaces while removing accumulated dust. The system combines a suction mechanism, an electric drive system, a lightweight chassis, and an embedded control system.

## 2. Suction Mechanism

A BLDC motor drives a fan or impeller that generates airflow. The suction assembly is designed to create a pressure difference between the region beneath the robot and the surrounding atmosphere. This pressure difference can produce an adhesion force that helps keep the robot attached to the ceiling.

The impeller geometry, airflow path, and sealing arrangement must be optimized to achieve sufficient adhesion.

## 3. Motor Speed Control

An Electronic Speed Controller (ESC) regulates the speed of the RS2205 2300KV BLDC motor in response to a compatible control signal. Motor speed affects airflow and suction performance, depending on the fan design and operating conditions.

## 4. Power Supply

A 3S LiPo battery with a nominal voltage of 11.1V is planned to supply the motor system. The power distribution system will provide suitable power connections for the controller and other electrical components.

## 5. Embedded Control

A microcontroller will generate the required ESC control signal and may process sensor data for monitoring and movement control. The controller and sensors will be selected based on the final system architecture.

## 6. Cleaning Mechanism

A cleaning attachment will remove dust from the ceiling surface as the robot moves. The design must minimize interference with the suction airflow and maintain adequate adhesion during cleaning.

## 7. Safety and Testing

Initial testing will use a secured test rig and a safety tether. Suction performance, adhesion force, motor current, battery runtime, and cleaning effectiveness will be evaluated before attempting operation on an overhead surface.

## 8. Current Development Status

The project is in the design and prototyping stage. The suction assembly, control architecture, cleaning attachment, and mechanical structure are being developed and validated.

## Future Improvements

- Closed-loop motor speed control
- Improved suction efficiency
- Sensor-based navigation
- Obstacle detection
- Battery monitoring
- Fail-safe protection against detachment
