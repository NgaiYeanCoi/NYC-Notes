# 学习LaTex笔记 by Ngai Yean Coi 2023年9月5日  

[返回主页](https://www.stayrabbit.top/)  

---
## 目录
- [学习LaTex笔记 by Ngai Yean Coi 2023年9月5日](#学习latex笔记-by-ngai-yean-coi-2023年9月5日)
  - [目录](#目录)
  - [一、前言](#一前言)
  - [二、行内公式和行间公式](#二行内公式和行间公式)
  - [三、LaTex的语法](#三latex的语法)
    - [3.1上标与下标](#31上标与下标)
## 一、前言

## 二、行内公式和行间公式

- `\$...\$` 或者 `\(...\)` 中的数学表达式将会在行内显示。  
- `$$...$$` 或者 `\[...\]` 或者 ```math 中的数学表达式将会在块内显示。 


行内公式：
```

```
$x=\rho\cos\theta$
$y=\rho\cos\theta$
$z=\rho\cos\theta$


行间公式：
```latex{.line-numbers}
$$
\begin{cases}
x=\rho\cos\theta\\
y=\rho\sin\theta\\
z=\rho\tan\theta\\
\end{cases}
$$
```
行间示例：
$$
\begin{cases}
x=\rho\cos\theta\\
y=\rho\sin\theta\\
z=\rho\tan\theta\\
\end{cases}
$$
## 三、LaTex的语法

### 3.1上标与下标

>\$x^2 + y^{12} = 1\$
>\$x_1 + y_{12} = 1$

示例：
$x^2 + y^{12} = 1$
$x_1 + y_{12} = 1$



