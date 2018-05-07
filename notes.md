# 数据通信笔记

1. 数据通信模型
  ![数据通信模型](/image/数据通信模型.png)

2. 模拟通信模型
  ![模拟通信模型](/image/模拟通信模型.png)

3. 数字通信模型
  ![数字通信模型](/image/数字通信模型.png)

4. 数字通信的特点
  ![数字通信的特点](/image/数字通信的特点.png)

5. 网络体系结构
  ![网络层次结构](/image/网络层次结构.png)
  >重点关注TCP/IP的5层模型
  > 物理层：为设备之间的数据通信提供传输媒体及互连设备，为数据传输提供可靠的环境。
  >
  > 数据链路层：通常包括操作系统中的设备驱动程序和计算机中对应的网络接口卡。
  >
  > 网络层：处理分组在网络中的活动，例如分组的选路。
  >
  > 传输层：主要为了两台主机上的应用程序提供端到端的通信。
  >
  > 应用层：负责处理特定的应用程序细节。

6. 套接字socket（待完成）

7. 进程间通信PCIe（待完成）

8. 时域信号

   > 数字信号：离散的
   >
   > 模拟信号：平滑的，连续的

![时域信号](/image/时域信号.png)

9. 和差化积

  $$sin\alpha + sin\beta = 2sin\frac{\alpha+\beta}{2} cos\frac{\alpha-\beta}{2}$$

  $$sin\alpha - sin\beta = 2cos\frac{\alpha+\beta}{2} sin\frac{\alpha-\beta}{2}$$

  $$cos\alpha + cos\beta = 2cos\frac{\alpha+\beta}{2} cos\frac{\alpha-\beta}{2}$$

  $$cos\alpha - cos\beta = -2sin\frac{\alpha+\beta}{2 }sin\frac{\alpha-\beta}{2}$$

10. 积化和差

   $$sin\alpha cos\beta = \frac{1}{2} [sin(\alpha + \beta) + sin(\alpha - \beta)]$$

   $$cos\alpha sin\beta = \frac{1}{2} [sin(\alpha + \beta) - sin(\alpha - \beta)]$$

   $$cos\alpha cos\beta = \frac{1}{2} [cos(\alpha + \beta) + cos(\alpha - \beta)]$$

   $$sin\alpha sin\beta = -\frac{1}{2} [cos(\alpha + \beta) - cos(\alpha - \beta)]$$

11. 傅里叶（待完成）

12. 信号能量和功率