---
tags:
  - 机器学习
  - 监督学习
created: 2026-08-02
status: 学习中
---

# 监督学习 (Supervised Learning)

## 机器学习四大分支

- 监督学习 (Supervised Learning)
- 非监督学习 (Unsupervised Learning) → [[Unsupervised-Learning]]
- 推荐系统 (Recommendation System)
- 强化学习 (Reinforcement Learning)

## 一句话定义

> 监督学习是用一组「带正确答案（标签）」的样本，学习输入 x → 输出 y 的映射关系，然后用它来预测新数据。

## 两大任务

监督学习的任务根据输出类型分为两种：

- **回归 (Regression)**：预测**连续数值**，如房价、温度 → 也叫「数值预测」。你所说的"数字预测"本质上就是回归。→ [[Regression]]
- **分类 (Classification)**：输出是一个**离散类标**（label），范围很小（通常就几个类别），**甚至可能不是数字**，如 "垃圾邮件 / 正常邮件"、"猫 / 狗"。→ [[Classification]]

> ⚠️ 术语提醒：与「分类」对应的是「回归」（数值预测），不存在独立的"数字预测"这一叫法。

## 输入可以是多个

- x 不一定是一个数，可以是**多个特征**组成的输入
- 如预测房价：面积、地段、房龄、楼层等都可作为输入特征
- 监督学习本质是"多输入 → 输出"的映射，常写作 x₁, x₂, … → y

## 相关链接

- [[Regression]]
- [[Classification]]