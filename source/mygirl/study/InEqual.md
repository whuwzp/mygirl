---
layout: post
title:  "不等式"
date:   2018-06-30 9:00:01 +0800
categories: 数学
tag: 不等式
mathjax: true
---

# 概要
本节关于不等式求解.

## 基本知识

1. 不等式同加同减不变号;
2. 不等式同乘同除正数不变号;
3. 不等式同乘同除负数变号;

## 多式求解

### 原理
1. 正正得正
2. 负负得正(拓展: 偶数个负数相乘为正)
3. 正负得负(拓展: 奇数个负数相乘为负)

### 例题

(1). $$\frac {(x+1) \times (x-3)} {x-2} \leq 0$$
	
**解**:

$$ 
\begin{equation}
\because \ 最终结果 \leq 0 \\
\therefore \ 3个式子中必有奇数个式子满足 \leq 0 \\
\therefore \ 可以分为以下两种情况进行讨论:\\ 

\begin{cases}
	1. \; 3个式子都满足 \leq 0\\
		\qquad \therefore 
		\begin{cases}
			x+1 \leq 0\\
			x-2 \leq 0\\
			x-3 \geq 0
		\end{cases}
		\qquad \Rightarrow \quad x \leq -1\\
		\\			
		\\

	2. \; 只有一个为\leq 0
		\\(因为不知道是哪一个)我们分别假设以下情况:\\

		\begin{cases}
			1.\ 只有x+1 \leq 0, \therefore
				\;
				\begin{cases}
						x+1 \leq 0\\
						x-2 \gt 0 \; (注:分母不能为0)\\
						x-3 \geq 0
				\end{cases}
				\qquad \Rightarrow \quad 此时无解 \\ 
			2.\ 只有x-2 \lt 0, \therefore
				\;
				\begin{cases}
						x+1 \geq 0\\
						x-2 \lt 0 \; (注:分母不能为0)\\
						x-3 \geq 0
				\end{cases}
				\qquad \Rightarrow \quad 此时无解 \\ 
			3.\ 只有x-3 \leq 0, \therefore
				\;
				\begin{cases}
						x+1 \geq 0\\
						x-2 \gt 0 \; (注:分母不能为0)\\
						x-3 \leq 0
				\end{cases}
				\qquad \Rightarrow \quad 2 \lt x \leq 3 \\ 
		\end{cases}

\end{cases}\\

综上所述, 解集为: (-\infty, -1] \cup (2, 3]

\end{equation}
$$

> **[success] 小技巧**

> 我们看到第二种情况下的前两种情况是无解的,这个其实我们可以用逻辑进行判断:

> $$\because (x-3)-(x-2) \lt 0, \; \therefore x-3 \lt x-2 $$

> 同样的方法, 可以证明出:

> $$x-3 \lt x-2 \lt x+1$$

> $$\therefore x-3最小, 如果只有一个\leq 0, 则必定是x-3 $$

> ($$举例: 假如x-2 \leq 0, 则有x-3 \lt x-2 \leq 0, 这样就有两个\leq 0, 不只有一个 $$)

> 用这种方法可以提前知道前两种是无解的了

.

> **[info] 拓展**
>
> 假设题目改成5个式子$$\leq 0$$, 则有奇数个$$\leq 0$$, 也就是分情况为:
$$
\begin{cases}
	只有1个式子\leq 0;\\
	只有3个式子\leq 0;\\
	5个式子都\leq 0
\end{cases}
$$
> 假如题目改成5个式子$$\geq 0$$, 则有偶数个$$\leq 0$$, 也就是分情况为:
$$
\begin{cases}
	0个式子 \leq 0;(所有都\geq 0)\\
	只有2个式子\leq 0;\\
	只有4个式子\leq 0
\end{cases}
$$
>

.

> **[danger] 注意**
>
> 分母不能为0, 看到分母就要开始戒备, 时刻记住  

















