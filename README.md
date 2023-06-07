# DFRobotCar 硬件工程


## 固件
* 小车固件基于ESP32单片机 [Node32s开发板](https://docs.platformio.org/en/latest/boards/espressif32/node32s.html)搭建，使用[Arduino IDE（2.1.0）](arduino.cc) 开发；
* 固件功能：①两路直流电机的驱动控制； ②串口通信指令封装。

## Python API
* 基于通信协议编写的小车运动控制Python库；
* 实现左轮侧轮子的运动速度控制，速度控制范围[-100,100] (正负表示正反转，单位为%)。
