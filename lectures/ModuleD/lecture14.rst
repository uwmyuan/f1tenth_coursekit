.. _doc_lecture14:


Lecture 14 - Rapidly-exploring Random Tree (RRT)
第14讲 - 快速探索随机树算法
====================================================

**Overview 总览:** 
	This lecture goes over a more complex path planning algorithm. It takes into account obstacle avoidance when planning a path from the vehicle's current position to the desired goal position. We will go over different graph/tree search algorithms such as best first search, A*, and Dijkstra's.
	这一讲介绍一种更复杂的路径规划算法。

**Topics Covered 涵盖话题:**
	-	Occupancy grids 占用格点
	-	RRT 快速探索随机树算法
	-	Search algorithms 搜索算法
	-	A\*, Dijkstra's, BFS A星, 迪杰斯特拉算法和广度优先算法

**Associated Assignment 相关作业:** 
	* :ref:`Lab 7: Motion Planning (RRT) <doc_lab7>`

**Slides 幻灯片:**

	.. raw:: html

		<iframe width="700" height="500" src="https://www.bilibili.com/read/cv11729587" frameborder="0" width="960" height="629" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

..
	**Video:**

		.. raw:: html
			<iframe src="//player.bilibili.com/player.html?bvid=BV1R54y157AP&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


**Links to additional resources 资源链接:**
	- `Sampling-based Algorithms for Optimal Motion Planning <https://arxiv.org/pdf/1105.1186.pdf>`_
		- Sections 3.1 and 3.2, and Algorithms 3, 3.3, and 6