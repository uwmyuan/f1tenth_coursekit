.. _doc_lecture03:


Lecture 3 - Rigid Body Transformation
第3讲 - 刚体转换
============================================================

**Overview 概览:** 
	A point in the real world can be defined in different ways from different perspectives. If the lidar, which is attached to a moving vehicle, detects an obstacle, we might want to know the obstacle's position in the real world. As the vehicle traverses the environment to create a map of the environment, the algorithm on the vehicle is actually creating multiple submaps and then tying all these submaps together and creating one global solution. In both of these applications, we will need to understand and use reference frames and frame transformations. This lecture will shed light on these two topics.
    现实世界中的一个坐标点可以从不同的角度用不同的方式来定义。如果安装在移动车辆上的激光雷达探测到障碍物，我们可能想知道障碍物在现实世界中的位置。当车辆遍历环境以创建环境地图时，车辆上的算法实际上是创建多个子地图，然后将所有这些子地图合并到一起以创建一个全局地图。在这两种应用中，我们都需要理解和使用坐标参考系和坐标系变换。这次讲座将阐明这两个主题。

**Topics Covered 涵盖话题:**
	-	Coordinate Frames and Reference Frames 坐标系和参考系
	-	Rigid Body Transformations 刚体转换
	-	Frames and Transformations in ROS ROS中的参考系和转换

**Slides 幻灯片:**

	.. raw:: html

	 <iframe width="700" height="500" src="https://www.bilibili.com/read/cv11687726" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

.. **Video:**

	.. raw:: html

	 <iframe src="//player.bilibili.com/player.html?bvid=BV1Ry4y1p7vA&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


**Links to additional resources 资源链接:**
	- `《机器人建模与控制》 Robot Modeling and Control <https://www.amazon.com/Robot-Modeling-Control-Mark-Spong/dp/0471649902/ref=sr_1_1?keywords=Robot+Modeling+and+Control&link_code=qs&qid=1583440764&sr=8-1>`_
	- `译者注：《机器人建模与控制》中译版链接 <https://item.jd.com/11992594.html>。链接仅供参考，译者与某东无利益相关`_
	- `ROS平台Tensorflow v2 tf2_ros <http://wiki.ros.org/tf2_ros>`_ 