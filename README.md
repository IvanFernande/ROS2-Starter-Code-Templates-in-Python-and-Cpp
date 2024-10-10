# ROS2 (Humble) Templates for nodes
<p align="center">
  <img src="https://github.com/user-attachments/assets/3e10d96d-7e1f-4caa-9d8f-4bcaf5ee6529" width="300">
</p>
ROS2 (Robot Operating System) is a flexible and scalable framework for writing robot software. It provides the tools and libraries needed to obtain, build, write and run code on multiple computers. One of the key features of ROS2 is its use of ‘nodes’ which are processes that perform computations. Nodes communicate with each other via topic messages within a network, which facilitates modularity and code reuse, essential in complex robotic development.

The node-based architecture of ROS2 is key because it allows a system to be broken down into small functional parts that can be developed and tested independently. These nodes can be as simple as an individual sensor controller or as complex as an advanced motion planning system. By modularising systems in this way, ROS2 facilitates collaboration between developers and the integration of heterogeneous systems, providing a robust intercommunication framework.

During my time learning to use ROS2, I noticed that it can be cumbersome to start developing a node from scratch. This initial hurdle led me to create templates for writing nodes in both Python and C++. These templates are designed to be a starting point, helping developers to quickly structure their own nodes and customise them to the needs of their specific projects. I have uploaded these codes, called template.py and template.cpp, in the hope that they will serve as a valuable tool for others starting out in ROS2.

It should be noted that these templates will have to be integrated into the projects as required by the language, as well as modifying the ‘MakeFile’ in the case of C++.

Good luck with your projects! 🚀🤖🔧
