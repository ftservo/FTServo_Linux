# FTServo_Linux
FEETECH BUS Servo Linux library

# 静态库libSCServo.a生成
使用cmake .命令生成Makefile
使用make命令生成libSCServo.a静态库文件

# 测试
cd examples/SMS_STS/WritePos进入测试例子
使用cmake .命令生成Makefile
使用make命令生成运行程序WritePos
运行:sudo ./WritePos /dev/ttyUSB0
注:/dev/ttyUSB0根据设备实际串口指定
注:以上例子以SMS/STS舵机的WritePos为例，需要根据舵机型号选择合适的测试例子
