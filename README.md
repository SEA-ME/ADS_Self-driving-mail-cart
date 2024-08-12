# ADS Project - Start and Goal. Self-driving mail delivering PiRacer
## You have a mail!  
</br>


# Index
#### [Introduction](#introduction-1)
#### [Background Information](#background-information-1)
#### [Project Goals & Objectives](#project-goals--objectives-1)
#### [Technical Requirements](#technical-requirements-1)
#### [System Architecture](#system-architecture-1)
#### [Software Design](#software-design-1)
#### [Project Timeline](#project-timeline-1)
#### [Collaboration and Teamwork](#collaboration-and-teamwork-1)
#### [Mentorship and Support](#mentorship-and-support-1)
#### [Reflection and Self-Assessment](#reflection-and-self-assessment-1)
#### [Submission](#submission-1)
#### [References](#references-1)
</br>


# Introduction

Autonomous driving technology is one of the most exciting and rapidly-evolving fields in the world of robotics and artificial intelligence. With the potential to revolutionize the way we move goods and people, it is an area that is ripe for exploration and experimentation. In this peer-to-peer educational project, participants will have the opportunity to build and compete with their own autonomous vehicles, known as PiRacers, as they learn about the technology and principles behind autonomous driving.

Throughout the project, participants will gain hands-on experience with cutting-edge technology in the field of autonomous driving, including computer vision, machine learning, control systems, and robotics. They will also develop valuable skills in software engineering, project management, and teamwork as they work together to build their PiRacer and compete against each other.

This peer-to-peer educational project is an exciting opportunity for anyone interested in autonomous driving, robotics, and technology to learn, experiment, and have fun. Whether you are a student, hobbyist, or professional, this project is a great way to expand your knowledge and skills, and be a part of the future of autonomous driving.  
</br>


# Background Information

Autonomous driving technology is rapidly advancing, with numerous companies and organizations investing in the development of self-driving vehicles. This technology has the potential to revolutionize transportation, increasing efficiency and safety, while reducing emissions and congestion. However, despite its many benefits, autonomous driving remains a complex and rapidly-evolving field that can be challenging for people to understand and get involved in.

To address this, this peer-to-peer educational project has been created to provide an accessible and engaging way for people to learn about autonomous driving. Participants will use Raspberry Pi computers, motors, wheels, and other off-the-shelf components to build and control their PiRacers, using open-source software libraries and tools such as TensorFlow, ROS, and OpenCV.

Teams of participants will work together to build the best PiRacer for delivering mail. Throughout the project, participants will learn about and apply key concepts in autonomous driving, including computer vision, machine learning, control systems, and robotics, as well as develop skills in software engineering, project management, and teamwork.

The goal of this project is to provide an accessible and engaging way for people to learn about autonomous driving and gain hands-on experience with the technology. Whether you are a student, hobbyist, or professional, this project offers a unique opportunity to explore and experiment with autonomous driving, and be a part of the future of this exciting and rapidly-evolving field.  
</br>


# Project Goals & Objectives

The goals and objectives of the Start and Goal project are as follows:

1. Create a system where PiRacer is possible to get from point A to point B, the coordinates are set by user.
2. Add parking feature to he system (optional)
  
</br>


# Technical Requirements


1. Hardware:
    * Raspberry Pi computers
    * Motors and wheels for the PiRacers
    * Batteries for power
    * Sensors such as cameras, ultrasonic sensors, and/or lidar sensors for perception
    * Other off-the-shelf components as needed to build and control the PiRacers
2. Software:
    * A Linux operating system for the Raspberry Pi
    * OpenCV for computer vision tasks
    * TensorFlow or another machine learning framework for perception and decision-making
    * ROS (Robot Operating System) or another robotics middleware for control and communication
    * Python or another programming language for software development
    * Tools for version control, project management, and documentation
3. Simulation environment:
    * A software platform for simulating the delivery environment, including obstacles and other objects
    * A visualizer for displaying the simulation and PiRacer performance
 
</br>


# System Architecture

The system architecture for the Start and Goal project can be divided into two main components:

1. Perception: Each PiRacer consists of a Raspberry Pi computer, motors and wheels for mobility, sensors for perception, and other components as needed. The Raspberry Pi runs software for perception, decision-making, and control, and communicates with the simulation environment through a wireless connection.
2. Simulation Environment: The simulation environment is a software platform for simulating the delivery environment and obstacles, and for visualizing the performance of the PiRacers. The simulation environment receives sensor data from the PiRacers and sends control commands to them. It also provides feedback to the participants through a visualizer, allowing them to observe and evaluate their PiRacer's performance.

</br>


# Software Design

The software design for the project can be divided into several key modules, each with its own functions and responsibilities.

