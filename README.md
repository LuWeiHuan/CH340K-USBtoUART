# CH340K-USBtoUART
使用CH340K实现的USB转串口自动下载51代码，
新的51单片机供电范围很快，对输入的滤波电容47uF建议减小一点，否则不足以完成断电
DTR引脚用来控制PMOS
也可以用DTR和RTS引脚进行ESP模组下载程序ESP模组的EN引脚可能需要10K上拉
