# FSD UniBO Motorsport resources
Resources to study and know the basics of:
- **Robotics**: Technology and methods of development and system orchestration, design and architecture choices.
- **Machine learning**: RL and supervised techniques, algorithms and useful libraries.
- **Autonomous driving**: requirements, design techniques and methods.

(TODO: expand with sensor processing, **machine vision** and embedded programming)

## Robotics
Instruments and methods from robotics are useful for system orcherstration. Such methods provide an interface for all the various parts and ensure a stabile system operation.
- Unibo [Industrial robotics](https://web.microsoftstream.com/user/606d5447-cbd8-4e7e-b138-628a15a51321) course lessons by Prof Palli.
- [Introductive course](http://ais.informatik.uni-freiburg.de/teaching/ss16/robotics/index_en.php) to mobile robotics.
- [Resource collection](https://github.com/kiloreux/awesome-robotics) about various arguments robotics-related stuff.
### ROS
ROS ("Robot os") is a developement middleware/framework directed towards robotics applications. It provides various libraries and instruments useful to build and manage autonomous systems. Choosing ROS is obvious because it is the most largely used and supported robot developement toolbox.
- ROS [Wiki](http://wiki.ros.org) ([introduction](http://wiki.ros.org/ROS/Introduction) e and [tutorial](http://wiki.ros.org/ROS/Tutorials) pages in particular).
- [Playlist](https://www.youtube.com/playlist?list=PLRG6WP3c31_U7TFGduEIJWVtkOw6AJjFf) and [slides](https://github.com/ROBOTIS-GIT/ros_seminar) for a brief introduction.
- [Basics](https://www.youtube.com/playlist?list=PLK0b4e05LnzZWg_7QrIQWyvSPX2WN2ncc) on main ROS concepts.
- [Palli's lesson](https://web.microsoftstream.com/video/26d259a9-ef87-4367-9fb5-a864d68688d6?list=user&userId=606d5447-cbd8-4e7e-b138-628a15a51321) on ros

## Machine Learning
Machine learning and machine vision will be needed for the perception and motion planning modules.
### General
- Explaination [Docs](https://ml-cheatsheet.readthedocs.io/en/latest/index.html) for various machine learning concepts.
- [Introductive course CS188](https://www.youtube.com/user/CS188Spring2013/videos) to artificial intelligence.
- [Introductive course CS189](https://www.eecs189.org/) to machine learning.
### Reinforcement Learning
- In particular from CS188:
    - [Lecture 8: Markov Decision Processes 1](https://www.youtube.com/watch?v=i0o-ui1N35U)
    - [Lecture 9: Markov Decision Processes 2](https://www.youtube.com/watch?v=Csiiv6WGzKM)
    - [Lecture 10: Reinforcement Learning 1](https://www.youtube.com/watch?v=ifma8G7LegE)
    - [Lecture 11: Reinforcement Learning 2](https://www.youtube.com/watch?v=Si1_YTw960c)
- [Hands-on tutorial](https://www.youtube.com/watch?v=sOiNMW8k4T0&feature=youtu.be) on RL and algorithms and data structures, with Python and Tensorflow.

## Autonomous driving
- [Resources](https://github.com/AMZ-Driverless/fsd-resources) from the Zurich driverless team AMZ.
- Design completo
    - [[paper](https://arxiv.org/pdf/1905.05150.pdf)] AMZ Driverless: The Full Autonomous Racing System
    - [[paper](https://publik.tuwien.ac.at/files/publik_262887.pdf)] Design of an Autonomous Race Car for theFormula Student Driverless (FSD)
- Motion planning
    - [[paper](https://arxiv.org/pdf/2003.04882.pdf)] Optimization-Based Hierarchical Motion Planning for Autonomous Racing
- Perception
    - [[paper](https://arxiv.org/pdf/2007.13971.pdf)] Accurate, Low-Latency Visual Perception for Autonomous Racing: Challenges, Mechanisms, and Practical Solutions
    - [[paper](https://arxiv.org/pdf/1809.10099.pdf)] Redundant Perception and State Estimation for Reliable Autonomous Racing
    - [Repo](https://github.com/germain-hug/Autonomous-RC-Car) of a simple autonomous RC car. ROSpy + convolutional network (camera images directly fed as network input).

(if it wasn't  clear enough we will "take a cue" from the Zurich AMZ team)
