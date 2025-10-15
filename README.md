Robot Manipulation Projects
A collection of industrial robot manipulation projects completed during the IFROS master's program, demonstrating practical applications in automated classification, assembly, and surface processing tasks.

📋 Project Overview
This repository contains three hands-on robotics projects focusing on pick-and-place operations and surface manipulation using industrial robots programmed in VAL3 and URScript.

🤖 Project 1: Automated Cylinder Classification System
Robot: Stäubli TS60
Duration: December 2024
Description
Developed an automated classification system that sorts metallic and non-metallic cylinders using real-time sensor data and places them in a classification matrix.
Key Achievements

Programmed a 3-level classification system progressing from manual to fully automated operation
Integrated inductive sensors for real-time material detection (metallic vs. non-metallic)
Implemented continuous feeding mechanism with 4-cylinder capacity per operation
Designed dynamic routing protocols (OSPF, BGP, EIGRP) for multi-branch network communication
Controlled actuators, barriers, and trolley systems for synchronized material flow

Technical Skills

Languages: VAL3
Tools: EVE-NG, Cisco Packet Tracer, Stäubli Robotics Suite
Concepts: Pick-and-place automation, sensor integration, I/O mapping, trajectory planning

Results
Successfully classified and placed 4 metallic and 4 non-metallic cylinders with 100% accuracy using automated sensor-driven sorting.

🔧 Project 2: Cylinder-Piston Assembly System
Robots: Stäubli TX60
Duration: December 2024
Description
Implemented a complete assembly line that picks cylinders and pistons from dispensers, assembles them at an assembly station, and places finished products in a matrix.
Key Achievements

Developed 3-level assembly program from basic to sensor-integrated continuous operation
Integrated presence sensors for piston detection across 8 random positions
Programmed dual-tool coordination (lateral tool for cylinders, tip tool for pistons)
Created custom reference frames for precise matrix placement
Implemented safety protocols with dual-speed control (normal and cautious velocities)

Technical Skills

Languages: VAL3, URScript
Platforms: Stäubli Robotics Suite, PolyScope
Concepts: Multi-tool operations, reference frames, digital I/O control, teach pendant programming

Results
Successfully assembled 4 cylinder-piston units with automatic piston detection and precise matrix placement across 12 positions (4 rows × 3 columns).

🔨 Project 3: Irregular Surface Polishing
Robot: UR3e Collaborative Robot
Duration: December 2024
Description
Programmed a collaborative robot to polish an irregular surface following a zig-zag trajectory while maintaining constant contact force.
Key Achievements

Achieved consistent force application across irregular surface topography
Programmed 10-waypoint zig-zag trajectory for complete surface coverage
Configured tool orientation to remain normal to polishing surface
Implemented real-time position tracking for debugging and performance monitoring
Applied collaborative robot safety standards for human-robot interaction

Technical Skills

Languages: URScript
Platform: PolyScope (UR3e interface)
Concepts: Force control, trajectory planning, waypoint programming, tool configuration

Results
Successfully polished entire irregular surface with consistent force application and smooth transitions between waypoints, demonstrated in video documentation.

🎯 Core Competencies Demonstrated

Programming & Simulation

VAL3 and URScript programming languages
Robot simulation and testing (SRS, PolyScope)
Teach pendant operation and program deployment

Robot Control

Trajectory planning and motion control
Force-controlled manipulation
Multi-tool coordination
Sensor integration and I/O management

System Integration

Digital input/output mapping
Actuator and sensor coordination
Reference frame definition
Safety system implementation


📊 Technical Specifications

Robots Used

Stäubli TS60: 4-axis robot, CS9 controller
Stäubli TX60: 6-axis robot, 500mm reach, 3kg payload
UR3e: 6-joint collaborative robot, 500mm reach, 3kg payload

Programming Environments

Stäubli Robotics Suite (SRS)
PolyScope (Universal Robots)
Teach pendant interfaces


🎥 Demo Videos

TS60 Classification System
TX60 Assembly Line
UR3e Surface Polishing


Team Members: Rihab Laroussi, Priyam Gupta, Davina Sanghera
Supervisor: Jad Mansour
Institution: University of Girona - IFROS Program
