# filter
median_filter average_filter gauss_filter whith Cpp

- 三种滤波器的C++实现及比较
- 对于中值滤波采用全比较排序法
- 中值滤波法是一种非线性平滑技术，可以有效消除孤立噪声点
- 高斯滤波是一种线性平滑滤波，适用于消除高斯噪声。
- 对于均值滤波，作用有限，只是简单取均值，只能轻微地减弱噪声，有待进一步考量。

- 原图
![原图](filter/test.jpg)
- 3\*3 均值滤波
