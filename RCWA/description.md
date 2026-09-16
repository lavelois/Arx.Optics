# 场景/应用

光栅：```x``` 方向周期排列, 且每个周期内折射率不均匀, 光沿 ```z``` 方向传播 
即 $\epsilon(x+\Lambda)=\epsilon(x)$

光在光栅中传播时，由于周期结构，会产生很多的衍射级次
要求的就是这些 ```m``` 次衍射波的反射系数和透射系数。

### 反射系数

反射系数表示的是入射到周期结构上的能量, 被分配到第 $m$ 个反射 [Floquet](floquet_mode.md) 衍射模中的比例.

在 RCWA 中, 反射测电场通常展开成

$$E_{ref}(x,z) = \sum_{m}\texttip{\mathbf{r}_{m}}{复数场振幅反射系数}e^{i(k_{x,m}x-k_{z,m}^{(r)}z)}$$

> $r_{m}$ 就是 **复数场振幅反射系数** $$r_{m}=|r_{m}|e^{i\phi_{m}^{(r)}}$$
而 $R_{m}$ 是对应的功率反射率 (diffraction efficiency).

需要注意的是:
$$\boxed{R_{m}\not\equiv|r_{m}|^{2}}$$

因为电磁波真正传输功率的是 [坡印廷矢量](../concept/poynting_vector.md)