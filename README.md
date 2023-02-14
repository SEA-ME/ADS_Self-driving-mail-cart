# ADS Project - Self-driving mail delivering PiRacer
## You have a mail!  
</br>


# Index
#### [Introduction](#introduction-1)
#### [Background Information](#background-information-1)
#### [Project Goals & Objectives](#project-goals--objectives-1)
#### [Technical Requirements](#technical-requirements-1)
#### [System Architecture](#system-architecture-1)
#### [Software Design](#software-design-1)
#### [Implementation](#implementation-1)
#### [Project Timeline](#project-timeline-1)
#### [Collaboration and Teamwork](#collaboration-and-teamwork-1)
#### [Mentorship and Support](#mentorship-and-support-1)
#### [Reflection and Self-Assessment](#reflection-and-self-assessment-1)
#### [Submission](#submission-1)
#### [References](#references-1)
</br>


# Introduction

Autonomous driving technology is one of the most exciting and rapidly-evolving fields in the world of robotics and artificial intelligence. With the potential to revolutionize the way we move goods and people, it is an area that is ripe for exploration and experimentation. In this peer-to-peer educational project, participants will have the opportunity to build and compete with their own autonomous vehicles, known as PiRacers, as they learn about the technology and principles behind autonomous driving.

The project will be structured as a competition, where teams of participants will work to build the best PiRacer for delivering mail within a simulated environment. Using Raspberry Pi computers, motors, wheels, and other off-the-shelf components, participants will write software to control their vehicles and complete various challenges, such as delivering mail accurately, navigating through obstacles, and avoiding collisions.

Throughout the project, participants will gain hands-on experience with cutting-edge technology in the field of autonomous driving, including computer vision, machine learning, control systems, and robotics. They will also develop valuable skills in software engineering, project management, and teamwork as they work together to build their PiRacer and compete against each other.

This peer-to-peer educational project is an exciting opportunity for anyone interested in autonomous driving, robotics, and technology to learn, experiment, and have fun. Whether you are a student, hobbyist, or professional, this project is a great way to expand your knowledge and skills, and be a part of the future of autonomous driving.  
</br>


# Background Information

Autonomous driving technology is rapidly advancing, with numerous companies and organizations investing in the development of self-driving vehicles. This technology has the potential to revolutionize transportation, increasing efficiency and safety, while reducing emissions and congestion. However, despite its many benefits, autonomous driving remains a complex and rapidly-evolving field that can be challenging for people to understand and get involved in.

To address this, this peer-to-peer educational project has been created to provide an accessible and engaging way for people to learn about autonomous driving. The project focuses on building and competing with small autonomous vehicles, known as PiRacers, that are designed to deliver mail within a simulated environment. Participants will use Raspberry Pi computers, motors, wheels, and other off-the-shelf components to build and control their PiRacers, using open-source software libraries and tools such as TensorFlow, ROS, and OpenCV.

The competition aspect of the project provides an exciting and challenging environment for participants to learn and grow. Teams of participants will work together to build the best PiRacer for delivering mail, and compete against each other in various challenges, such as delivering mail accurately and efficiently, navigating through obstacles, and avoiding collisions. Throughout the project, participants will learn about and apply key concepts in autonomous driving, including computer vision, machine learning, control systems, and robotics, as well as develop skills in software engineering, project management, and teamwork.

The goal of this project is to provide an accessible and engaging way for people to learn about autonomous driving and gain hands-on experience with the technology. Whether you are a student, hobbyist, or professional, this project offers a unique opportunity to explore and experiment with autonomous driving, and be a part of the future of this exciting and rapidly-evolving field.  
</br>


# Project Goals & Objectives

The goals and objectives of the Autonomous Mail Delivery Challenge using PiRacers project are as follows:

1. To provide an accessible and engaging way for people to learn about autonomous driving technology and its applications.
2. To give participants hands-on experience with building and controlling autonomous vehicles (PiRacers) for delivering mail in a simulated environment.
3. To promote learning and understanding of key concepts in autonomous driving, including computer vision, machine learning, control systems, and robotics.
4. To develop participants' skills in software engineering, project management, and teamwork as they work together to build and compete with their PiRacers.
5. To foster creativity and innovation in the field of autonomous driving through the competition aspect of the project.
6. To provide a platform for participants to showcase their skills and achievements to others, and connect with like-minded individuals in the field.
7. To promote awareness and understanding of the potential benefits and challenges of autonomous driving, and its impact on society.
8. To provide participants with an enjoyable and rewarding learning experience that inspires them to continue exploring and experimenting with autonomous driving technology.
9. To contribute to the advancement of autonomous driving technology and its applications, by bringing together a community of enthusiasts, experts, and learners.

