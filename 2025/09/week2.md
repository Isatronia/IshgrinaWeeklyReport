# 2025年九月周报2

Author: Ishgrina

2025.09.15 - 2025.09.21

## 本周工作

主要包括看深度学习网课、阅读文献和帮师哥采数据。

## 深度学习网课

主要了解监督学习

### 全连接网络

全连接网络的“基本单元”——单层感知机。在此基础上，将其在深度上叠加引入多层感知机，也就得到了基础的全连接网络。

二分类问题与机器学习

### 从逻辑斯蒂回归(Logistic Regression)到单层感知机(Single-Layer Perceptron)

Logistic Regression:

$P(y=1)=f(x;\theta)=\sigma(w^Tx+b)$

Logistic function: $\sigma(x)=\frac{1}{1+e^{-x}}$

函数关于$x=0$对称，取值范围为$(0,1)$其中$\sigma(x)$可微，可以帮助求解参数。

- 损失函数

一般定义损失函数$err(f(x;\theta), y(x))$如下：
$$
err(f(x;\theta),y(x))=
\begin{cases}
-log\sigma(w^Tx+b) & if y=1 \\
-log(1-\sigma(w^T+b)) & if y=0
\end{cases}
$$

数据学习方法：最小经验风险（EmpriricalRisk Minimization）
$$
\theta^*=argmin\frac{1}{N}\sum_{(x^i,y^i)\in X}err(f(x^i;\theta), y(x^i))
$$

## 文献阅读

### Affective Brain–Computer Interfaces (aBCIs): A Tutorial

- EEG Based Emotion Recognition: A Tutorial and Review

## 其他工作

帮助师哥采集数据。
