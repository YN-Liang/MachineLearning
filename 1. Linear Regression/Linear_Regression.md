# Linear Regression 线性回归

## 1. 什么是回归分析
*回归分析*是一种预测性的建模技术，它研究的是因变量（目标）和自变量（预测器）之间的关系。这种技术通常用于预测分析，时间序列模型以及发现变量之间的因果关系。通常使用曲线/线来拟合数据点，目标是使曲线到数据点的距离差异最小。
---
## 2. 什么是线性回归
线性回归是回归问题中的一种，线性回归假设目标值与特征之间线性相关，即满足一个多元一次方程。通过构建损失函数，来求解损失函数最小时的参数w和b。通长我们可以表达成如下公式
$$
\hat y = \omega \cdot x+b
$$
![](http://latex.codecogs.com/gif.latex?\\hat y = \omega \cdot x+b

![](http://latex.codecogs.com/gif.latex?\\sigma=\sqrt{\frac{1}{n}{\sum_{k=1}^n(x_i-\bar{x})^2}})
