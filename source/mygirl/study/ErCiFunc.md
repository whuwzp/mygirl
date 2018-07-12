---
layout: post
title:  "二次函数"
date:   2018-07-02 9:00:01 +0800
categories: 数学
tag: 二次函数
mathjax: true
---

# 概要
本节关于二次函数相关知识求解.

## 基本知识

如下图所示是**$$y = x^2 - 5x +6$$**的图形

{% graph %}
{
    "title": "x^2-5x+6",
    "grid": true,
    "xAxis": {
        "domain": [-2, 6]
    },
    "yAxis": {
        "domain": [-0.5, 8]
    },
    "data": [{
        "fn": "x^2 -5*x +6",
        "closed": false
    }]
}
{% endgraph %}

### 图像
1. 线是由**无数点**构成的, 而这些点(的横纵坐标x,y)都是**满足方程**$$y = x^2 - 5x +6$$的;
2. 横纵坐标也是线, 分别是$$x=0, y=0$$

### 解集
即图中的(2, 0)和(3, 0).

1. 函数意义: 
$$ \begin{cases} y=0 \\ y=x^2-5x+6 \end{cases} \Rightarrow x^2-5x+6 =0 $$ 

2. 图像意义: 
$$\begin{cases} y=0,即x轴 \\ y= x^2-5+6,即二次函数函数图像 \end{cases} \qquad \Rightarrow  两条线的交点,即二次函数与x轴的交点$$

### 对称轴
即图中的$$x=2.5$$

1. 对称轴求法:
$$\begin{cases}1. \ 把式子化成y=ax^2+bx+c;\\ 2.\  x=-\frac {b} {2a}= - \frac {-5} {2 \times 1} = 2.5 \end{cases}$$ 
	

### y的最大值/最小值
对于$$y=ax^2+bx+c$$, 根据对$$x$$是否有范围的约束条件,分为以下两种情况:




$$ 
\begin{equation}


\begin{cases}
	1. \; 无范围约束:  \begin{cases}
		a \lt 0: \ \cap 型, 有最大值\\
		a \gt 0: \ \cup 型, 有最小值
		\end{cases} ,  \qquad 此时在x=-\frac {b} {2a}时取得最值
		\\
		\\

	2. \; 有范围约束: \begin{cases}
		1. 先画出二次函数示意图\\
		2. 在图中标记x的取值范围
		\end{cases} , \quad \qquad 然后,在此范围内找y的最大值或最小值

\end{cases}\\


\end{equation}
$$
