# regs_tools

用于在用户态操作龙芯1C的寄存器， 应该不光局限于1C和龙芯，可以进行位设置， 位读取，字节设置， 字节读取，  
还有2个专门用于龙芯1C的复用寄存器的程序  
gpio_fun 对复用GPIO选择功能号  
cbus_dump 对复用寄存器，进行显示  
功能复用在线速查手册:https://mirrors.tuna.tsinghua.edu.cn/loongson/loongson1c_bsp/loongson1c_pins/  
速查手册源码:https://github.com/lshw/ic_pin  
龙芯1C用户手册:http://www.loongson.cn/uploadfile/cpu/1C/Loongson_1C300_user.pdf  
