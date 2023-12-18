---
layout: page
permalink: /projects/index.html
title: Projects
---


##### Latex 工程
###### 基金类latex模板
旨在帮助各位老师方便用latex完成国家自然科学基金的项目申请与结题，浙江省自然科学基金项目申请与结题。<font color=blue>相关模板可通过以下蓝色超链接下载使用。</font>

- [<font color=blue>国家自然科学基金项目申请书latex模板</font>](https://github.com/wennboo/NSFC-application-report-latex)
- [<font color=blue>国家自然科学基金项目结题报告latex模板</font>](https://github.com/wennboo/NSFC-concluding-report-latex)
- [<font color=blue>浙江自然科学基金项目结题报告latex模板</font>](https://github.com/wennboo/ZPNSF-concluding-report-template/tree/main)

###### 硕博开题报告及论文latex模板
旨在帮助杭州电子科技大学本硕博方便用latex完成学位论文。<font color=blue>相关模板可通过以下蓝色超链接下载使用。</font>

- [<font color=blue>杭州电子科技大学硕博学位论文latex模板</font>](https://github.com/wennboo/HDU-latex-template-for-master)
- [<font color=blue>杭州电子科技大学开题/实验报告latex模板</font>](https://github.com/wennboo/HDU-opening-experimental-report)
- [<font color=blue>自动化学院本科生开题报告及毕业设计latex模板</font>](https://github.com/wennboo/HDU-Automation-School-latex-template-for-bachelor)

##### 自主无人与无人集群演示系统开发
旨在完成四轴无人机个体开发，基于UWB的室内定位系统开发，并搭建由无人机/无人车构成的异构无人集群系统，完成分布式任务分配、集群编队等演示示范，<font color=blue>相关工程可通过蓝色标题超链接下载查看。</font>

###### [<font color=blue>无人机及基于uwb的定位系统开发</font>](https://github.com/wennboo/UWB-based-Quadrotor-Swarm-Demo-System)
<img src="{{ site.url }}/images/uav0.png" class="floatpic" width="320" height="480">
项目简介：当前已经完成四轴无人机个体开发（代码基于网上开源项目，全部重新编写，架构清晰，便于修改）及基于uwb的无人机无头模式自定位与导航。后续需进一步开发有头模式无人机自主避障与导航，以及基于2.4g模块的无人机集群组网。



###### [<font color=blue>基于深度相机的领导-追随者移动小车跟随控制</font>](https://github.com/wennboo/YOLOv5-based-Vehicle-Detection-and-Formation-Tracking)
<img src="{{ site.url }}/images/tracking0.png" class="floatpic" width="320" height="480">
项目简介：当前已经基于深度相机及YOLOv5等算法完成了1v1领导追随者型移动小车跟随控制算法开发与部署。后续将对检测模型轻量化、位姿高精度估计、自主避障等做进一步研究，并完成更大规模的基于视觉的集群演示验证。



###### [<font color=blue>基于单目视觉的领导-追随者移动小车跟随控制</font>](https://github.com/wennboo/Ground-Segmentation-based-Monocular-depth-estimation)
<img src="{{ site.url }}/images/depth-est0.png" class="floatpic" width="320" height="480">
项目简介：当前已经基于SE DenseNet模型已完成基于单目的相对深度估计。后续将对估计模型做轻量化处理，并进一步研究基于单目的领导-追随者移动小车跟随控制，完成自主避障、集群演示示范。



##### 多智能体强化学习及其应用
旨在完成面向多智能体强化学习的类似gym的一些标准环境开发，例如追逃博弈、资源分配等，为强化学习算法的验证提供良好的验证环境。<font color=blue>相关工程可通过蓝色标题超链接下载查看。</font>

###### [<font color=blue>基于多智能体强化学习的非完整智能体追逃问题</font>](https://github.com/wennboo/Multi-Agent-Pursuit-Reinforce-Learning-Environment)
项目简介：完成了二维空间面向强化学习的非完整多智能体追逃环境编写，基于此环境，构建MADDPG算法，实现了智能体的自主决策。后续将对模型进行统一表征处理，使其能适应智能体数目可变的情形，以及考虑三维空间的情形。

###### [<font color=blue>基于多智能体强化学习的无人机集群对抗机动决策</font>](https://github.com/wennboo/Multi-Agent-Pursuit-Reinforce-Learning-Environment)
项目简介：初步完成了三维空间面向强化学习的多机对抗协同机动决策环境编写。后续将利用强化学习算法，实现多对多对抗下无人机自主机动决策。

###### [<font color=blue>基于多智能体强化学习的雷达干扰资源分配</font>](https://github.com/wennboo/Multi-Agent-Pursuit-Reinforce-Learning-Environment)
项目简介：初步完成了面向强化学习的一干扰机对多雷达的干扰资源分配环境编写，基于此环境，利用DQN算法初步实现了干扰机的干扰资源自主分配。后续将考虑更一般的贴近实际的对抗场景，并考虑多对多环境下的干扰资源分配问题，以及面向雷达探测资源分配问题，开发强化学习环境。

##### 多智能体自主协同控制
旨在总结自己在多智能体自主协同控制方向的一些成果及对应代码。<font color=blue>相关代码可通过蓝色标题超链接下载查看。</font>
###### [<font color=blue>多智能体协同任务分配</font>](https://github.com/wennboo/Distribution-Auction-Algorithm-based-UAV-Swarm-Task-Assignment)

项目简介：针对无人机集群等多智能体系统的协同静态任务分配问题，考虑了两种通信拓扑架构（连通图、联邦架构），完成了基于分布式拍卖算法的程序编写与仿真。后续将考虑更加真实的智能体自身硬件、执行任务环境因素、动态任务分配情形，完成程序编写与仿真。

###### [<font color=blue>多智能体一致性</font>](https://github.com/wennboo/Consensus-Results-of-Single-or-Second-Order-MASs-and-Applications)
<img src="{{ site.url }}/images/consensus0.png" class="floatpic" width="320" height="480">
项目简介：针对一阶多智能体系统，完成了考虑相对状态依赖的噪声、乘性噪声等存在噪声扰动下的程序编写与仿真。针对二阶多智能体系统，完成了考虑相对状态依赖的噪声下的程序编写与仿真。

###### [<font color=blue>多智能体协同定位</font>](https://github.com/wennboo/Distributed-Network-Localization-With-Noisy-Measurement-and-Communication-Information)

项目简介：针对基于相对位置的不依赖于全局参考坐标系的二维空间多智能体分布式定位问题，完成了考虑距离噪声、角度噪声等存在噪声扰动下的程序编写与仿真。

###### [<font color=blue>多智能体分布式编队</font>](https://github.com/wennboo/Noisy-Relative-Position-Measurement-based-Formation-Control)
<img src="{{ site.url }}/images/formation0.png" class="floatpic" width="320" height="480">
项目简介：针对基于相对位置的不依赖于全局参考坐标系的二维空间多智能体分布式静态编队控制问题，完成了考虑距离噪声、角度噪声等存在噪声扰动下的方位估计、编队程序编写及仿真，并与其它两种算法进行了比较。