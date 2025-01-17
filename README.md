### Hi there <a href="https://www.gautamkrishnar.com/"><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="5%"></a>
欢迎来到我的主页，这里有我的项目和学习笔记 :rofl:

- 🔭 &nbsp;我叫甘罗宇，英文名叫Oliver，1999年出生，来自中国长沙 :smile:
- 🌱 &nbsp;我目前在拓维信息系统股份有限公司工作 :wink:
- 💬 &nbsp;欢迎与我探讨升级能力子系统的构建以及数字信号算法处理
- 👨‍💻 &nbsp;如果想要了解我的项目，可以参观我的仓库，[[github](https://github.com/luoyugan), [gitee](https://gitee.com/gan-luoyu), [gitea](https://gitea.openvalley.net/LuoyuGan)]
- ⚡ &nbsp;爱好: 我 :heart: 运动和FPS游戏(Vlorant)

📕 &nbsp;**最近的一些博客和论文**
<!-- BLOG-POST-LIST:START -->
- [Heart rate variability analysis method for exercise-induced fatigue monitoring](https://www.sciencedirect.com/science/article/abs/pii/S1746809424000247)
- [OTA AB差分升级示例](https://blog.csdn.net/weixin_62941746/article/details/144419107?spm=1001.2014.3001.5502)
- [OpenHarmony HDF传感器驱动开发](https://blog.csdn.net/weixin_62941746/article/details/143566898?spm=1001.2014.3001.5502)
- [蓝牙连接及安全基础](https://blog.csdn.net/weixin_62941746/article/details/131833542?spm=1001.2014.3001.5502)
- [鸿蒙驱动开发-解决iphone手机热点重启后，设备未自动连接热点](https://blog.csdn.net/weixin_62941746/article/details/140991425?spm=1001.2014.3001.5502)
<!-- BLOG-POST-LIST:END -->

🔗 &nbsp;**联系我**

邮箱：gly19990820@163.com

电话：18816233398

CSDN：[橄榄油加油](https://blog.csdn.net/weixin_62941746?type=blog)

知乎：[橄榄油加油](https://www.zhihu.com/people/gan-luo-yu-93)

### ✨&nbsp; 关于我

我是一名嵌入式软件工程师，目前投身于开源鸿蒙的驱动开发。对算法、人工智能、物联网有一定的了解。


#### 我的经历
以下记录了我的工作经历与学习经历。

##### 工作经历：
- 2024年7月-至今，在[拓维信息系统股份有限公司](https://www.talkweb.com.cn/)从事嵌入式软件开发工程师，主要工作为驱动的适配与开发。

  参与项目：

  1.内核OTA流式升级能力开发，在RK3568 DAYU200上以OpenHarmony为基础实现的OTA流式升级，负责的内容包括：OTA流式升级包的制作以及异常回滚功能。OTA流式升级包的制作：增加流式控制；AB分区增加copy命令；AB分区解耦stash、free命令；diff反向切片；new切片；全量包切片；单分区无文件系统切片；update.bin包的封装。异常回滚：开机激活的AB分区异常回滚；data分区数据回滚。

  2.基于HDF的传感器驱动开发，在RK3568 Rockpi基于OpenHarmony的HDF框架，适配了温湿度传感器SHT30、数码管TM1637、10轴传感器JY901B、光感传感器VEML7700、gpsATGM336。

  3.控制器功能实现，水浸传感器数据传到在鸿控制器，然后数据到在鸿云，在鸿云平台显示在线，RSU连接5G路由器后上云，在鸿云平台显示在线，在鸿云平台控制器与RSU场景联动，有/无浸水能触发在鸿云通过mqtt下发指令到RSU。

- 2023年5月-2023年12月，在[九号公司](https://www.ninebot.com/)从事嵌入式软件开发工程师，主要从事蓝牙协议栈的开发。
  
  参与项目：

  1.感应接近解锁：在移远的模组ec200n的协议栈上进行应用开发，添加了RSSI距离解锁功能，编写了一套以卡尔曼为主的滤波算法，满足了低延迟稳定的特性，并成功加⼊到感应解锁3.0中，实现了不用nfc卡靠近车辆，按auto键或者坐上坐垫就能立即解锁。同时增加了AT指令，对卡尔曼滤波进行调参。

  2.Find My Network移植：将IOS的Find My Network移植到蓝牙开源协议栈BTstack恒玄芯片上，实现BLE ATT/GATT的应用开发，主要实现框架编译；协议栈平台初始化相关配置；adv模块移植适配；连接模块移植适配；gatt模块移植适配；安全加密模块适配；整体功能调试适配。

  3.NBOS蓝牙导航传输：在NBOS仪表项目上，进行导航传输的BLE数传服务开发（包括加密的GATT服务和不加密的数据传输服务），通信加密协议移植，以及蓝牙连接稳定性测试、丢包率、延迟、速率测试，对出现的断连不稳定、速率、广播数据等BUG进行修复，以及参数mtu、连接间隔等参数调优。配合APP组完成200N/800N模组上蓝牙连接速率测试。

##### 学校经历:
- 2024年6月硕士毕业于[北京体育大学（211）体育工程学院](https://sse.bsu.edu.cn/index.htm)电子信息工程专业 - 主要研究智能硬件的开发，生物电信号处理及应用等方面。

  其中以核心研发人员参与的项目：

  1.冰雪头盔的视域和认知功能测试技术与设备研发（国家科技冬奥课题）

  2.非线性递增负荷强度心率变异性系统研究（国家主动课题）

  3.分段计时训练系统研发

[⏩ &nbsp; 了解更多](https://github.com/luoyugan?tab=repositories) 


#### 奖项和成就
- 发表了一篇SCI中科院二区算法类的论文：[Heart rate variability analysis method for exercise-induced fatigue monitoring](https://www.sciencedirect.com/science/article/abs/pii/S1746809424000247)
- 三项国家发明专利
- 第二届全国体育科技创新大赛优秀产品奖
- 第八届中国“互联网+”北京赛区二等奖
  
<details>
  <summary><b>🛠️&nbsp;&nbsp;语言&nbsp;和&nbsp;工具</b></summary>
  <br/>
  <p align="left"> <a href="https://www.cprogramming.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> </p>

</details>

<img alt='analytics' src='https://profile-counter.glitch.me/gautamkrishnar/count.svg' width='0px'>
