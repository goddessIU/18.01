第一次写总结，如有不好请指正

# 第一章--导数
1. 首先是直接引入切线和导数的概念，做一条割线，两个割点一定一动，动点向定点逼近，最后成为切线。切线斜率是导数。
2. 然后就给出了导数定义，在此基础上，导数的加减乘除法则以及chain rule等。
3. 同时计算了一些基本函数的公式，尤其是指数函数的求导计算，是很有意思的。
4. 还有continuity部分的讨论，极限等于值，则连续；以及可导推出连续等。


# 第二章--导数的应用
1. 首先是linear approximation和quadratic approximation，利用导数做近似。其实就是泰勒展开的前几项，但是从导数的观点推导而来。linear approximation: f(x) 约等于 f(x0) + f'(x0)(x - x0)
2. 然后，基于一阶导数，二阶导数，可以画函数的草图。求最大最小值问题。related rate，以及newton method
3. 比较重要的Mean value theorem,可以用它做一些不等式证明类问题等。
4. 微分的介绍，我的感触，从导数看dy/dx是一个整体；从微分看dy dx可以分开独立，以商的形式看dy/dx。
5. 不定积分求解和基本的微分方程(分离变量就够用了)

# 第三章--积分
1. 首先定积分通过求曲线下方面积引入，以求矩形面积为引入。以及一些基本性质。
2. 然后是两个定积分基本定理+证明。
3. 有了定积分的加持，就可以以定积分的形式表示很多新函数，如err function。包括log也是，并且借助以上的定理性质，比如可以对积分求导等，我们可以画这些函数的草图。
4. 然后就是积分的应用，求面积（对dx 或者dy两个角度） 求体积（disk和shell两种）求均值 求加权平均等。借助求体积，得e^(-x^2)从0到无穷的积分值
5. 在一些我们不是能求出原函数的情况下，我们也有些近似的方法求积分值（Riemann Sum  Trapezoidal Rule  . Simpson’s Rule ）

# 第四章--积分
1. 求积分的一些进阶方法：三角代换、Partial Fractions、分部积分。
2. 以及应用：求弧长、借助弧长求三维物体的表面积、参数方程、极坐标等。

# 第五周--其他
1. 洛必达  
2. improper integral（判断是converge or diverge）
3. infinite series (geometric series  Power Series),并且判断converge（Integral Comparison、limit comparison）
4. taylor's Formula以及结合泰勒公式，我们可以对展开式进行加减乘除 求导 积分 替换x等操作，获得其他函数的展开式
5. 以及base point不是x=0，而是x=b的泰勒展开式