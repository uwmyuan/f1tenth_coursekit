.. _doc_lecture09:


Lecture 9 - Scan Matching I
第9讲 - 扫描匹配I
=============================================

**Overview 概览:** 
	This lecture is part one of three localization lectures. We'll learn how to determine the state (position and orietnation) of a robot with respect to its environment. The F1TENTH vehicle uses range measurements from the lidar to localize. The iterative closest point algorithm and fast correspondence search are explained. At the end of the lecture, there is an overview of Lab 5.
	这一讲是三次定位话题讲座的第一部分。我们将学习如何确定机器人相对于其环境的状态（位置和方向）。F1TENTH小车使用激光雷达的距离测量来定位。介绍了迭代最近点算法和快速对应搜索算法。最后介绍了作业5。
**Topics Covered 涵盖话题:**
	-	Localization/SLAM 定位，同步定位与建图算法
	- 	Scan Matching 扫描匹配算法
	-	Iterative Closest Point 迭代最近点算法
	-	Fast Correspondence Search 快速对应搜索算法

**Associated Assignment 相关作业:** 
	* :ref:`Lab 5: Scan Matching 扫描匹配 <doc_lab5>`

**Slides 幻灯片:**

	.. raw:: html

	  <iframe width="700" height="500" src="https://www.bilibili.com/read/cv11703062" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
	  <iframe width="700" height="500" src="https://www.bilibili.com/read/cv11703074" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


	**Video 视频:**

		.. raw:: html
			<iframe src="//player.bilibili.com/player.html?aid=715529549&bvid=BV17Q4y1o7Vr&cid=337893849&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

**Links to additional resources 资料链接:**
	- `参考文献 An ICP variant using a point-to-line metric <https://censi.science/pub/research/2008-icra-plicp.pdf>`_
	- `凸优化课程 Convex Optimization course <https://see.stanford.edu/Course/EE364A>`_