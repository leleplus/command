# Windows 命令行终端Cmder

------
author : witt

`Cmder`是一个可以在Windows平台下使用Unix命令行的软件，[Cmder官方网站](https://cmder.net/)，本版本为我个人配置版，跟随官方进度，持续更新中...

## 下载Cmder
使用git-for-windows
通过SSH
`$ git clone git@github.com:leleplus/command.git`
或者HTTPS
`$ git clone https://github.com/leleplus/command.git`

## 设置环境变量
1.通过`Windows徽标键`+`R`打开运行(或者鼠标右键点击开始菜单，选择`运行`)，输入`sysdm.cpl`,回车键打开对话框，依次选择`高级`->`环境变量`->找到系统变量，新建如下的环境变量
```bash
变量名:CMDER_HOME
变量值:Cmder的家目录，可以看到Cmder.exe的目录
```
2.编辑`Path`变量，新增如下的环境变量
```bash
%CMDER_HOME%
%CMDER_HOME%\bin
%CMDER_HOME%r\vendor\bin
%CMDER_HOME%\vendor\git-for-windows\bin
```
> 一般只需添加前两个


## 安装字体
本版本基于我个人配置使用，需要安装字体`Monaco.ttf`.

## 注册
通过`Windows徽标键`+`R`打开运行，输入`cmder`，即可打开，接着输入`Cmder.exe /REGISTER ALL`,即可生成右键菜单

## 使用
通过运行输入`cmder`或者右键`cmder here`即可打开

