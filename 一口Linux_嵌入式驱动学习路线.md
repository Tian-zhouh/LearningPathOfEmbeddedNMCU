# 嵌入式驱动工程师学习路线【建议收藏】

原创 土豆居士 [一口Linux](javascript:void(0);) *2021-08-24 11:45*

收录于合集

[#Linux驱动53个](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUxMjEyNDgyNw==&action=getalbum&album_id=1502410824114569216&scene=173&from_msgid=2247496985&from_itemidx=1&count=3&nolastread=1#wechat_redirect)

[#所有原创197个](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUxMjEyNDgyNw==&action=getalbum&album_id=1479949091139813387&scene=173&from_msgid=2247496985&from_itemidx=1&count=3&nolastread=1#wechat_redirect)

网上看了很多的嵌入式学习路线，有的比较片面，有的为了博人眼球东拼西凑，几乎把整个行业用得着用不着的技术都写上去了，没有侧重点，简直是劝退指南，还有的纯粹是打广告卖板子招生。

一口君曾经是某见的教学总监，带过的学生也有大几千了，基本都从事linux相关开发工作。

现在在各行各业也基本都是翘楚，有的都成公司技术主管，带领几十人上百人团队。

一口君凭借多年的研发和开发经验，整理了嵌入式学习的最经典路线

下面就为大家介绍学习路线：

# 一、基础

## 1. linux基本操作：

需要掌握的知识如下：

1. 环境的搭建：ubuntu、vmware安装
2. Linux目录结构；
3. 文件类型；
4. 基本目录操作，文件操作，vim，ifconfig，ping，cd，cp，mv，mkdir等，最关键是gcc命令要会用；
5. 一些简单的shell脚本；
6. Makefile的编写。

个人建议只要会一些基本的操作就行了，不需要太深入的学习每一个命令，用到的时候会去搜索就行了。 

参考文章如下：

《[Linux入门的基础知识点汇总，有这篇就够了](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247494659&idx=1&sn=7c2eb2fe4a2036c6e7b3dbd7edfea39d&chksm=f96b9ef7ce1c17e1f5a3a1bc102576cd6c2c4e294f612090927967cf44894e393bcdd7d9db9e&scene=21#wechat_redirect)》 

《[linux驱动、ARM学习环境搭建](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247494342&idx=1&sn=d98150c45a1b68528006a0eb97c419fe&chksm=f96b9832ce1c1124fe1ffde0a79a3c36669d7a993184704edc54a220563b666e07d32c2e78e3&scene=21#wechat_redirect)》

《[Linux入门-shell编程-适合小白](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247494976&idx=1&sn=2770fbc15f6120d150170c7e555d4b06&chksm=f96b9fb4ce1c16a2e296272808618c79432a4d4dc0ba3b7e40c49d35f9c3c05c0e8eea111e25&scene=21#wechat_redirect)》

《[一键获取linux内存、cpu、磁盘IO等信息脚本编写，及其原理详解](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247492252&idx=1&sn=fa8609d11d28bbf750ed88f0a8651839&chksm=f96b9068ce1c197e2d06b7626f6557d74da319cde3c1b3061bda6dd8024bb3dd4173c9fcb880&scene=21#wechat_redirect)》

## 2. c语言：

**所谓编程不学C语言，便称码农也枉然。**

学Linux，**不学编程，建议就不要学了，否则职业后期全是瓶颈**。

那些和你说学Linux不需要懂编程的都是再耍流氓。

学习C语言一定要学习**Linux下C编程**，C语言网上视频也很多，知识点不一一介绍了。

但是有一点，就是一定要记住，一般的程序员从入门到绝对的精通大概需要2年时间，要想随心所欲写出超高质量的代码，时间因人而异，还要看个人造化。

实际上并不需要每个人都成为大师，能成为一个快快乐乐的小码农，不也是见开心的事吗？

## 3. 数据结构：

数据结构很重要，但是在这个上面花太多时间，也是没必要的。想进大厂的除外，自己拼命去刷题吧。对于嵌入式方向来说，个人建议只要掌握几个基本的排序和查找算法即可，没必要把所有算法都研究一遍。 

《[玩转内核链表list_head，如何管理不同类型节点的实现（万字文）可以收藏](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486501&idx=1&sn=dacf84b60342021af253f5f7090c4453&chksm=f9687ed1ce1ff7c7c31ac579295793abbc0341a857ba7e99573221b4423a4c79e4fb718380e0&scene=21#wechat_redirect)》 

《[十大经典排序算法(代码实现)，建议收藏](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247488738&idx=2&sn=c36028fbf93dc1129e27653424392772&chksm=f9686616ce1fef002f86ce9f79688bd665225a670ee8ca44afff56697f57d853c58db3c4528b&scene=21#wechat_redirect)》 

《[20张图揭开「队列」的迷雾](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247489187&idx=2&sn=869c6f75f15a003b42a79a904a713828&chksm=f9686457ce1fed41f66ccff99fb87d0ed2739efbb3e70d0bb7b229ac75e576dff2a8a9507637&scene=21#wechat_redirect)》 

《[二叉树详解，非常全，还包含C代码](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247490002&idx=2&sn=17958857452f76a8e6089cc20b09015e&chksm=f9686b26ce1fe230645e90dd1a9c26fac176d277618462627e7e947aa2beede9c09e5ba0cd46&scene=21#wechat_redirect)》

1. 能掌握常见的算法比如：冒泡排序、直接插入排序、快速排序、二叉树等。
2. 链表：双向链表，增删改查。

## 4. 基础阶段项目

基础阶段，个人强烈建议一定要做一个综合性项目，一定要从0开始写。

**建议项目**《电话本管理软件》

**该项目包含的知识点、功能点：**

1. 包含简单的菜单功能
2. 链表：包括增、删、改、查、排序等操作的双向链表。
3. 结构体、数组、指针、二级指针，字符串操作
4. 排序
5. 用户登录
6. 用户电话号码信息的添加、删除、修改

# 二、进阶

进阶阶段知识点很重要，学完这个阶段的内容，我们就可以用各种**库函数+系统调用**来自己实现Linux命令：ls、cd、stat、pwd、ifconfig，甚至自己实现一些网络协议：tftp、ftp、http。

即使以后不做linux c开发，有了这些基础，你再去学java、c++你的视野一定会不一样，Linux下系统编程是真正基于一个胸痛来编程的。

为什么我们要学Linux，就是因为他的开放性，有无数的大牛在给Linux添砖加瓦，所有代码都可以看到，而我们根本不用担心版权问题！

## 1. 文件IO

- 掌握Linux文件IO的一套系统调用API：open、read、write、lseek，close等。
- 熟练写出文件拷贝等功能模块。
- 理解I/O、缓冲的概念。

在Linux下，一切皆文件，我们操作操作许许多多的外设（字符设备、套接字、文件等等）就像操作文件一样。要想知道如何操作文件和外设，我们就必须熟练掌握文件IO，这是我们学习Linux下面编程最基本的知识点。

## 2. 进程线程

- 进程与线程的概念
- 掌握常用的函数fork、exec族函数等api；
- 进程创建、回收，一个.c源文件变成可执行程序的过程；
- 常用的进程相关命令：ps、top、crontab、at；
- 进程间通信：信号量、消息队列、共享内存、管道、信号；
- 守护进程；
- 线程创建、同步互斥，互斥锁；
- 库的概念，什么是动态库和静态库，如何自己制作动态库和静态库。

进程、线程是我们学习Linux下系统编程非常重要的一个知识点，必须掌握。

参考文章如下：

《[多线程详解，一篇文章彻底搞懂多线程中各个难点](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247495726&idx=1&sn=1261eb4c1edeabfb69c3e29aa62d031c&chksm=f96b82dace1c0bccca5bbb5f069db49640b08b31f559fb0f63f7285c289ae540d3afa03cb185&scene=21#wechat_redirect)》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect)Linux中常见同步和互斥机制设计原理 》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect)Linux信号量（1）-SYSTEM V》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect)Linux信号量（2）-POSIX 信号量》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect)Linux互斥锁（1）-线程互斥锁》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect)进程组、会话、控制终端关系，守护进程详解》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect) [一个多线程的简单例子让你看清线程调度的随机性](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247488785&idx=1&sn=de65652e983cc6a31c2a30d9e452018b&chksm=f96867e5ce1feef367340c1c5a2536e420bcf6f0488e1a93dca525926002e30010e6eb46b8ed&scene=21#wechat_redirect)[粉丝提问》](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247489336&idx=1&sn=fc645b7abc705275cf43eccc08ca0fcd&chksm=f96865ccce1fecdafd14bb4b025ec256ea986d414d20f3e81184cb89c5f7e1a29a402959a409&scene=21#wechat_redirect)

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect)Linux库概念，动态库和静态库的制作，如何移植第三方库》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect) 两个线程，两个互斥锁，怎么形成一个死循环？ [粉丝提问》](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247489336&idx=1&sn=fc645b7abc705275cf43eccc08ca0fcd&chksm=f96865ccce1fecdafd14bb4b025ec256ea986d414d20f3e81184cb89c5f7e1a29a402959a409&scene=21#wechat_redirect)

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect)用了这么多年Linux，你清楚控制台、终端与shell及它们的关系吗？》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect)多线程详解，一篇文章彻底搞懂多线程中各个难点》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486030&idx=1&sn=bbc0407c41c003891102bfb73c49a065&chksm=f96878bace1ff1acc53cade12abe5f15eb0c71d183612cb3a54e8085a73e3deae3236ad5a27d&scene=21#wechat_redirect)子进程进程的父进程关系》

## 3. 网络编程

- TCP/IP协议分层以及每一层的功能；不要看OSI，只要知道即可；
- socket api的使用，
- tcp、udp；C/S架构如何创建；
- 套接字属性的设置；
- C/S架构；
- 多进程、多线程网络服务器模型；
- 任意一款抓包工具使用；
- 常见的网络协议分析：ping、 tftp、 ftp、http、telnet 等。

网络的重要性不言而喻，应用实在太广了，网络的知识也非常的复杂：网络编程、TCP/IP协议栈、网络拓扑、网卡驱动、各种无线通信协议。

可以收每一大块知识的学习，都需要很长一段时间来入门，并需要一定难度的项目做支撑，才能真正了解和掌握网络。对于嵌入式方向初学者，我们最好先了解一些基础的网络协议知识，然后学习套接字的使用。

参考文章如下：

[《22张图详解浏览器请求数据包如何到达web服务器（搞懂网络可以毕业了）》](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247486752&idx=1&sn=0b6ef838024fc0c6584fb66750d6768e&chksm=f9687fd4ce1ff6c2d44e82f0cf8413d15dc9bf68cee1217a5f8f8ab2f15597e595c30149bd63&scene=21#wechat_redirect)

[《一个端口号可以同时被两个进程绑定吗？](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247489150&idx=1&sn=ac026bd40d7195ce883287d02560bd20&chksm=f968648ace1fed9c73a3a9964b996b910aa532279a7c4955c046e433eb7bff76a3d38cfc913f&scene=21#wechat_redirect) 》

[《【粉丝问答7】局域网内终端是如何访问外网？答案在最后 》](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247490400&idx=1&sn=4e79b0745016b97e128795d1f4e443b8&chksm=f9686994ce1fe082991740bf0d154695ca8009d93cb1f72b57e8e20819c68f2f0da6303c0a75&scene=21#wechat_redirect)

[《一文包你学会网络数据抓包 》](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247490595&idx=1&sn=11fb56cb4d18da0c3da5cad1cded52b5&chksm=f9686ed7ce1fe7c1de117abf6d3b09ba85b76da3855b5676b65b9f2fd14de807607a1dabf3a2&scene=21#wechat_redirect)

《【视频】[教你如何抓取网络中的数据包！黑客必备技能》](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247491157&idx=1&sn=7c78bb12094fa7415e6fdc56b7cadb77&chksm=f9686ca1ce1fe5b784d65de153901a317e6b97c3043f88e74a2f2e5186d42520207da3e3f4f0&scene=21#wechat_redirect)

[《网络/命令行抓包工具tcpdump详解](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247490920&idx=1&sn=69be9e2dcde1bca58f37fb6f01947d81&chksm=f9686f9cce1fe68a0d195701b5fc8ba0c5044ec12aed77141a8d363cb9a5f1af053609ece52b&scene=21#wechat_redirect)[ 》](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247490595&idx=1&sn=11fb56cb4d18da0c3da5cad1cded52b5&chksm=f9686ed7ce1fe7c1de117abf6d3b09ba85b76da3855b5676b65b9f2fd14de807607a1dabf3a2&scene=21#wechat_redirect)

[《【粉丝问答11】如何在内网搭建TCP服务器并能被外网直接访问》](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247491866&idx=1&sn=0b0581c71a331ae698d788e474ef5906&chksm=f96b93eece1c1af840416ce75cf807878ddbeb628910dc106cd8652ff9fae736d23cb7f2f06e&scene=21#wechat_redirect)

## 4. 进阶项目

该阶段可以选择综合项目《多线程聊天室》，实现公聊、私聊、注册登录，互相发送文件等功能。

一口君已经把这个项目拆解成4篇文章，并提供源码，方便大家入门。

《[从0实现基于Linux socket聊天室](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247487625&idx=1&sn=dc9ac657a9440abade9110d1c0fd92c0&chksm=f968627dce1feb6b03b07f3fbb427f1b3b962f88064f1d04bdcd382b5a9677340a3089d9bb23&scene=21#wechat_redirect)》

# 三、高阶

该阶段学习需要开发板配合，建议新手先把之前内容打扎实，再进入这个阶段学习。

开发板的选择，最重要的是资料！资料！资料！资料！资料！资料！资料！资料！

资料不全的板子不要买！

## 1. ARM

- arm架构、arm的模式、arm指令，寻址，异常，中断，异常向量表，
- 伪指令、C语言和汇编代码的互相调用、内联汇编；
- 学会查看常见电路图，了解数据线、信号线、地址线、中断线，常见外设电路图
- 学会查看各种芯片的用户手册
- *常见的外设的裸机驱动开发，led、key、adc、pwm、rtc、看门狗、i2c、spi、网卡、flash、USB等

这个阶段的内容，对于了解整个计算机软件的工作原理非常重要，Linux内核的很多机制都要依赖汇编指令，尤其ARM工作模式、寻址、异常，中断，异常向量表这些概念。可以说，掌握了这个阶段的内容，那么单片机、STM32真的就是手到擒来了！

大家也可以参考我写的《[ARM系列文章](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUxMjEyNDgyNw==&action=getalbum&album_id=1614665559315382276#wechat_redirect)》

B站正在更新这个系列的视频教程，

纯奶妈式教学，只要有C基础，绝对学得会！

**https://space.bilibili.com/661326452**

## 2. 系统移植

- uboot移植、uboot参数设置
- rootfs制作、内核剪裁移植，
- usb、网卡驱动移植，
- uboot、linux启动流程，
- 自己添加uboot命令

这一阶段的内容对于嵌入式工程师来说，在做实际项目的时候，会经常用到，各个厂家的移植步骤会有所差异，但原理基本相同，熟练掌握这些操作，非常必要。

这部分内容其实很复杂，对于新手来说，建议会操作即可，工作后如果在深入研究，再回头研究这些细节。

参考文章

[《【问答23】移植Linux：如何制作rootfs？详细教程](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247493795&idx=1&sn=67b66204b892c1d8b8bd542ab2bc461a&chksm=f96b9a57ce1c1341ebe8bcfca5c2f50e3fb2b4f43d0d7d621a00393be297a7ac463b7163ee60&scene=21#wechat_redirect)》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247493795&idx=1&sn=67b66204b892c1d8b8bd542ab2bc461a&chksm=f96b9a57ce1c1341ebe8bcfca5c2f50e3fb2b4f43d0d7d621a00393be297a7ac463b7163ee60&scene=21#wechat_redirect)19. Cortex-A9 uboot启动代码详解[**必看》**](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247488626&idx=1&sn=c9c045382502de4417a48cf63fffc691&chksm=f9686686ce1fef90b096ddbf70129785b8e0b9666a3367e706364543ea81d728b61323747e2f&scene=21#wechat_redirect)

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247493795&idx=1&sn=67b66204b892c1d8b8bd542ab2bc461a&chksm=f96b9a57ce1c1341ebe8bcfca5c2f50e3fb2b4f43d0d7d621a00393be297a7ac463b7163ee60&scene=21#wechat_redirect)20.从0学ARM-从0移植uboot支持exynos4412-亲测》

[《](http://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247493795&idx=1&sn=67b66204b892c1d8b8bd542ab2bc461a&chksm=f96b9a57ce1c1341ebe8bcfca5c2f50e3fb2b4f43d0d7d621a00393be297a7ac463b7163ee60&scene=21#wechat_redirect)Linux模块文件如何编译到内核和独立编译成模块？》

## 3. Linux驱动

- 字符设备架构、inode、cdev、file_operations、file之间关系；
- platform总线、设备树；
- 内存管理；
- 同步互斥机制，自旋锁、信号量、互斥体，原子操作；
- Linux进程管理
- 块设备
- 中断、中断底半部；
- 等待队列，poll的实现；
- 常见设备的驱动的编写和代码分析；
- 网络设备：网卡驱动分析、netfilter使用、网络协议栈架构；
- USB、TTY、SPI、IIC、PCIE等架构。

能够学到这个阶段，那么恭喜你，你可以称为一名真正合格的嵌入式工程师了。

Linux驱动我们学习Linux内核最好的一个入口， 在这庞大、浩瀚、错综复杂的内核代码中找到一个突破口， 从而真正走向大神之路！

驱动的学习，主要在于多捋架构，多阅读大牛的代码！

**代码读百遍，其义自见！**

**代码中自由颜如玉，代码中自由黄金屋！**

**每天抱着内核看，像泡女人一样泡她，迟早你会成为大师。**

驱动文章可以参考我写的**《[驱动集合](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUxMjEyNDgyNw==&action=getalbum&album_id=1502410824114569216#wechat_redirect)》**

也可以进入我的B站，一口君已经更新了《从0学Linux驱动第一期》

https://space.bilibili.com/661326452

# 四、终极

我想如果能学到这个份上，后面如何发展，已经不需要一口君再多费唇舌了，可以继续学习**安卓、QT，也可以深挖物联网、算法，AI、VR、大数据或者钻研Linux内核优化内核**等，每个领域独当一面，收入都不会低。

也衷心祝愿各位还能坚持到这个阶段的，头发依然保持茂密！

最后给大家一个建议，学习编程没有任何捷径可以走，需要花费几年的时间才能有所成，所以我们要提早做**好规划，找好大方向，制定好短期、长期的计划，然后按照计划，一点点的实施**。