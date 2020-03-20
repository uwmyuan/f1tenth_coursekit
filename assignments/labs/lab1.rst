.. _doc_lab1:


Lab 1 - Intro to ROS
======================
.. note:: This is an **INDIVIDUAL** assignment.

| **Goals:** 
| The goal of this lab assignment is to get you familiar with the various paradigms and uses of ROS and how it can be used to build robust robotic systems. ROS is a meta-operating system which simplifies inter-process communication between elements of a robot's perception planning and control systems.

| **Learning Outcomes:** 
| The following fundamentals should be understood by the students upon completion of this lab:

	* Understanding the directory structure and framework of ROS
	* Understanding how publishers and subscribers are implemented
	* Implementing custom messages
	* Understanding Cmake lists and package.XML files
	* Understanding dependencies
	* Working with launch files
	* Working with Rviz
	* Working with Bag files

**Required Skills:** Python or C++ (or at least some programming experience)

**Allotted Time:** 1 week

**Latex Source Code:** `Github Repository <https://github.com/f1tenth/f110_ros/tree/master/ros_lab>`_

| **Deliverables:**
| Submit the following as ``studentname.zip`` (replace ``studentname`` with your name)

	#. Pdf with answers filled in. (the source LaTex files are provided)
	#. A ROS Package by the name of ``studentname_roslab`` 
	#. the ROS Package should have the following files

		#. ``lidar_processing.cpp`` OR ``lidar_processing.py``
		#. ``scan_range.msg``
		#. ``studentname_roslab.launch``
		#. Any other helper function files that you use.
		#. A ``README`` with any other dependencies your submission requires (you should not need any).

.. tip:: We would highly recommend that you are able to understand this tutorial in both Python and C++. The Autonomous/Robotics industry is heavily C++ oriented, especially outside of machine learning and data science applications. This class will be a good opportunity to get hands-on with C++ implementation in robotic systems. In any case, the lab may be submitted in C++ or Python. At least one lab in the course will require the use of C++; in general both options will be available. All written questions must be answered irrespective of the language you choose for your implementation. The questions titled with Python are for python and C++ is for C++. If the question titles Python & C++ then the same question applies for both Python and C++.

.. raw:: html

	<iframe width="700" height="800" src="https://drive.google.com/file/d/1p-XJmLWq6MfYiHIBPVSEkmM_7eD2a-f9/preview" width="640" height="480"></iframe>