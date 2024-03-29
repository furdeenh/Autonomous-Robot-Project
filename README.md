# Autonomous Robot Project

## Overview

This project focuses on implementing a line-following robot. The primary goal is to integrate the learnings from the course to create a battery-powered/autonomous robot capable of navigating a track by following a line. 

## Project Goals

- **Integration**: Combining course learnings to build a functional line-following robot.
- **Customization**: Encouraged to enhance functionality with new modules for additional points.

## Hardware Requirements

- PIC32 Kit board
- Robot Kit Frame
- IR sensor pmod and 4 IR sensors
- 2 R/C Servos
- Oscilloscope for debugging

## Inputs and Outputs

**Inputs**
- Microphone
- IR Sensors

**Outputs**
- On-board LEDs, SSDs, LCD
- R/C Servos

## Functional Requirements

1. **Movement**: Utilize servo motors for navigation.
2. **Line Following**: Employ 4 IR sensors to follow a track marked by a black stripe on a white background.
3. **Timing**: Measure run time in tenths of seconds and display it on the SSD.
4. **Starting Mechanism**: Start the robot with two claps detected by the microphone within a second.

## Line Following Rules

- The track is ring-shaped, with the start/end point marked by a black stripe.
- Robots wait for a starting sound (two claps) detected by a microphone or an on-board button press.
- The track includes both sharp and curve turns, with the smallest angle being around 90 degrees.

## Control

- PWM period: 16~23ms (recommended frequency: 50Hz).
- Pulse width range: 0.9ms to 2.1ms. Servo behavior depends on the pulse width relative to 1.5ms (neutral position).

## Checkpoints

1. **Sensor Configuration**: Set up and test IR sensors for black stripe detection.
2. **PWM Setup**: Configure and validate PWM signals for servo control.
3. **Servo Integration**: Attach servos and validate with external power.
4. **Algorithm Implementation**: Program the robot to complete the track.
5. **Finalization**: Bring all components together for a functioning robot.

## Hardware Assembly and Demo

- Creative robot naming displayed on LCD.
- Demonstration of IR sensor functionality and motor control logic.
- PWM signal creation for servo motors to operate the robot untethered.

## Due Dates

- Mid-stage demo: 11/18 in class
- C Code submission: 12/7 at 10:30am
- Competition: 12/7 at 11:10

## Additional Resources
- [Hardware Assembly Guide](https://reference.digilentinc.com/_media/line-following_servo_robot_kit:srk-line_rm.pdf)

## Project Notes

- Emphasis on accuracy, robustness, and speed.
- Encouraged customization for enhanced functionality and additional points.

