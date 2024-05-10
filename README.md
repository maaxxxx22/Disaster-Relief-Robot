# Tactical IED Detection Robot

## Overview
The Tactical IED Detection Robot is a simulated robot designed to assist in detecting improvised explosive devices (IEDs) in hazardous environments. This project aims to simulate the operation of a robotic system capable of navigating through debris-filled areas and identifying hidden IEDs using various sensors.

## Features
- Simulation environment: The project utilizes CoppeliaSim to create a realistic urban environment with debris, obstacles, and hidden IEDs.
- IED detection: The robot is equipped with sensors capable of detecting chemical traces emitted by explosives, allowing it to locate hidden IEDs.
- Proximity detection: The robot uses proximity sensors to detect obstacles and navigate through cluttered environments safely.
- Counting system: The robot keeps track of the number of detected IEDs using a count widget displayed in the simulation.

## Architecture
The robot's architecture is based on the BubbleRob tutorial, featuring two main sensors:
1. Proximity Sensor: Detects obstacles and triggers avoidance maneuvers to ensure safe navigation.
2. IED Detection Sensor: Identifies chemical traces emitted by explosives, indicating the presence of hidden IEDs.

## Implementation
The project is implemented using Lua scripting within CoppeliaSim. Key components of the implementation include:
- Initialization: Setting up variables, sensors, and motors.
- Sensing: Reading sensor data to detect obstacles and IEDs.
- Actuation: Controlling robot movements based on sensor inputs.
- User Interface: Integrating a custom UI to display the IED count and adjust robot speed.

## Getting Started
1. Clone the repository to your local machine.
2. Install CoppeliaSim.
3. Open the CoppeliaSim scene file included in the repository.
4. Run the simulation to observe the robot in action.

## Demo
[Insert link to demo video or GIF showcasing the robot's operation]

## Future Improvements
- Implement reinforcement learning algorithms to enhance decision-making.
- Explore advanced search algorithms for optimized navigation in dynamic environments.
- Enhance the simulation environment with more realistic debris and IED placements.

## Contributors
- [Your Name or Username] - Project Lead and Developer

## License
This project is licensed under the [License Name] License - see the [LICENSE.md](LICENSE.md) file for details.

