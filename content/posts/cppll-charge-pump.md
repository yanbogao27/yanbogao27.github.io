---
title: "CPPLL Charge Pump 测试"
date: 2026-09-14
draft: true
description: "用于测试博客的技术文章与数学公式显示。"
categories:
  - PLL
tags:
  - CPPLL
  - Charge Pump
math: true
---

## 数学公式测试

VCO 的输出频率可以表示为：

\[
f_{VCO}=f_0+K_{VCO}V_{ctrl}
\]

PLL 的一个简化闭环传递函数可以写成：

$$
H(s)=
\frac{K_{PD}K_{VCO}F(s)}
{sN+K_{PD}K_{VCO}F(s)}
$$

其中 \(K_{VCO}\) 表示 VCO 增益，\(K_{PD}\) 表示鉴相器增益。

## 代码测试

```text
Cadence Virtuoso
Spectre
MATLAB