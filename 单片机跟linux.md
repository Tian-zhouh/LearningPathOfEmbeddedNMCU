说实话，问题中**嵌入式开发**这个话题有点庞大，毕竟它涵盖的领域和范围很宽泛。作为一个在[嵌入式软件](https://www.zhihu.com/search?q=%E5%B5%8C%E5%85%A5%E5%BC%8F%E8%BD%AF%E4%BB%B6&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A1782550929%7D)开发方面工作了十多年的老程序猿，这么多年过来也在通过不停的自学和各类项目的历练中，不断积累自己的嵌入式软件开发的技能栈。这里也借题主的问题宝地，梳理一下嵌入式软件开发方向的技能栈，以期对题主和广大嵌入式软件爱好者有所帮助。毕竟是站在个人的经历角度分享，如有缺失敬请谅解。

作为嵌入式软件开发，在答主前面很多次的回答中都有提到，这个**软件开发**其实可以细分为：

1. 嵌入式MCU软件开发工程师；
2. 嵌入式Linux底层（BSP）软件开发工程师；
3. 嵌入式Linux应用开发工程师；
4. 嵌入式FPGA算法开发工程师

答主这么多年，从MCU开发及Linux应用开发起步，在合伙创业过程中自学并通过项目实践构建了Linux底层驱动技能栈，FPGA算法工程师仅仅因为与公司的相应同事有过交际集，这里就不过多阐述FPGA算法工程师的技能栈，防止给大家带跑偏了。

## **1，嵌入式MCU软件开发工程师**

- 【基本武器】：
- （1）C语言编码能力（[数据结构](https://www.zhihu.com/search?q=%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A1782550929%7D)，常用算法，指针和数组，结构体和位域等）
- （2）MCU的理论知识（[时钟树](https://www.zhihu.com/search?q=%E6%97%B6%E9%92%9F%E6%A0%91&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A1782550929%7D)，内存，中断，GPIO，功能外设（uart，iic，dma等）等）
- （3）MCU的编码方式（寄存器/[库函数](https://www.zhihu.com/search?q=%E5%BA%93%E5%87%BD%E6%95%B0&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A1782550929%7D)），编译下载过程（根据题主选择的MCU来学习）
- （4）基本的电路连线图能看懂（MCU的管脚如何连接到外界器件等）
- （5）实时操作系统编码能力（ucos，[freertos](https://www.zhihu.com/search?q=freertos&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A1782550929%7D)，liteos等等）
- （6）业务场景知识（根据题主嵌入式产品场景而定）
- 【升级武器】：
- （1）软件架构设计能力
- （2）示波器，[逻辑分析仪](https://www.zhihu.com/search?q=%E9%80%BB%E8%BE%91%E5%88%86%E6%9E%90%E4%BB%AA&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A1782550929%7D)使用（调试通信器件使用）
- （3）读取反汇编能力（定位Bug时候可能用到）
- （4）掌握通信协议（串口232通信，485通信，iic协议，[spi协议](https://www.zhihu.com/search?q=spi%E5%8D%8F%E8%AE%AE&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A1782550929%7D)，tcp/ip，can协议等等）

## **2，嵌入式Linux应用开发工程师**

- 【基本武器】：
- Linux C语言编码能力（数据结构，常用算法，指针和数组，结构体和位域等）
- Linux常用功能API（多线程，多进程，锁类，进程/线程通信机制相关等）
- Linux Shell使用（基本的Linux操作能力）
- Makefile/GDB调试
- 掌握通信协议（串口232通信，485通信，iic协议，spi协议，tcp/ip，can协议等等）
- 业务场景知识（根据题主嵌入式产品场景而定）（比如视频，那么rtsp，h264编码，视频基础）
- 【升级武器】：
- （1）软件架构设计能力
- （2）读取反汇编能力（定位Bug时候可能用到）
- （3）Linxu操作系统理解（[用户态](https://www.zhihu.com/search?q=%E7%94%A8%E6%88%B7%E6%80%81&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A1782550929%7D)，内核态，中断机制，内存机制等）

## **3，嵌入式Linux底层（BSP）开发工程师**

- 【基本武器**】**：
- Linux C语言编码能力（数据结构，常用算法，指针和数组，结构体和位域等）
- Linux裁剪，移植，编译
- Linxu操作系统理解（用户态，内核态，中断机制，内存机制等）
- Linux Shell使用（Linux操作能力）
- bootloader（uboot等）修改
- 基本调试用通信方法（uart，tcp/ip）
- 【升级武器】：
- Linux驱动开发能力
- Linux内核机制
- 等等

以上根据个人的工作经历中使用的技能栈总结，难免存在遗漏。毕竟每个嵌入式工程师从事的行业不同，技能栈也会有所不同。以上建议，也仅供题主和广大嵌入式软件爱好者参考。