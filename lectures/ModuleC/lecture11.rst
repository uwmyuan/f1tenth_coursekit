.. _doc_lecture11:


Lecture 11 - Particle Filters
第11讲 - 粒子滤波器
=============================================

**Overview 概览:** 
	This is the third installment in the Localization lectures. Given inputs of laser scan data, a control input, and a map, we want to output a pose and some "particles". This lecture is divided into three parts: 1) going over the particle filter localization algorithm, 2) tuning the alrogithm, and 3) additional resources and a hands on tutorial. Expect a dense but extremely informative lecture.
	这是有关定位问题的第三个讲座。给定激光扫描数据、控制输入和地图的输入，我们想要输出一个姿态和一些“粒子”。本课程分为三个部分：1）回顾粒子滤波定位算法，2）调整算法，3）附加资源和实践教程。期待一场信息量大、内容丰富的讲座。
**Topics Covered 涵盖话题:**
	-	Particle filters 粒子滤波器

**Slides 幻灯片:**

	.. raw:: html
		
		<iframe width="700" height="500" src="https://www.bilibili.com/read/cv11703266" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

.. 
	**Video:**

		.. raw:: html
			<iframe src="//player.bilibili.com/player.html?bvid=BV1wK4y1o76s&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


**Links to additional resources 资源链接:**
	- `专著 S. Thrun, W. Burgard. “Probabilistic Robotics.” Chapter 4 and Chapter 8. <http://www.probabilistic-robotics.org/>`_
	- `公开课程 S. Thrun. “Artificial Intelligence for Robotics, Lesson 3.” Udacity. <https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373>`_
	- `论文 S. Thrun, D. Fox, W. Burgard and F. Dellaert. “Robust Monte Carlo Localization for Mobile Robots.”​ Artificial Intelligence Journal. 2001. <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.71.6016&rep=rep1&type=pdf>`_
	- `论文 D. Fox, W. Burgard, and S. Thrun. “Markov localization for mobile robots in dynamic environments,” ​ Journal of Artificial Intelligence Research ​ , vol. 11, pp. 391427, 1999. <http://www.jair.org/media/616/live-616-1819-jair.pdf>`_
	- `论文 D. Fox. “KLD-sampling: Adaptive particle filters,” Advances in Neural Information Processing Systems 14 (NIPS), Cambridge, MA, 2002. MIT Press. <https://papers.nips.cc/paper/1998-kld-sampling-adaptive-particle-filters.pdf>`_
	- `课程材料 D. Bagnell “Particle Filters: The Good, The Bad, The Ugly” <http://www.cs.cmu.edu/~16831-f12/notes/F14/16831_lecture05_gseyfarth_zbatts.pdf>`_
	- `预印版论文 C. Walsh, S. Karaman. “CDDT: Fast Approximate 2D Ray Casting for Accelerated Localization.” Arxiv, 2017. <http://arxiv.org/abs/1705.01167>`_


