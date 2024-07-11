# 基于51的智能家居
第七届郑州地方高校职业技能竞赛，2021 年 10 月 28 日

## 题目

家居开关自动蓝牙控制系统(G 题) 
一、任务 
智能家居系统包含了家用电器控制、窗帘自动控制、照
明自动控制以及防盗报警等多种便利的功能，运用蓝牙技术
与智能手机终端，设计了基于蓝牙的家居开关自动控制系
统，目的是通过使用网络信息和无线通信技术来实现对家居
开关的智能化远程控制，人们可以随时去控制像灯光、空调、
洗衣机、电视机等家用电器的开关的开启或关闭，还可以随
时通过手机查看家用电器当前的工作状态是什么，有没有忘
记关闭，不用再像以前那么麻烦，为生活提供了很大的便利。
二、要求 
1.了解家居开关自动控制系统的大致组成，根据系统设
计需求提出基于蓝牙的家居开关自动控制系统的设计方案。
2.按照设计方案，完成家居开关自动控制系统的整体硬
件电路，设计硬件电路的模块：单片机模块、蓝牙模块、继
电器模块，根据模块画出电路图，最后由各个模块图组成系
统总体的电路图并进行焊接。
3.系统的软件程序包括：初始化子程序、蓝牙控制子程
序、无线接收发送子程序等。
4.完成系统的硬件制作和软件调试。
三、说明 
1.系统的遥控主要是利用蓝牙模块，人们可以使用手机
查看家用电器的工作状态并可以随时的进行远程控制。
2.研究时要能够进行深入分析；充分表明自己的观点，
内容应具有一定的理论和现实意义及可行性





## 项目说明
![0](/images/1.jpg)

本个项目题目是智能家居，
其中按键模拟家庭的开关；
LED模仿的是家里的电器，如灯，冰箱，电视
舵机模仿的是家里面的电动窗帘



蓝牙功能是通过中断开启的，这样通过蓝牙串口APP发送信息来控制舵机和几个LED，
LCD12864上会实时显示温度湿度和当前的模式，
key1充当模式切换的按键；



普通模式（zhuangtai == 0）

key2控制led1；
key3控制led2；
key4控制led3；

智能模式（zhuangtai == 1）

当环境温度到达26度时，调动舵机转动，也就是开窗帘；
当环境温度到达24度时，调动舵机转动，也就是关窗帘；
由于比赛时，没有那么容易让环境温度变为26度或24度，所有用key3和key4分别模拟，
比如当按下key3，由程序让温湿传感器检测的温度在数值上短暂的变成24度；
当光敏传感器识别到环境光线变暗时，打开LED1，反之关闭LED1；


## 项目图片

![1](\images\2.jpg)

![2](\images\3.jpg)

![3](\images\4.jpg)

![4](\images\6.png)

