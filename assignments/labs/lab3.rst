.. _doc_lab3:


Lab 3 - Wall Following
=======================
.. note:: This is an **INDIVIDUAL** assignment.

.. tip:: Before starting this lab, review the lectures on **PID and LiDAR** to ensure you are familiar with the material.

| **Goals:**
| In this lab, you will implement a PID (proportional integral derivative) controller to make the car drive parallel to the walls of a corridor at a fixed distance. At a high level, you will accomplish this by taking laser scan distances from the Hokuyo LiDAR, computing the required steering angle and speed (drive parameters), an publishing these to the VESC to drive the car. 

| **Learning Outcomes:**
| The following fundamentals should be understood by the students upon completion of this lab:

	* PID controllers
	* Driving the car autonomously via Wall Following

**Required Skills:** ROS, Python/C++

**Allotted Time:** 1 Week

**Latex Source Code:** `Github Repository <https://github.com/f1tenth/f110_ros/tree/master/wall_follow>`_

| **Deliverables:**
| Submit the following as ``studentname.zip`` (replace ``studentname`` with your name)

	#. Your package named ``studentname_wallfollow.zip`` including the wall following node. **Make sure it compiles before you submit after changing the package name.**
	#. Make a youtube video of wall following around the Levine Loop in the simulator add this link to a text file named ``studentname_wallfollow_video.txt``

.. raw:: html

	<iframe width="700" height="800" src="https://drive.google.com/file/d/1tzyfGYq3JjvLlYHIiSTyvoNq4kcPf53n/preview" width="640" height="480"></iframe>
