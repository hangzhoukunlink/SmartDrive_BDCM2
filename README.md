# SmartDrive_BDCM2
智驱-双路直流有刷电机版本（SmartDrive - Brushed DC Motor Two way）

> 该驱动器由 YLT 制作，并开源，遵循GPL协议，仅可用于非商业用途，商用请联系773673787@qq.com

**"智驱"** 的双路直流有刷电机版本，该版本可以同时驱动两个直流有刷电机。

BDCM2 带有**位置环**、**速度环**、**电流环**，具有过流报警、自动保护的功能。

该版本可以提供单路 **最高36V、持续10A** 的大电流输出。

**兼容两种通信方式**

- 分别是 <u>STEP/DIR</u> ，兼容一般的步进电机，私服系统。

- <u>USART</u>（串口），使用115200通信速率，遵循私有协议，可发送位置、速度指令进行控制。连接上位机可进行PID调参、实时监控电流、速度、位置信息。


![SmartDrive_BDCM2_Front](../SmartDrive/img/SmartDrive_BDCM2_Front.png)

![SmartDrive_BDCM2_Back](../SmartDrive/img/SmartDrive_BDCM2_Back.png)

![SmartDrive_BDCM2_left](../SmartDrive/img/SmartDrive_BDCM2_left.png)

![SmartDrive_BDCM2_right](../SmartDrive/img/SmartDrive_BDCM2_right.png)