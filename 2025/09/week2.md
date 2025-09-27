# 2025年九月周报2

Author: Ishgrina

2025.09.15 - 2025.09.21

## 本周工作

主要包括看深度学习网课、阅读文献和帮师哥采数据。

## 深度学习网课

AI -> Machine Learning -> Representation Learning -> Deep Learning.

为什么要提出深度学习？

> Conventional machine-learning techniques were limited in their ability to process natural data in their raw form(Yan LeCun, et.al).

Hebbian Learning

了解AI发展历史（1958 Perceptron， 1973 winter, 1990s CNN）
- 2012: 语音识别， Andrew Ng. Google，AlexNet in ImageNet
- 2014: Deep Q-Learning
- 2016 AlphaGo， Google的机翻系统
- 2019 OpenAI's RL Projects
- 2020 GPT-3, AlphaFold
- 2022 AIGC, ChatGPT
- 2024 Sora, O1(AI开始思考)

### 全连接网络

全连接网络的“基本单元”:单层感知机。

在此基础上，将其在深度上叠加引入多层感知机，也就得到了基础的全连接网络。

### 从逻辑斯蒂回归(Logistic Regression)到单层感知机(Single-Layer Perceptron)

逻辑斯蒂回归(Logistic Regression)与损失函数:

$P(y=1)=f(x;\theta)=\sigma(w^Tx+b)$

Logistic function (or Sigmoid function): 
$$\sigma(x)=\frac{1}{1+e^{-x}}$$

函数关于$x=0$对称，取值范围为$(0,1)$其中$\sigma(x)$可微，可以帮助求解参数。

数据学习方法：最小经验风险（EmpriricalRisk Minimization）

## 文献阅读

### 再读Affective Brain–Computer Interfaces (aBCIs): A Tutorial

对基本的EEG时域、频域特征及数据处理方法（如时域的一阶、二阶差分（First & Second Difference）；差分熵(DE)）加深了解。

准备再学习新概念[Differential Entropy](https://www.sciencedirect.com/topics/engineering/differential-entropy)

## 其他工作

帮助师哥采数据。

## 下周计划

先参加学校课程，然后阅读几篇论文，先了解一下两个应用方向。目前感兴趣的几篇先列一下：

- [EEG Based Emotion Recognition: A Tutorial and Review](https://arxiv.org/abs/2203.11279)
- [Investigating EEG-Based Functional Connectivity Patterns for Multimodal Emotion Recognition](https://arxiv.org/abs/2004.01973)