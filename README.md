# ROS_Bootcamp
Description about ROS


Q. What is ROS, and its merits and the limitations for robotics?

Ans. Robot Operating System is robotics middleware (i.e. collection of software frameworks for robot software development). Although ROS is not an operating system, it provides services designed for a heterogeneous computer cluster such as hardware abstraction, low-level device control, implementation of commonly used functionality, message-passing between processes, and package management.


    *MERITS*
    > ROS is an open source project with a permissive license.
    > ROS has great simulation tools
    > The same base code and knowledge can be applied to many different kinds of robots : robotic arms, drones, mobile bases, … 
    > Peer-to-peer communication
    > Thin
    > Multi Language
    *LIMITATIONS*
    > Maximum Size of a Message
    > Powerful hardware Required
    
    
Q. Explain the following :
  
  A. Workspace - a temporary digital storage area that contains related data and software files
  
  B. ROS Package - A ROS package is simply a directory descended from ROS_PACKAGE_PATH (see ROS Environment Variables) that has a package.
  
  C. Nodes -  Nodes are combined into a graph and communicate with each other using ROS topics, services, actions, etc
  
  D. Topics - Topics are named buses over which nodes exchange messages.
  
  E. Messages - A message is a simple data structure, comprising typed fields
  
  F. Services - Services are defined using srv files, which are compiled into source code by a ROS client library. 
  
  Q. What is a subscriber and publisher?
  
  Ans The primary mechanism for ROS nodes to exchange data is sending and receiving messages. Messages are transmitted on a topic, and    each topic has a unique name in the ROS network. If a node wants to share information, it uses a publisher to send data to a topic. A node that wants to receive that information uses a subscriber to that same topic. 
 
  Q . Explain the following :
  
  A. Roscore - roscore is a collection of nodes and programs that are pre-requisites of a ROS-based system. You must have a roscore running in order for ROS nodes to communicate. 
  
  B. Rosrun - Rosrun is part of the rosbash suite. It helps to start a program.
  
  C. Rostopic list - rostopic list returns a list of all topics currently subscribed to and published.
  
  D. Rostopic echo - topicname returns the messages being sent from the ROS master about a specific topic, topicname.
  
  E. Rosmsg Show - Display the fields in a ROS message type
  
