---
layout: page
permalink: /projects/index.html
title: Projects
---


#### Project on Latex（Latex 工程）
##### 基金类latex模板
旨在帮助各位老师方便用latex完成国家自然科学基金的项目申请与结题，浙江省自然科学基金项目申请与结题。非官方模板，如若使用，后果自负！！！<font color=red>相关模板可通过以下超链接访问仓库，下载使用。</font>

- [国家自然科学基金项目申请书latex模板](https://github.com/wennboo/NSFC-application-report-latex)
- [国家自然科学基金项目结题报告latex模板](https://github.com/wennboo/NSFC-concluding-report-latex)
- [浙江自然科学基金项目结题报告latex模板](https://github.com/wennboo/ZPNSF-concluding-report-template/tree/main)

##### 硕博开题报告及论文latex模板
旨在帮助杭州电子科技大学本硕博方便用latex完成学位论文。非官方模板，如若使用，后果自负！！！<font color=red>相关模板可通过以下超链接访问仓库，下载使用。</font>

- [杭州电子科技大学硕博学位论文latex模板](https://github.com/wennboo/HDU-latex-template-for-master)
- [杭州电子科技大学开题/实验报告latex模板](https://github.com/wennboo/HDU-opening-experimental-report)
- [自动化学院本科生开题报告及毕业设计latex模板](https://github.com/wennboo/HDU-Automation-School-latex-template-for-bachelor)

#### Project on autonomous unmanned systems and unmanned swarm systems（自主无人系统与无人集群系统开发）
旨在完成四轴无人机个体开发，基于UWB的室内定位系统开发，并搭建由无人机/无人车构成的异构无人集群系统，完成分布式任务分配、集群编队等演示示范，<font color=red>可通过标题超链接访问对应仓库，下载查看。</font>

##### [无人机及基于uwb的定位系统开发](https://github.com/wennboo/UWB-based-Quadrotor-Swarm-Demo-System)
<img src="{{ site.url }}/images/uav0.png" class="floatpic" width="240" height="320">
项目简介：当前已经完成四轴无人机个体开发（代码基于网上开源项目，全部重新编写，架构清晰，便于修改）及基于uwb的无人机无头模式自定位与导航。后续需进一步开发有头模式无人机自主避障与导航，以及基于2.4g模块的无人机集群组网。



##### [基于深度相机的领导-追随者移动小车跟随控制](https://github.com/wennboo/YOLOv5-based-Vehicle-Detection-and-Formation-Tracking)
<img src="{{ site.url }}/images/tracking0.png" class="floatpic" width="240" height="320">
项目简介：当前已经基于深度相机及YOLOv5等算法完成了1v1领导追随者型移动小车跟随控制算法开发与部署。后续将对检测模型轻量化、位姿高精度估计、自主避障等做进一步研究，并完成更大规模的基于视觉的集群演示验证。



##### [基于单目视觉的领导-追随者移动小车跟随控制](https://github.com/wennboo/Ground-Segmentation-based-Monocular-depth-estimation)
<img src="{{ site.url }}/images/depth-est0.png" class="floatpic" width="240" height="320">
项目简介：当前已经基于SE DenseNet模型已完成基于单目的相对深度估计。后续将对估计模型做轻量化处理，并进一步研究基于单目的领导-追随者移动小车跟随控制，完成自主避障、集群演示示范。



#### Project on Multi-agent reinforcement learning and applications（多智能体强化学习及其应用）

##### [基于多智能体强化学习的非完整智能体追逃问题](https://github.com/wennboo/Multi-Agent-Pursuit-Reinforce-Learning-Environment)
项目简介：完成了二维空间面向强化学习的非完整多智能体追逃环境编写，基于此环境，构建MADDPG算法，实现了智能体的自主决策。后续将对模型进行统一表征处理，使其能适应智能体数目可变的情形，以及考虑三维空间的情形。

##### [基于多智能体强化学习的无人机集群对抗机动决策](https://github.com/wennboo/Multi-Agent-Pursuit-Reinforce-Learning-Environment)
项目简介：初步完成了三维空间面向强化学习的多机对抗协同机动决策环境编写。后续将利用强化学习算法，实现多对多对抗下无人机自主机动决策。

##### [基于多智能体强化学习的雷达干扰资源分配](https://github.com/wennboo/Multi-Agent-Pursuit-Reinforce-Learning-Environment)
项目简介：初步完成了面向强化学习的一干扰机对多雷达的干扰资源分配环境编写，基于此环境，利用DQN算法初步实现了干扰机的干扰资源自主分配。后续将考虑更一般的贴近实际的对抗场景，并考虑多对多环境下的干扰资源分配问题，以及面向雷达探测资源分配问题，开发强化学习环境。

#### Project on Multi-agent coordinated control（多智能体协同控制）

##### [多智能体协同任务分配](https://github.com/wennboo/Distribution-Auction-Algorithm-based-UAV-Swarm-Task-Assignment)

项目简介：针对无人机集群等多智能体系统的协同静态任务分配问题，考虑了两种通信拓扑架构（连通图、联邦架构），完成了基于分布式拍卖算法的程序编写与仿真。后续将考虑更加真实的智能体自身硬件、执行任务环境因素、动态任务分配情形，完成程序编写与仿真。

##### [多智能体一致性](https://github.com/wennboo/Consensus-Results-of-Single-or-Second-Order-MASs-and-Applications)
<img src="{{ site.url }}/images/consensus0.png" class="floatpic" width="240" height="320">
项目简介：针对一阶多智能体系统，完成了考虑相对状态依赖的噪声、乘性噪声等存在噪声扰动下的程序编写与仿真。针对二阶多智能体系统，完成了考虑相对状态依赖的噪声下的程序编写与仿真。

##### [基于相对位置的多智能体分布式定位](https://github.com/wennboo/Distributed-Network-Localization-With-Noisy-Measurement-and-Communication-Information)

项目简介：针对基于相对位置的不依赖于全局参考坐标系的二维空间多智能体分布式定位问题，完成了考虑距离噪声、角度噪声等存在噪声扰动下的程序编写与仿真。

##### [基于扰动相对位置的多智能体分布式静态编队控制](https://github.com/wennboo/Noisy-Relative-Position-Measurement-based-Formation-Control)
<img src="{{ site.url }}/images/formation0.png" class="floatpic" width="240" height="320">
项目简介：针对基于相对位置的不依赖于全局参考坐标系的二维空间多智能体分布式静态编队控制问题，完成了考虑距离噪声、角度噪声等存在噪声扰动下的方位估计、编队程序编写及仿真，并与其它两种算法进行了比较。