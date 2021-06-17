.. _doc_lecture04:


Lecture 4 - Laplace Domain Dynamics & PID
第4讲 - 拉普拉斯域动力学与PID控制
===========================================
**Overview 概览:** 
	We command the pid control on vesc, converts rpm requirement to current output for the motor, uses pid to get right current, we give rpm
	我们向VESC发送PID控制指令，VESC将转速要求转化为电机的电流输出，利用PID得到正确的电流，从而达到预定转速。
1) vesc tuning VESC调校
2) wall following (error is distance to wall, left wall right wall wahteves, we control steering angle) - lec 讲座内容为车辆循墙（误差为与墙的距离，墙指的是左边或右边的连续障碍物，控制车辆转向角）

**Topics Covered 涵盖话题:**
	-	Laplace Domain Dynamics 拉普拉斯域动力学
	-	PID Control PID控制
	-	testing 测试

**Associated Assignment 相关作业:** 
	* :ref:`Lab 3: Wall Following <doc_lab3>`

**Slides:**

	.. raw:: html

	 <iframe src="https://www.bilibili.com/read/cv11687774" width="640" height="480"></iframe>

.. **Video:**

	.. raw:: html

	 <iframe src="//player.bilibili.com/player.html?bvid=BV1BN411o79d&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


**Links to additional resources 资源链接:**
	- `调校PID控制器参数的Ziegler-Nichols方法 Ziegler-Nichols method of tuning a PID controller <https://en.wikipedia.org/wiki/Ziegler%E2%80%93Nichols_method>`_
