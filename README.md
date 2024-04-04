# XPC-OS XYLCS工作室专业型软件系列之一
###### 语言：Rust
#####
## 系统运行由XPC内核支持
##### XPC OS CONTROL(XOSC)由XPC、Read、Output、Pack（Mod、Ware）、Control、Datapack组成，他们为Programs（.xpcprog）提供支撑运行服务，其中最关键的是XPC，XPC读取Programs发送给XOSC的指令做出决定并给Programs发送控制流以运行这个指令，XPC中默认提供XPC语言包，使得程序运行得到良好的支撑，并给使用该系统进行开发的开发人员提供良好的开发环境
###### 哪个开发人员能抗拒一个内置编程语言的开发环境呢？
##### XPC语言仓库地址：github.com/xylcsstudio-github/XPC
#####
## TAFS文件系统
##### TAFS（Three Aeras File System）由三个区构成 分别为：
##### 系统区：储存系统配置以及系统核心文件，还有系统资源
##### 文件区：储存日常文件与软件
##### 快速区：储存桌面文件以及软件缓存，也是临时内存的存储地方
#####
## 多线程运行
##### 在这里有一种概念叫做运行区线（也称线程），每一个运行区可以运行一个任务，当一个Programs需要多线程运行，就会向运行区线发送访问请求，然后使用多个运行区线运行任务，类似于Linux的后台，但是多后台，且可以随意切换到任意一个运行区线的系统环境中
#####
## 完备权限
##### 系统还有一个概念叫做persm，就是权限的意思，有个类似于Linux的root的权限：control，这个权限能控制整个系统的调用，XPCOS控制程序（xpcos.program）拥有这个权限，也有其他类型的权限，这里不多做叙述
#####
## 联系我们
##### Email：xylcsstudio@outlookcom
##### QQ：822415187
#####
## 加入我们的开发团队
##### QQ群：347710586
