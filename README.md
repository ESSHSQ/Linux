# Linux
准备

虚拟机及系统下载安装

VM下载安装:
https://www.vmware.com/cn.html
VMKEY:
如图1.
系统镜像下载：
http://www.linuxdown.net/ 
https://centos.org/   
https://msdn.itellyou.cn/
WIN系统KEY：
https://www.nruan.com/win-key.html

终端操作
CentOS8.2.2版Linux

一．关机
1.	现在关机：halt或init 0
2.	关机： shutdown -h now
二．备份系统
1．快照（频繁使用备份，开启时）。
2．克隆（长期存在，关闭时）。
三．Linux下一切皆文件。
四．目录结构
如图2 
Bin：binary,存储二进制可执行文件。
Dev：存储外接设备，Linux下无法自动分盘符，全存dev里，需挂载。
Mnt：给外接设备挂载的文件，系统可读取。
Etc：存储所有配置文件。
Home：除root用户以外的用户的目录的家目录（类似user）。
Proc：process，Linux运行的进程。
Root：root用户的家目录。
Sbin：super binary，存储仅超级管理员才可执行的二进制可执行文件。
Temp：系统运行时产生的临时文件。
Usr：用户自己安装的软件。
Var：程序或系统日志文件。

Linux指令

一．指令格式：
#指令+【对象】+【操作对象（默认当前）】
一个指令有一个指令主体（动作），可以多选项，可以多操作对象。
 二．基础指令
1．ls指令：list，列出当前工作目录下的所有文件和文件夹（相对路径，绝对路径）。  
ls -l列出，ls -la列出所有，含隐藏文件（多以”.”开头）,ls -lh列出文件并自动选择单位。还有ls -lah。
列出后第一列表示文件类型。“-”和“d”。
2．pwd指令：print working directory,打印当前工作目录。
3．cd指令：切换工作目录（“~”表示当前用户家目录）。
4．mkdir指令：make directory，创建目录，语法规则：mkdir+路径。
