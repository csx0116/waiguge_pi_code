# waiguge_pi_code
从零开始的祖传代码——一键部署的伟大尝试，电控代码框架的开山鼻祖
这里是丁sir的外骨骼电控代码，包含：电机5015，直线编码器，树莓派环境，争取让所有外骨骼样机实现一键部署

如果你使用的是2-ch can hat+ 那么请使用img镜像里的2can pi.img
如果你使用rs485 can hat(B),那么请使用can-485 pi.img

使用win32 diskimager,写入镜像文件

注意：如果不能找到设备，则部分功能需要手动开启。
1.先使用（ls /dev/tty*）指令查找
2.如果缺少 （/dev/ttyAMA*）则把
