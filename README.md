![Markdown](http://i2.kiimg.com/597728/53f2811082aa1e2a.jpg)
![Markdown](http://i2.kiimg.com/597728/e47c02be05adc929.jpg)
# 分控板 V2.1

修正：

1117-3.3的1管脚在原理图上未连接到地

继电器的三个初始上拉电阻未接地

5V 3.3V 继电器 LED指示灯未连接


# 分控板 V2.0

更新：

集成24V转接板

增加三路码盘接口

修改继电器为AO3400 持续电流5.7A 峰值电流 30A

尝试用缓冲器74ls07代替非隔离场合的光耦 

# 分控板
- 通信接口：
	- CAN
	- UART（调试用）
- Core:
	- [F103Core](https://github.com/BUPTRobocon/STM32F103)
- 特性：
	- 3路码盘接口
	- 3路电机驱动接口（24V CAN）
	- 4路舵机/电调接口
	- 3路继电器接口
	

2017.4.10