1. Perception: The perception module is responsible for collecting and processing sensor data from the PiRacer's sensors, such as cameras, ultrasonic sensors, or lidar sensors. It uses computer vision techniques, such as object detection and image processing, to detect and identify objects in the environment, and feed this information to the decision-making module.
2. Control: The control module is responsible for executing the decisions made by the decision-making module, and controlling the PiRacer's movements and actions. It communicates with the motors and wheels to control the PiRacer's speed and direction, and also provides feedback to the decision-making module about the PiRacer's current state.
3. Localization and path-planning: For PiRacer's navigation it is suggested to create a race map in ros and use any suitable sensor for localization and static path-planning.
4. Communication: The communication module is responsible for exchanging data and commands between the PiRacer and the simulation environment. It uses a wireless connection to send sensor data from the PiRacer to the simulation environment, and to receive control commands from the simulation environment.
5. Simulation: The simulation module is responsible for simulating the delivery environment and obstacles, and for visualizing the performance of the PiRacers. It receives sensor data from the PiRacers and sends control commands to them, and also provides feedback to the participants through a visualizer.

</br>



# Project Timeline

The timeline for the Autonomous Mail Delivery Challenge using PiRacers project can be broken down into several phases, each with its own set of tasks and deadlines. With a separation of the projects into main topics it is expected that phases 2-5 will be done simultaneous:

1. Preparation (2-3 weeks)
    * Announcement of the project and registration of participants
    * Provision of hardware components and software components
    * Assembly of PiRacer hardware and installation of software components
2. Perception Development (2-3 weeks)
    * Development of the perception module
    * Testing of the perception module in the simulation environment
    * Debugging and improvement of the perception module as needed
3. Decision-Making Development (2-3 weeks)
    * Development of the decision-making module
    * Training of machine learning models
    * Testing of the decision-making module in the simulation environment
    * Debugging and improvement of the decision-making module as needed
4. Control Development (2-3 weeks)
    * Development of the control module
    * Testing of the control module in the simulation environment
    * Debugging and improvement of the control module as needed
5. Localization Development (2-3 weeks)
    * Development of the perception module
    * Testing of the localization module in the simulation environment
    * Debugging and improvement of the localization module as needed
6. Final testing and preparing for presentation (2 weeks)
    * Combine all modules and perfect the working system
    * Prepare slides with explaining work that you have done with real PiRacer performance

 

</br>



# Submission

Upon completion of the project, participants should submit a GitHub repository that includes the following components:

1. Hardware Assembly: Participants should provide a detailed description of the hardware components used in their PiRacer, and the steps taken to assemble the hardware. This may include photos or videos of the assembly process.
2. Software Code: Participants should provide the source code for their PiRacer software, including the perception module, decision-making module, and control module. The code should be well-documented, with clear explanations of the algorithms and techniques used.
3. Simulation Results: Participants should provide simulation results that demonstrate the performance of their PiRacer in the simulation environment. This may include screenshots or videos of the PiRacer in action, as well as metrics and statistics that measure the performance of the PiRacer.
4. Project Report: Participants should provide a project report that describes their experience with the project, including any challenges faced and how they were overcome. The report should also include a discussion of the algorithms and techniques used, as well as the results and conclusions of the project.

By providing these components, the participants will demonstrate their understanding of the concepts and techniques involved in the project, and will provide evidence of their ability to implement an autonomous system. The GitHub repository will serve as a portfolio of the participants' work, and will provide a record of their achievements and contributions to the field of autonomous systems.  
</br>


# References

Here are some open-source references that could be used for the Mail Delivering PiRacer project:

1. ROS (Robot Operating System) (http://www.ros.org/): ROS is an open-source robotic operating system that provides a wide range of tools and libraries for developing autonomous systems, including robots and drones. It can be used to build the software framework for the Mail Delivering PiRacer and manage its various components, such as the navigation and delivery modules.
2. Gazebo (http://gazebosim.org/): Gazebo is an open-source robotics simulator that provides a realistic environment for testing and evaluating autonomous systems. Participants can use Gazebo to test and refine their Mail Delivering PiRacer in a virtual environment, before deploying it in the real world.
3. ArduPilot (https://ardupilot.org/): ArduPilot is an open-source autopilot platform that provides a full suite of tools for developing autonomous vehicles, including drones. It can be used to implement the navigation and control systems for the Mail Delivering PiRacer.
4. OpenCV (https://opencv.org/): OpenCV is an open-source computer vision library that provides a wide range of algorithms and functions for image and video processing. It can be used to implement various computer vision techniques, such as object detection and tracking, for the Mail Delivering PiRacer.

These open-source tools and platforms can be used as a starting point for the Mail Delivering PiRacer project, and participants can build on them to create their own custom solutions. The specific tools and platforms used will depend on the goals and objectives of the educational program, as well as the skills and interests of the participants.



Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