Overall, the goals and objectives of the Autonomous Mail Delivery Challenge using PiRacers project are to provide an enjoyable and educational experience for participants, while promoting understanding and innovation in the field of autonomous driving.  
</br>


# Technical Requirements

The Autonomous Mail Delivery Challenge using PiRacers project requires the following technical requirements:

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
4. Competition rules and requirements:
    * Detailed rules and requirements for the competition, including the delivery task, obstacles, and other challenges
    * A scoring system for evaluating PiRacer performance
    * A process for submitting and testing PiRacers before the competition
    * A procedure for conducting the competition, including timing, judging, and announcement of results
5. Infrastructure:
    * Computing resources and storage for the Raspberry Pi and simulation environment
    * Network connectivity for communication between the PiRacers and the simulation environment
    * Space for setting up and conducting the competition
6. Participants:
    * Teams of participants, each with a Raspberry Pi and components for building and controlling their PiRacer
    * Participants with basic knowledge of programming and electronics
    * Participants with an interest in autonomous driving and robotics

By meeting these technical requirements, the Autonomous Mail Delivery Challenge using PiRacers project will provide participants with the necessary tools and resources to build and compete with their PiRacers, and learn about autonomous driving technology.  
</br>


# System Architecture

The system architecture for the Autonomous Mail Delivery Challenge using PiRacers project can be divided into three main components: the PiRacers, the simulation environment, and the competition infrastructure.

1. PiRacers: Each PiRacer consists of a Raspberry Pi computer, motors and wheels for mobility, sensors for perception, and other components as needed. The Raspberry Pi runs software for perception, decision-making, and control, and communicates with the simulation environment through a wireless connection.
2. Simulation Environment: The simulation environment is a software platform for simulating the delivery environment and obstacles, and for visualizing the performance of the PiRacers. The simulation environment receives sensor data from the PiRacers and sends control commands to them. It also provides feedback to the participants through a visualizer, allowing them to observe and evaluate their PiRacer's performance.
3. Competition Infrastructure: The competition infrastructure includes the computing resources, storage, and network connectivity needed to run the simulation environment, as well as the space and equipment required to conduct the competition. The competition infrastructure also includes the rules, scoring system, and process for submitting and testing PiRacers before the competition.

In summary, the system architecture of the Autonomous Mail Delivery Challenge using PiRacers project provides the necessary components and resources for building, competing, and learning about autonomous driving technology. The PiRacers, simulation environment, and competition infrastructure work together to create a challenging and engaging learning experience for the participants.  
</br>


# Software Design

The software design for the Autonomous Mail Delivery Challenge using PiRacers project can be divided into several key modules, each with its own functions and responsibilities.

1. Perception: The perception module is responsible for collecting and processing sensor data from the PiRacer's sensors, such as cameras, ultrasonic sensors, or lidar sensors. It uses computer vision techniques, such as object detection and image processing, to detect and identify objects in the environment, and feed this information to the decision-making module.
2. Decision-Making: The decision-making module is responsible for using the information from the perception module to make decisions about the PiRacer's behavior and actions. It uses machine learning algorithms, such as decision trees or neural networks, to determine the best course of action based on the current state of the environment.
3. Control: The control module is responsible for executing the decisions made by the decision-making module, and controlling the PiRacer's movements and actions. It communicates with the motors and wheels to control the PiRacer's speed and direction, and also provides feedback to the decision-making module about the PiRacer's current state.
4. Communication: The communication module is responsible for exchanging data and commands between the PiRacer and the simulation environment. It uses a wireless connection to send sensor data from the PiRacer to the simulation environment, and to receive control commands from the simulation environment.
5. Simulation: The simulation module is responsible for simulating the delivery environment and obstacles, and for visualizing the performance of the PiRacers. It receives sensor data from the PiRacers and sends control commands to them, and also provides feedback to the participants through a visualizer.
6. Competition: The competition module is responsible for implementing the rules and requirements of the competition, including the scoring system, process for submitting and testing PiRacers, and procedure for conducting the competition.

