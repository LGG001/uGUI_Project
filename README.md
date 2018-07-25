# μGUI项目

μGUI是一个免费开源的嵌入式系统图形库，它与平台无关并且能轻松地移植到几乎所有的单片机系统。μGUI并不局限于某种显示技术，只要显示器有显示图像的功能即可使用，因此，像LCD、TFT、E-Paper、LED或OLED等都支持。整个μGUI由三个文件组成：**ugui.c**，**ugui.h**，**ugui_config.h**。


## 内容
- Documents：存放μGUI移植、使用等相关文档
- Driver：存放不同显示器的驱动程序
- Examples：μGUI相关的例程
- uGUI_Lib：官方的库源码

## 应用
μGUI的应用例程位于Examples文件夹下，通过复制Examples文件夹下相应的例程文件，然后在IDE（MDK、IAR FOR ARM或其他的编译器工具）上创建工程，编译，下载，即可看到效果。例程实现的平台有：
- OLED（SSD1351）
	- STM32F103
	- STM8L051
	- GD32F130G8
	- MM32F003
- TFT
- IPS




