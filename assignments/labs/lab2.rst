.. _doc_lab2:


Lab 2 - Safety
====================================
.. note:: This is an **INDIVIDUAL** assignment.

.. tip:: Before starting this lab, review the lectures on **Automatic Emergency Braking** to ensure you are familiar with the material.

| **Goals:**
| The goal of this lab is to develop a safety node for the race cars that will stop the car from collision when travelling at higher velocities. We will implement Time to Collision using the LaserScan message in the simulator. 

| **Learning Outcomes:**
| The following fundamentals should be understood by the students upon completion of this lab:

	* Using the LaserScan message in ROS
	* Time to Collision (TTC)
	* Safety critical systems

**Required Skills:** Basics of ROS from Lab 1, Python or C++ (or at least some programming experience)

**Allotted Time:** 1 week

**Latex Source Code:** `Github Repository <https://github.com/f1tenth/f110_ros/tree/master/safety>`_

| **Deliverables:**
| Submit the following as ``studentname_lab2.zip`` (replace ``studentname`` with your name)

	#. Your package including the safety node, named as ``studentname_safety``. **Make sure it compiles before you submit after changing the package name.**
	#. Make a youtube video of teleop (manual driving) around the Levine loop (with your safety node on) in the simulator without significant false positives. Add this link to a text file named ``studentname_lab2_video.txt``

.. raw:: html

	<iframe width="700" height="800" src="https://drive.google.com/file/d/1qBCmMB54XrRZbU_A8IiBSO6TwAILfUO8/preview" width="640" height="480"></iframe>
