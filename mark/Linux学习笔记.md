# Linux学习

## 一 Libux概述

### 1-1 Linux 是什么

- Linux是一个操作系统(OS)

### 1-2 GNU/Linux

GPL 表示当前源码是公开的

如果用到了GPL协议的也需要开源

保障了用户的自由

BSD 保障了软件开发者/公司的自由

![img_2.png](img_2.png)

### 1-3 Linux发行版

![img_3.png](img_3.png)

### 1-4 Linux VS Windows

![img_4.png](img_4.png)

### 下载安装 

[清华大学源](https://mirrors.tuna.tsinghua.edu.cn/centos/7.9.2009/isos/x86_64/)


### 使用 shell 控制台

- ctrl + f2 到 f6 shell控制台 

- ctrl + alt 召唤鼠标

- ctrl + f1 回到图形化界面


## 三 文件系统和挂载点

### 3-1 Linux文件

Linux系统中一切皆文件

### 3-2 Linux目录结构

![img_5.png](img_5.png)


- /bin
  - 是Binary(二进制,输入类型命令)的缩写,这个目录存放着最经常使用的命令
- /sbin
  - s是system的意思,这里存放的是系统管理员使用的系统管理程序
- /lib
  - 系统和应用程序的共享库文件,类似于dll
- /lib64
  - 64位共享库文件
- /usr  (Unix Software Resource)
  - 包含了用户的所有的应用程序和数据, 类似于system32
- /boot 挂载分区时候的目录
- /dev 
  - 设备文件目录
- /etc 
  - 系统配置文件
- /home 
  - 主目录,个性化数据文件存放位置,普通用户的文件夹,没有root用户
- /root 
  - root用户的文件目录
- /opt (optional可选目录)
  - 额外软件约定俗成放到这里
- /media
  - 媒体目录,可以识别一些可移动媒体设备
- /mnt 
  - 挂载目录 根media类似 
- /proc
  - 进程目录
- /run
  - 运行目录,存放的是所有系统运行的实时信息,重启后内文件就会消失
- /srv
  - 系统服务
- /sys
  - 系统内部硬件相关信息
- /tmp (temporary 临时的)
  - 临时目录
- /var
  - 可变目录,存放经常被修改的东西,比如日志

## 四 VI/VIM编辑器

### 4-1 vi/vim 是什么
 
VI是Unix操作系统和类Unix操作系统中最通用的文本编辑器
VIM编辑器是从VI法阵出来的一个性能强大的文本编辑器,可以主动的一字体的颜色辨别语法的正确性,方便程序设计,VIM与VI编辑器完全兼容

### 4-2 测试数据准备

(1) 拷贝/etc/profile 数据到/root目录下
  cp /etc/profile/root
    cd /root/

### 4-3 一般模式

以vi打开一个档案就直接进入一般模式了(这是默认的模式) 在这个模式中,你可以使用[上下左右] 按键来移动光标,你可以使用
[删除字符]或[删除整行]来处理档案内容,也可以使用[复制,粘贴]来处理你的文件数据


### 4-4 模式间转换
![img_6.png](img_6.png)



