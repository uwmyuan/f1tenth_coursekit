.. _doc_lecture17:


Lecture 17 - Detection and Pose Estimation
第17讲 - 检测和姿态估计
======================================================

**Overview 概览:** 
	In a race, there are usually multiple players. Now that we know how to map and localize in our environment and path plan to a goal point, how do we take into account another moving vehicle? This lecture goes over a vehicle tracking and prediciton framework that can be used to find the pose of and obstacle vheicle and predict the obstacle vehicle's probable poses in the future.
	在一场比赛中，通常有多辆车。既然我们知道如何在我们的环境和路径规划中绘制地图和定位到目标点，那么我们如何考虑另一个移动的车辆呢？本讲座将介绍一个车辆跟踪和预测框架，该框架可用于找到障碍物的位置和车辆，并预测未来可能出现的障碍物车辆的位置。

**Topics Covered 涵盖课程:**
	-	Single view geometry 单视点几何学
	-	Pose estimation 姿态估计
	-	Homography 单应性
	-	Trajectory prediction 轨迹预测
	-	Using April tags 使用四月标签

**Slides 幻灯片:**

	.. raw:: html

		<iframe width="700" height="500" src="https://www.bilibili.com/read/cv11762172" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

..	
	**Video 视频:**

		.. raw:: html
			<iframe src="//player.bilibili.com/player.html?bvid=BV1fq4y1772u&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


**Links to additional resources 资源链接:**
	- `论文 Model Based Vehicle Detection and Tracking for Autonomous Urban Driving <https://www-cs.stanford.edu/group/manips/publications/pdfs/Petrovskaya_2009_AURO.pdf>`_
	- `预印版论文 TrafficPredict: Trajectory Prediction for Heterogeneous Traffic-Agents <https://arxiv.org/pdf/1811.02146.pdf>`_
	- `预印版论文 The Trajectron: Probabilistic Multi-Agent Trajectory Modeling With Dynamic Spatiotemporal Graphs <https://arxiv.org/pdf/1810.05993.pdf>`_
	- `预印版论文 World Models (paper) <https://arxiv.org/pdf/1803.10122.pdf>`_
	- `技术文档 World Models (interactive) <https://worldmodels.github.io/>`_