---
tags:
  - 机器学习
  - 监督学习
  - 回归
  - 特征缩放
created: 2026-08-02
status: 学习中
---

# 特征缩放 (Feature Scaling)

## 一句话定义

> 把各特征缩放到相近范围（粗略 -1~1，不必严格），让梯度下降大幅提速。

## 为什么

- 多特征取值范围差距太大 → J 的等高线图是细长**椭圆**
- 范围大的特征主导梯度方向，梯度下降走"之"字、很慢
- 缩放到相近范围后等高线变圆，直奔谷底

## 均值归一化 (Mean Normalization)

```
x_new = (x - μ) / (max - min)
```

- μ = 该特征的均值
- 结果以 0 为中心，粗略落在 -1~1

## Z 分数归一化 (Z-score Normalization)

```
x_new = (x - μ) / σ
```

- σ = 该特征的标准差
- 结果均值 0、标准差 1
- 也叫标准化 (Standardization)

## 相关链接

- [[Gradient-Descent]]
- [[Regression]]