# Gesture-Recognition

## 前言
Simple gesture recognition on Windows & Linux

基于 OpenCV 的简单手势识别

可适用于 Windows10 的 HID Simulation 和 Rasberry 4b 的 Gpoint HID

后续可能会上卷积网络训练（咕咕咕...

## 更新日志

### 2022.10.17

更新了手部识别代码 (FingerDetect文件夹)，可以进行手部手指数目的识别，并返回手指数目

在强光环境和复杂场景返回值会有 ±1 左右的上下浮动，后续设计需要有返回数目的容错

该部分代码完全基于OpenCV-Py，没有使用Pytorch ( 咕咕..)

测试摄像头为电脑前置摄像头 (G15-5510)，和通过Ikrun Webcam连接到手机 (OPPO FIND X3)的前后摄像头

参数目前基于测试摄像头，后期购买完摄像头后进行二次调参


