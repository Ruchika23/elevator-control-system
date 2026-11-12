Elevator Control System

Overview

This repository contains a MATLAB Simulink and Stateflow implementation of an elevator control system developed as part of the course 1DT059 – Model-based Design of Embedded Software.

The project focuses on the design, implementation, verification, and validation of an elevator controller supporting both simulation and hardware execution using Arduino. The system serves four floors and supports floor requests, request cancellation, door operation, and emergency stop functionality.

Features
Stateflow-based controller design
MATLAB Simulink simulation
Arduino hardware integration
Ultrasonic sensor position feedback
Requirement monitoring
Simulink Design Verifier (SLDV) testing
Formal verification of safety requirements
Technologies
MATLAB
Simulink
Stateflow
Arduino
Simulink Design Verifier (SLDV)
Project Structure
Controller Design
Physical Elevator Model
Arduino Hardware Model
Requirement Monitoring Models
Verification and Testing
Requirements Verified
Door remains closed while elevator is moving
Door stays open for required duration
Elevator does not stop at unrequested floors
Elevator reaches requested floors within defined limits
Results

The controller was successfully validated through simulation, requirement monitoring, automated test generation, and hardware execution using Arduino-based position feedback. The implemented system satisfied all project requirements after resolving timing and sample-time inconsistencies.

Author

Ruchika Verma


Demonstration Video
A demonstration of the elevator control system is available here:

                                          https://youtube.com/shorts/ZqxBHt_fibA?feature=share







NOTE: Source code and implementation files are not publicly distributed. This repository is intended to showcase the project architecture, methodology, verification activities, and results.

