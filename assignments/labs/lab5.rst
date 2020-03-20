.. _doc_lab5:


Lab 5 - Scan Matching
======================
.. note:: This is an **GROUP** assignment.

.. tip:: Before starting this lab, review the lectures on **Scan Matching** to ensure you are familiar with the material.

| **Goals:**
| This lab deals with the problem of localization in Robotics and provides an introduction to localization and why is it important in the autonomy stack. Through the lab, one of the most fundamental algorithms of localization, *scan matching*, is implemented. It uses the *Iterative Closest Point* algorithm which has been introduced
in class. You can take reference from the `Andre Censi PLICP paper <https://censi.science/pub/research/2008-icra-plicp.pdf>`_. By the end of this lab you will have a certain level of knowledge and expertise in localization of a robot given a mapped environment and how it is important in path planning and trajectory tracking.

| **Learning Outcomes:**
| The following fundamental should be understood by the students upon completion of this lab:

	* Localization
	* Odometry Estimation
	* Convex optimization
	* C++ OOP
	* Quadratic Programming

**Required Skills:** ROS, Python/C++

**Allotted Time:** 1 week

**Latex Source Code:** `Github Repository <https://github.com/f1tenth/f110_ros/tree/master/scan_matching>`_

| **Deliverables:**
| Submit the following as ``groupnumber_lab5.zip`` (replace ``number`` with your group number)

	#. Answers to the theoretical questions in a separate pdf file. You can give handwritten answers converted to pdf files (the answers should be clear)
	#. A ROS Package by the name of ``studentname_scan_matching_lab``. **Make sure it compiles before you submit after changing the package name.**
	#. the ROS Package should have the following files

		#. All the existing files of the skeleton with all the functions specified in this handout filled in.
		#. A short video of the simulation demonstrating the odometry estimation
		#. A PDF writeup describing your approach and the roadblocks you encountered in the development.
		#. Writeup should include plots of measurements of performance and analysis of results
		#. Any other helper function files that you use.
		#. A ``README`` with any other dependencies your submission requires.


.. raw:: html

	<iframe width="700" height="800" src="https://drive.google.com/file/d/1g27WUTeoxrznFozfY0Vj45V1evVw1uTA/preview" width="640" height="480"></iframe>