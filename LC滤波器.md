# LC滤波器

**LC滤波器按所通过信号的频段分为以下三类**

**1.低通滤波器(LPF)**

低通滤波器是一种用于传递直流或者低频信号，衰减高频信号的滤波器。

作为被最广泛使用的滤波器电路，主要用于剔除高频噪声。

此外，音响中用于剔除低音用扬声器的高音/中音成分。

![image](https://github.com/user-attachments/assets/bca87b9e-4121-4bae-8870-7fa011c31850)
![image](https://github.com/user-attachments/assets/2e60f12e-d926-4835-94a9-4c567ee15f59)


**2.高通滤波器(HPF)**

高通滤波器是允许高于某一截频的频率通过，而大大衰减较低频率的一种滤波器。

这种滤波器被用于剔除听阈的低频噪声，或剔除高音用扬声器的中音/低音成分等

![image](https://github.com/user-attachments/assets/7540afe1-9359-49c9-ab25-82d2b9ed2451)
![image](https://github.com/user-attachments/assets/52f05599-6c57-4e86-b516-27db04b86036)


**3.带通滤波器(BPF)**

带通滤波器是用来只允许特定频率的信号通过，屏蔽其他频率信号的滤波器电路。

这种滤波器被用于收音机的选台(调整频率)、或剔除中音用扬声器的低音/高音成分等。

![image](https://github.com/user-attachments/assets/c2cb936f-fa55-4985-b427-01737db12f13)
![image](https://github.com/user-attachments/assets/e4660c79-210e-48f3-939c-5bc831370482)

## 应用

在设计供电时，常常使用lc滤波电路，例如：

![Screenshot from 2024-08-06 09-32-02](https://github.com/user-attachments/assets/1d7cb2ca-bd09-4d55-bbde-493405e0209f)

其中LC有以下作用：

**滤波作用：** 电感L2与电容C25、C22组成了一个LC滤波器，可以滤除电源线上的高频噪声，确保稳压器输入端的电压更加平滑稳定。这样可以提高LDO的输出稳定性和噪声性能。

**抑制电压尖峰：** 电感可以抑制电压尖峰和浪涌电流，保护后续电路，尤其是在电池供电的情况下，电源线路上的电压波动可能会比较大，电感能够起到缓冲和稳定的作用。


