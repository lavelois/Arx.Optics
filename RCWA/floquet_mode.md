# Floquet Mode - 弗洛凯模

> 本质和衍射级次意义相近，是周期结构中的电磁场模式。
**但不是所有 Floquet 模都是传播模，存在使模场振幅衰减的倏逝模。**

## 表示形式
第 ```m``` 阶 Floquet 模可以写成:

$$E_m(x,z) = E_{0,m}e^{i(k_{x,m}x+k_{z,m}z)}$$

其中, 

$$E_{0,m} = \begin{bmatrix}
E_{x,m}\\
E_{y,m}\\
E_{z,m}\\
\end{bmatrix}$$

$E_{*,m}$ 场振幅, $k_{m}$ 为 [波矢](..\concept\wave_number_k.md)

$E_{*,m}$ 还表示偏振状态
对于常见二维 RCWA:
- 结构沿 $x$ 周期变化, 沿 $y$ 不变
- 波在 $x-z$ 平面传播

当 $E_{x,m},E_{z,m}\neq0$ 且 $E_{y,m}=0$ 时, 为 ``TM`` 偏振, 反之, 为 ``TE`` 偏振
> TE 模的特点是： 电场垂直于传播平面, 表示为: $$E_{m}^{TE} = 
\begin{bmatrix}
0\\E_{y,m}\\0
\end{bmatrix} 
e^{i(k_{x,m}x+k_{z,m}z)}$$