By dividing the software into these key modules, the software design of the Autonomous Mail Delivery Challenge using PiRacers project provides a clear and organized structure for the participants to build and control their PiRacers, and for the simulation environment to evaluate and visualize their performance. It also makes it easier for participants to focus on specific aspects of the project, such as perception, decision-making, or control, and to learn about these concepts in depth.  
</br>


# Implementation

The implementation of the Autonomous Mail Delivery Challenge using PiRacers project can be broken down into several stages:

1. Hardware Assembly: The first stage of implementation is to assemble the PiRacer hardware components, including the Raspberry Pi, motors and wheels, sensors, and other components as needed. The participants should follow the provided instructions and guidelines for assembling the hardware, and test the components to ensure that they are functioning properly.
2. Software Installation: The next stage of implementation is to install the software components needed for the project, including the operating system, libraries, and other dependencies. The participants should also install the simulation environment software and the competition infrastructure software, and ensure that they are working properly.
3. Perception Development: In this stage, the participants will develop the perception module of their PiRacer software, using computer vision techniques to detect and identify objects in the environment. This may involve using existing libraries or developing custom algorithms, and testing the perception module in the simulation environment to ensure that it is working correctly.
4. Decision-Making Development: In this stage, the participants will develop the decision-making module of their PiRacer software, using machine learning algorithms to make decisions about the PiRacer's behavior and actions. This may involve training a machine learning model on a dataset of examples, and testing the decision-making module in the simulation environment to ensure that it is working correctly.
5. Control Development: In this stage, the participants will develop the control module of their PiRacer software, which will execute the decisions made by the decision-making module and control the PiRacer's movements and actions. This may involve writing code to control the motors and wheels, and testing the control module in the simulation environment to ensure that it is working correctly.
6. Competition Preparation: In this final stage, the participants will submit their PiRacer software for testing and evaluation, and prepare for the competition. They should review the competition rules and requirements, and make any necessary changes to their software to meet the criteria. They should also test their PiRacer in the simulation environment to ensure that it is functioning properly.

By following these stages, the implementation of the Autonomous Mail Delivery Challenge using PiRacers project provides a step-by-step process for building and testing a fully-functional PiRacer, and for participating in the competition. The project provides a hands-on learning experience for the participants, allowing them to develop their skills in computer vision, machine learning, and robotics, and to apply these skills in a real-world setting.  
</br>


# Project Timeline

The timeline for the Autonomous Mail Delivery Challenge using PiRacers project can be broken down into several phases, each with its own set of tasks and deadlines:

1. Phase 1: Preparation (2-3 weeks)
    * Announcement of the project and registration of participants
    * Provision of hardware components and software components
    * Assembly of PiRacer hardware and installation of software components
2. Phase 2: Perception Development (2-3 weeks)
    * Development of the perception module
    * Testing of the perception module in the simulation environment
    * Debugging and improvement of the perception module as needed
3. Phase 3: Decision-Making Development (2-3 weeks)
    * Development of the decision-making module
    * Training of machine learning models
    * Testing of the decision-making module in the simulation environment
    * Debugging and improvement of the decision-making module as needed
4. Phase 4: Control Development (2-3 weeks)
    * Development of the control module
    * Testing of the control module in the simulation environment
    * Debugging and improvement of the control module as needed
5. Phase 5: Competition Preparation (2 weeks)
    * Final testing of the PiRacer in the simulation environment

</br>


# Collaboration and Teamwork

Students will be working in teams of maximum six to complete this project. Each team member will be assigned specific tasks and responsibilities, and will be expected to contribute to the overall success of the project. Teams will be required to submit regular progress reports and to meet with the instructor for check-ins and feedback.  
</br>


# Mentorship and Support

Students will be provided with mentorship and support from the instructor throughout the project. The instructor will be available for questions and guidance, and will hold regular check-ins and progress reports to provide feedback and support.  
</br>


# Reflection and Self-Assessment

Students will be encouraged to reflect on their own learning and progress throughout the project. This will be done through self-assessment exercises and through feedback from the instructor and other team members.  
</br>


# Submission

Upon completion of the Autonomous Mail Delivery Challenge using PiRacers project, participants should submit a GitHub repository that includes the following components:

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
