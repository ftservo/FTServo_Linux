# FTServo_Linux
FEETECH BUS Servo Linux library

# Static library libSCServo.a
- cd src
- cmake .
- make

# TEST
- cd examples/SMS_STS/WritePos
- cmake .
- make
- sudo ./WritePos /dev/ttyUSB0
- /dev/ttyUSB0根据设备实际串口指定
- 以上例子以SMS/STS舵机的WritePos为例，需要根据舵机型号选择合适的测试例子
