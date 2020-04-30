# EFI-Acer-T5000

## 机器型号以及配置

- 机器型号：Acer T5000-707D 
- 配置参考：http://detail.zol.com.cn/1136/1135969/param.shtml
- CUP : I7 6700HQ
- 内存：两条8G，频率：2133，DDR4
- 硬盘：256固态(M.2接口, NVMe协议，型号： NVMeSamsung SSD 970 EVO Plus 250GB) + 120G固态（M.2接口 ，Sata协议，型号： HP S700 120GB ）
- 显卡：
	核显： Intel HD 530
	独显： NVIDIA GeForce GTX 950M（DDR3，2G）
- 有线网卡：Realtek RTL8168H/8111H PCI Express Gigabit Ethernet：
- 声卡： Realtek ALC256

## 安装Mac系统
	安装系统： Catalina 10.15.2 

## 那些硬件能正常工作
	1、有线网卡
	2、蓝牙
	3、声卡
		增大音量快捷键： fn + 上方向键
		减少音量快捷点： fn + 下方向键
	4、有线网卡
	5、核显（能够使用hdmi接口连接外接显示器；单独使用VGA接口不可以。但是使用hdmi接口转VGA可以正常输出）
	6、键盘正常使用（注意：这里键盘的按键可能和一些其他EFI不一致，特此说明）
		alt ==> 相当于mac中的mac键
		windows键 ===> 相当于mac中option键
	7、触摸板（支持简单的点击、滑动、双击、右键等操作）
	8、调节亮度
		减少亮度： fn + F12
		增加亮度： fn + Pause Break	

## 那些不能够正常工作
	1、无线网卡 （我是在淘宝买了USB无线网卡）
	2、独立显卡（苹果目前不支持N卡，所以这个无法解决）

## 还有一些不足之处
	1、机型目前设置的是MacBookPro13,1 , 但是我这个配置明显设置MacBookPro13,3更为合适，
		但是设置成MacBookPro13,3以后，外接显示器就不能正常工作。

