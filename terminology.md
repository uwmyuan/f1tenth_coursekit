# 机器人技术学习攻略 Robotics Learning Guide

## 背景知识 Prerequisite
> Disclaimer 注：链接为本文档作者任性地给出，仅供参考，本文档作者与链接中的机构无利益相关。

| 英文 | 中文 | 相关链接 |
| ---- | ---- | ---- |
| Convex Optimization | 凸优化 | https://see.stanford.edu/Course/EE364A |
| Programming Language Python or C++ | 编程语言Python或C++ |
| Principle of Automatic Control | 自动控制原理 | 
| Robotics: Computational Motion Planning | 机器人技术：计算动作规划 | https://www.coursera.org/learn/robotics-motion-planning |
| Robotic Motion Planning  | 机器人动作规划 | https://www.cs.cmu.edu/~motionplanning/ |
| Robot Operation System | 机器人操作系统 | http://wiki.ros.org/ROS/Tutorials |
| Artificial Intelligence for Robotics | 机器人的人工智能 | https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373 |
| Statistical Techniques in Robotics | 机器人的统计方法 | http://www.cs.cmu.edu/~16831-f12/notes/F14/16831_lecture05_gseyfarth_zbatts.pdf |
| Linux OS (Ubuntu) | Linux操作系统基本操作 |  |


## 参考书目 books
> Disclaimer 注：推荐书目、推荐星级皆为本文档作者任性地给出。没有中译本的书名由本文档作者任性地翻译。链接仅供参考，本文档作者与某东无利益相关。

| 英文书名 | 中文书名 | 推荐星级 | 链接 |
| ---- | ---- | ---- | ---- |
| Robot Modeling and Control | 机器人建模与控制 | \*\*\* | https://item.jd.com/11992594.html |
| Principles of Robot Motion: Theory, Algorithms, and Implementations | 机器人动作原理 | \*\* |
| A Systematic Approach to Learn Robot Programming with ROS | ROS机器人编程：原理与应用 | \* | https://item.jd.com/12528807.html |
| Programming Robots with ROS: A Practical Introduction to the Robot Operating System | ROS机器人编程：机器人操作系统实用指南 |\* |  |

# 常用术语对照表 Glossary 

## 机器人技术 Robotics
| 英文 | 中文 | 详细解释 |
| ---- | ---- | ---- |
| autonomy | 机器人学 | | 
| mechatronics | 机械电子技术 | |
| autonomous | 自主 | 完全自动， SAE L4-L5的自动驾驶水平 | 
| automatic | 自动 | 有时也用automated |
| vehicle | 小车，车辆，载具 | 狭义上指本课程中的模型车，泛指各类车辆，广义上泛指车辆、船舶、航空器等 |
| brushless motor | 无刷电机 | |
| variant | 变体 | |
| mapping | 建图（绘制地图） | 在不同语境中有不同含义，有映射、绘制地图、在地图上标点等含义 |
| localization | 定位 | 获取小车的坐标和姿态 |
| filter | 滤波器 | 一类估计、预测算法 |
| homography | 单应性 | |
| trajectory | 轨迹 | 小车实际经过的坐标点的序列，有时与路径path混用 |
| April Tag | 四月标签 | 特指一种计算机视觉方法 |
| range sensor | 远距传感器 | 如激光雷达、立体摄像头 |
| odometry | 里程计，测程 | 如视觉惯性测程，包括车辆速度、转向角等 |
| range-rate | 接近率 | 本教程中距离对时间的导数 |
| robot | 机器人 | 本教程中指小车 |
| world, environment | 世界，环境 | 指机器人或小车探测、运动的总空间 |
| actuation | 执行 | 指小车上行驶系统、转向系统的功能 |
| servo motor | 伺服电机 |
| correspondence search | 对应搜索算法 |  
| odds function | 优势函数 | |
| Gauss Elimination | 高斯消去法 | |
|  ||

## 物理学 Physics
| 英文 | 中文 | 详细解释 |
| ---- | ---- | ---- |
| frame | 参考系 | 指经典物理学上的意义 |
| Euler angle | 欧拉角 | |
| axis angle | 坐标角 | 
| translation | 平移|
| displacement | 位移 | | 
| rigid body | 刚体 ||
| transform | 变换 |
| convention | 转换 ||
| inertia | 转动惯量 |


