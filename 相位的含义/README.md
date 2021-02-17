相位是很重要的特征，但是第一次试验采到的数据让我有两点疑惑。

![标签固定，在不同频率下的相位](https://github.com/Jennifer331/-RFID-/blob/main/image/phase_at_different_freq.png)
- 斜率为什么是负的？
- 斜率为什么比 <img src="https://latex.codecogs.com/gif.latex?\inline&space;\phi&space;=&space;(2d2\pi/\lambda)&space;\mod&space;2\pi">  计算出来的理论值大？

为了增进对相位和信号强度的了解，做了标签与天线距离不同距离的实验，采集的数据在[RFID_Experiment_Data](https://github.com/Jennifer331/RFID_Experiment_Data/tree/main/20210202/distance)这个仓库中。

分别按固定位置频率变化和固定频率位置变化可视化地画在[grouped_by_dist)scatter.pdf](https://github.com/Jennifer331/-RFID-/blob/main/%E7%9B%B8%E4%BD%8D%E7%9A%84%E5%90%AB%E4%B9%89/grouped_by_dist_scatter.pdf)和[grouped_by_freq_scatter](https://github.com/Jennifer331/-RFID-/blob/main/%E7%9B%B8%E4%BD%8D%E7%9A%84%E5%90%AB%E4%B9%89/grouped_by_freq_scatter.pdf)中

经过实验和讨论，对上述问题的认识为：
- 相位变化的正负不重要，重要的是相对变化
- 相位读数不仅由距离决定，还受到标签和天线的影响。（这也验证了Wang, G., et al. (2020). A Universal Method to Combat Multipaths for RFID Sensing. IEEE INFOCOM 2020中提到的这三项影响都是线性的）
