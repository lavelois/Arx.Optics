# 坡印廷矢量

坡印廷矢量是电磁学中描述电磁能量流动方向和密度的物理量, 通常记为
$$\vec{S} = \texttip{\vec{E}}{电场强度} \times \texttip{\vec{H}}{磁场强度}$$

### 物理意义
- 方向: 电磁能量传播的方向
- 大小: 能流密度, 单位时间内通过垂直于传播方向的单位面积的电磁能量
- 单位: $\rm{W/m^{2}}$, 瓦每平方米

对于<span title = "时间简谐, 即电磁场的每一个分量都随时间按同一频率的正弦/余弦规律变化">时谐</span>电磁场, 常用复数坡印廷矢量
$$\vec{S}_{c} = \frac{1}{2}\vec{E}\times\vec{H}$$

其**实部** $\langle\vec{S}\rangle = \frac{1}{2}Re(\vec{E}\times\vec{H}^{*})$ 表示时间平均能流密度
若<span title="相量就是正弦量的复数表示：用模表示振幅或有效值，用幅角表示相位，把时间因子 $e^{j \omega t}$ 省略掉">相量</span>取有效值, 则平均能流密度为
$$\langle\vec{S}\rangle = Re(\vec{E}\times\vec{H}^{*})$$

### 坡印廷定理
> 表示能量守恒, 即电磁能量流出某区域、区域内能量增加以及电场对电流做功消耗的能量之间满足守恒关系。

微分形式:
$$\nabla\cdot\vec{S} + \frac{\partial{u}}{\partial{t}} = -\vec{J}\cdot\vec{E}$$

积分形式:
$$\oint_{S}\vec{S}\cdot\vec{A} + \frac{d}{dt}\int_{V}udV = -\int_{V}\vec{J}\cdot\vec{E}dV$$

其中:
$$u = \frac{1}{2}(\vec{E}\cdot\vec{D} + \vec{B}\cdot\vec{H})$$