## 电子电力 自动控制 EE & Control & Math
| 英文 | 中文 | 详细解释 |
| ---- | ---- | ---- |
| Laplace domain | 拉普拉斯域 | |
| Laplace transformation | 拉普拉斯变换，拉氏变换，复变函数理论 | 
| signal | 信号 |  |
| step response | 阶跃响应 | |
| PID | 比例积分微分算法 |
| controller | 控制器 | 
| plant | 设备，这里指执行器 | 
| steady-state error | 稳态误差 |
| complex | 复数 |
| imaginary | 虚数 |
| Analytic Extension theorem | 解析扩张定理 | 
| unit step | 单位阶跃（函数） |
| gain | 增益 |
| denominator | 分母 |


## 机器学习 Machine Learning
| 英文 | 中文 | 详细解释 |
| ---- | ---- | ---- |
| deep learning | 深度学习 | 使用深度神经网络完成如分类、回归任务的技术 |
| Q-learning | Q-学习 | 一种强化学习方法 |
| binary classifer | 二元分类器 | |
| outlier | 离群点 | 


## 计算机科学 编程 通信 网络 CS & Programming & Communication & Network
| 英文 | 中文 | 详细解释 |
| ---- | ---- | ---- |
| message | 消息 | |
| header | 消息头部 | 指通信技术上的一条消息中指示性的部分，与消息内容（body）相对 |
| broadcaster | 广播器 | |
| lisener | 监听器 | |
| broadcast | 广播 | |
| subscribe | 订阅 | |
| API | 应用程序接口 | 一种软件工程概念 |
| jump table | 跳表 | 一种数据结构 |
| A\* | A星 | 一种最短路径搜索算法 |
| Dijkstra's | 迪杰斯特拉算法 | 一种最短路径搜索算法 |
| BFS | 广度优先算法 | 一种搜索算法 |
| Object detection | 目标检测算法 |
| Multi-view geometry | 多视点几何学 |
| recursion | 递归 |  |
| heuristic | 启发式算法，启发式权值 |
| tuple | 元组 | 
| graph | 图 | 一种数据结构 |
| tree | 树 | 一种数据结构 |
| best first search | 最优优先搜索 | 
| breadth-first search | 广度优先搜索 |
| depth-first search | 深度优先搜索 |
| uniform cost search | 统一成本搜索 |

## 常用缩略词对照表 Abbreviation
| 缩略词 | 英文 | 中文 | 
| ---- | ---- | ---- | 
| AV | Autonomous Vehicle | 自主载具（汽车） | 
| ROS | Robot Operation System | 机器人操作系统 |
| PID | Proportional Integral Derivative | 比例积分微分（控制器、控制算法）|
| ESC | Electric Speed Control | 电子调速器，简称电调 |
| VESC | Vedder Electric Speed Control | 本杰明（式）电调，一种由Benjamin Vedder创作的开源硬件 |
| SLAM | Simultaneous Localization and Mapping Algorithm | 同步定位与建图算法 |
| RRT | Rapidly-exploring Random Tree | 快速探索随机树算法 |
| YOLO | You Only Look Once | YOLO，一种实时目标检测深度神经网络 |
| CNN | Convolutional Neural Network | 卷积神经网络 |
| MPC | Model Predictive Control | 模型预测控制 |
| RL | Reinforcement Learning | 强化学习，增强学习 |
| V2V | Vehicle to Vehicle | 车对车（通信），常与车联网相关|
| BFS | Breadth First Search | 广度优先算法 |
| AEB | Automatic Emergency Braking | 自动紧急制动 |
| TTC | Time-to-collision | 即将碰撞时间 |
| F1TENTH, F1/10 | F1 1/10 scale race car | 本教程的专有名词，指十分之一尺度模型车的方程式赛车 |
| API | Application Programming Interface | 软件工程概念，应用程序接口 |
| PWM | Pulse Width-Modulated | 脉宽调制 |
| rpm | revolution per minute | 转每分，一种转速单位 |
| s.t. | subject to | 受限于 |
| ODE | Ordinary Differential Equation | 常微分方程 |
| BLDC | Brushless Direct Current | 无刷直流（电机）|
| APF | Artificial Potential Fields | 人工势场 |
| ICP | Iterative Closest Point | 迭代最近点算法 |
| QCQP | Quadratic Constrained Quadratic Program | 二次约束二次规划模型 | 
| EKF | Extended Kalman Filter | 扩展卡尔曼滤波 |
| MAP | Maximum a Posteriori | 最大后验（估计） |
| LMS | Least Min Square | 最小均方误差 |
| SVD | Singular Value Decomposition | 奇异值分解 |

# 文档版权说明 License
作者 Author and maintainer: Yun Yuan (yun dot yuan at utah dot edu)

版权所有，禁止转载，仅供个人使用，违者必究。

All Rights Reserved. For your personal use only. 