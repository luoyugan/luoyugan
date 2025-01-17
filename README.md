### Hi there <a href="https://www.gautamkrishnar.com/"><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="5%"></a>
欢迎来到我的主页，这里有我的项目和学习笔记 :rofl:

- 🔭 &nbsp;我叫甘罗宇，英文名叫Oliver，1999年出生，来自中国长沙 :smile:
- 🌱 &nbsp;我目前在拓维信息系统股份有限公司工作 :wink:
- 💬 &nbsp;可以咨询我关于OpenHarmony的升级子系统能力以及关于心率变异性的任何问题
- 👨‍💻 &nbsp;如果想要了解我做的项目，可以参观我的CSDN [橄榄油加油](https://blog.csdn.net/weixin_62941746?type=blog)
- ⚡ &nbsp;爱好: 我 :heart: 运动和FPS游戏(Vlorant) (GamerTag: [三十岁仍想打职业]

📕 &nbsp;**最近的一些博客、论文和专利**
<!-- BLOG-POST-LIST:START -->
- [Heart rate variability analysis method for exercise-induced fatigue monitoring](https://www.sciencedirect.com/science/article/abs/pii/S1746809424000247)
- [OTA AB差分升级示例](https://blog.csdn.net/weixin_62941746/article/details/144419107?spm=1001.2014.3001.5502)
- [OpenHarmony HDF传感器驱动开发](https://blog.csdn.net/weixin_62941746/article/details/143566898?spm=1001.2014.3001.5502)
- [蓝牙连接及安全基础](https://blog.csdn.net/weixin_62941746/article/details/131833542?spm=1001.2014.3001.5502)
- [鸿蒙驱动开发-解决iphone手机热点重启后，设备未自动连接热点](https://blog.csdn.net/weixin_62941746/article/details/140991425?spm=1001.2014.3001.5502)
<!-- BLOG-POST-LIST:END -->

🔗 &nbsp;**Connect with me**
<p align="left">
<a href="https://dev.to/gautamkrishnar" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/dev-dot-to.svg" alt="gautamkrishnar" height="30" width="40" /></a>
<a href="https://twitter.com/gautamkrishnar" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="gautamkrishnar" height="30" width="40" /></a>
<a href="https://linkedin.com/in/gautamkrishnar" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="gautamkrishnar" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/4214976" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="4214976" height="30" width="40" /></a>
<a href="https://instagram.com/gautamkrishnar" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="gautamkrishnar" height="30" width="40" /></a>

### ✨&nbsp; 关于我

我是一名嵌入式软件工程师，目前投身于开源鸿蒙的驱动开发。对算法、人工智能有一定的了解。


#### 我的经历
以下记录了我的工作经历与学习经历。
##### 工作经历：
- 2024年7月-至今，在[拓维信息系统股份有限公司](https://www.talkweb.com.cn/)从事嵌入式软件开发工程师，主要从事于驱动的适配与开发。
  ##### 参与项目：
  1. 内核OTA流式升级能力开发，在RK3568 DAYU200上以OpenHarmony为基础实现的OTA流式升级，负责的内容包括：OTA流式升级包的制作以及异常回滚功能。OTA流式升级包的制作：增加流式控制；AB分区增加copy命令；AB分区解耦stash、free命令；diff反向切片；new切片；全量包切片；单分区无文件系统切片；update.bin包的封装。异常回滚：开机激活的AB分区异常回滚；data分区数据回滚。
  2. 基于HDF的传感器驱动开发，在RK3568 Rockpi基于OpenHarmony的HDF框架，适配了温湿度传感器SHT30、数码管TM1637、10轴传感器JY901B、光感传感器VEML7700、gpsATGM336。
  3. 控制器功能实现，水浸传感器数据传到在鸿控制器，然后数据到在鸿云，在鸿云平台显示在线，RSU连接5G路由器后上云，在鸿云平台显示在线，在鸿云平台控制器与RSU场景联动，有/无浸水能触发在鸿云通过mqtt下发指令到RSU。
- 2023年5月-2023年12月，在[九号公司]（https://www.ninebot.com/）从事嵌入式软件开发工程师，主要从事蓝牙协议栈的开发。
  ##### 参与项目：
  1. 感应接近解锁：在移远的模组ec200n的协议栈上进行应用开发，添加了RSSI距离解锁功能，编写了一套以卡尔曼为主的滤波算法，满足了低延迟稳定的特性，并成功加⼊到感应解锁3.0中，实现了不用nfc卡靠近车辆，按auto键或者坐上坐垫就能立即解锁。同时增加了AT指令，对卡尔曼滤波进行调参。
  2. Find My Network移植：将IOS的Find My Network移植到蓝牙开源协议栈BTstack恒玄芯片上，实现BLE ATT/GATT的应用开发，主要实现框架编译；协议栈平台初始化相关配置；adv模块移植适配；连接模块移植适配；gatt模块移植适配；安全加密模块适配；整体功能调试适配。
  3. NBOS蓝牙导航传输：在NBOS仪表项目上，进行导航传输的BLE数传服务开发（包括加密的GATT服务和不加密的数据传输服务），通信加密协议移植，以及蓝牙连接稳定性测试、丢包率、延迟、速率测试，对出现的断连不稳定、速率、广播数据等BUG进行修复，以及参数mtu、连接间隔等参数调优。配合APP组完成200N/800N模组上蓝牙连接速率测试。
##### 学校经历:
- 我于2024年6月硕士毕业于[北京体育大学（211）体育工程学院](https://sse.bsu.edu.cn/index.htm)电子信息工程专业 - 主要研究智能硬件的开发，生物电信号处理及应用等方面。
  ##### 其中以核心研发人员参与的项目：
  1. 冰雪头盔的视域和认知功能测试技术与设备研发（国家科技冬奥课题）
  2. 非线性递增负荷强度心率变异性系统研究（国家主动课题）
  3. 分段计时训练系统研发
  ##### 学术成果：
  1. 一篇SCI中科院二区论文
  2. 两项国家发明专利
  3. 第二届全国体育科技创新大赛优秀产品奖
  4. 第八届中国“互联网+”北京赛区二等奖
- [Blog Post Workflow](https://github.com/gautamkrishnar/blog-post-workflow) - A Github action to show your latest blog posts from any sources or StackOverflow activity or Youtube Videos on your GitHub profile/project readme automatically using the RSS feed. It is now used by over 5.6K+ users and running on thousands of GitHub actions runner every hour. It is also one of the top 20 [most used](https://github.com/marketplace?category=&query=sort%3Apopularity-desc&type=actions&verification=) GitHub actions internationally in GitHub Marketplace.
-  [SoCLI](https://github.com/gautamkrishnar/socli) Within 24 hours of its release, it garnered over 300 stars and now has nearly 2K users. This tool offers a convenient way of accessing StackOverflow directly from a terminal.
- [Motrix WebExtension](https://github.com/gautamkrishnar/motrix-webextension) - A browser extension for the Motrix Download Manager. It now has more than 20K+ users worldwide.
- [Refined GitHub Feeds](https://github.com/gautamkrishnar/refined-github-feeds) - A browser extension that adds filtering to the Github news feeds. 

[⏩ &nbsp; and many more](https://github.com/gautamkrishnar?tab=repositories&q=&type=source&language=&sort=stargazers) 

```
  ____                  ____                      
 / __ \___  ___ ___    / __/__  __ _____________  
/ /_/ / _ \/ -_) _ \  _\ \/ _ \/ // / __/ __/ -_) 
\____/ .__/\__/_//_/ /___/\___/\_,_/_/  \__/\__/  
   _/_/                  __  __   _               
  / __/  _____ ______ __/ /_/ /  (_)__  ___ _     
 / _/| |/ / -_) __/ // / __/ _ \/ / _ \/ _ `/ _ _ 
/___/|___/\__/_/  \_, /\__/_//_/_/_//_/\_, (_|_|_)
                 /___/                /___/       
```

During my free time, I actively contribute to open-source projects on GitHub. Due to my significant contributions to DuckDuckGo, I was appointed as a maintainer and community leader with write access to all of DuckDuckGo's repositories. I have also made contributions to a variety of other open-source projects and organizations, including Mozilla, Angular, Svelte, Node.JS etc
  
I also maintain and contribute to a lot of community open-source projects and libraries. Some of the communities includes [Tinkerhub Foundation](https://tinkerhub.org/), [Kites Foundation](https://kitesfoundation.org/), [Mozilla Foundation](https://foundation.mozilla.org/en/), [Patternfly](https://www.patternfly.org/) etc. I strongly believe that the true value of open-source is not just the code, it's the community around it.

You can read more about me and my open source journey at my website: [https://www.gautamkrishnar.com/](https://www.gautamkrishnar.com/)

I create most of my open-source projects to solve the challenges I encounter in life, with many more still waiting to be addressed. I am embarking on a quest to find solutions for each one, one problem at a time.

#### Awards and Achievements
- Won the 1st edition of [GitHub India Open Source Grants](https://github.blog/2021-09-12-recipients-open-source-grants-github-sponsors-india/)
- Worked as [DuckDuckGo Community Leader](https://web.archive.org/web/20210727164606/https://help.duckduckgo.com/community/community-leaders/) and Maintainer
- Won 1st place in Several Hackathons and events
  
<details>
  <summary><b>🛠️&nbsp;&nbsp;语言&nbsp;和&nbsp;工具</b></summary>
  <br/>
  <p align="left"> <a href="https://www.cprogramming.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> </p>

</details>

<img alt='analytics' src='https://profile-counter.glitch.me/gautamkrishnar/count.svg' width='0px'>
