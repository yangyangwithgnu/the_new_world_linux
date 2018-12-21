<h1 align="center">美丽新世界：linux 下的惬意生活</h1>
yangyangwithgnu@yeah.net  
http://yangyangwithgnu.github.io/  
2015-09-03 13:32:11


##谢谢
----
**捐赠：支付宝 yangyangwithgnu@yeah.net ，支付宝二维码（左），微信二维码（右）**
<div align="center">
<img src="https://raw.githubusercontent.com/yangyangwithgnu/yangyangwithgnu.github.io/master/pics/alipay_donate_qr.png" alt=""/>
<img src="https://raw.githubusercontent.com/yangyangwithgnu/yangyangwithgnu.github.io/master/pics/wechat_donate_qr.png" alt=""/><br>
</div>

**二手书**：书，我提高开发技能的重要手段之一，随着职业生涯的发展，书籍也在不断增多，对我而言，一本书最多读三遍，再往后，几乎没有什么营养吸收，这部分书对我已基本无用，但对其他人可能仍有价值，所以，为合理利用资源，我决定低价出售这些书，希望达到两个目的：0）用售出的钱购买更多新书（没当过雷锋的朋友 (๑´ڡ`๑)）；1）你低价购得需要的书（虽然二手）。到 https://github.com/yangyangwithgnu/used_books 看看有无你钟意的。



##【公告】
----
* **讨论**：任何意见建议移步 http://www.v2ex.com/t/137202


##【版本】
----
* v0.1.13，修正，2015-09-03：0）调整分区方案；1）优化提升虚拟机性能的措施；2）goldendict 屏幕取词方式；
* v0.1.12，修正，2015-06-15：最新源码安装的 goldendict 存在键盘鼠标控制权无法释放、剪贴板内容变更引发屏幕取词等奇怪问题，改用发行套件中预编译安装。
* v0.1.11，修正，2015-06-13：0）FF 下载管理器改用 flashgot，以实现整合 aria2c；1）删除 FF 的 flash 插件安装部分；2）其他用语通顺性调整。
* v0.1.10，新增/修正，2015-06-12：0）增加透明代理介绍；1）重写翻译工具章节；2）重新中文输入法章节。
* v0.1.9，新增/修正，2015-05-24：0）批量解析百度歌曲下载地址工具 yosong 的介绍；1）多种方式接入 tor 地下网络介绍；2）virtualbox 性能提升的可靠措施介绍。
* v0.1.8，新增，2015-02-04：借助插件 greasemonkey 在 FF 中随心所欲地控制任意页面，并配以实例：免登录、未付费环境下，直接下载百度音乐无损音乐。
* v0.1.7，新增，2015-01-27：0）推荐新的用于搭建 goagent 代理的免费空间；1）更新免费 SS 帐号获取源；2）bleachbit 不应清除 bash 历史在内的多个条目；3）像 vim 一样使用 FF。
* v0.1.6，新增，2015-01-07：0）新增免费 shadowsocks 帐号获取源；1）借由 goagent 在免费 VPS 空间搭建专属代理服务器；2）新增系统垃圾清理工具 bleachbit；3）给出 umplayer 外挂中文字幕显示乱码的解决思路。
* v0.1.5，新增/修正，2015-01-01：0）为提升系统性能，建议增配 SSD，相应调整分区建议；1）在文件管理器 nautilus 的文件列表采用目录优先；2）给出 goagent 的“install root certificate failed, Please run as administrator/root/sudo”警告提示的解决办法；3）由于 openSUSE 13.2 不再使用 gnome-session-properties，所以改用 ~/.bashrc 管理 goagent 启动项；4）给出 VB 虚拟机性能损耗的弥补措施；5）更新 winTPC 永久激活方法。
* v0.1.4，新增/修正，2014-12-4：0）更新 goagent 的 proxy.ini，GAE 不再支持 pagespeed，删除 proxy.ini 中的 pagespeed 选项；另外，PAC 存在漏洞，假定某运行 goagent 的客户端 IP 为 123.4.5.6，那么可以通过 http://123.4.5.6:8086/%2f..%2f..%2f..%2f..%2f..%2f..%2f..%2f..%2f..%2f..%2f/ 访问该客户端上任意文件，禁用 PAC 以封堵该漏洞；1）更新免费 SS 帐号获取网站。
* v0.1.3，新增，2014-11-6：0）增加免费 SS 帐号获取网站；1）增加自动获取 SS 帐号的工具 autoshadower；2）增加零配置的开箱即用 goagent 下载。
* v0.1.2，新增/修正，2014-10-21：0）增加免费 VPN 帐号、SS 帐号获取网站；1）修正部分错别字；2）修正部分 URL 与相邻字符串合并成超链接的错误。
* v0.1.1，新增/修正，2014-10-11：0）将目录制作成书签；1）翻墙部分相关图片更新，修正全文错别字，修正 kernel-desktop 的错误描述。
* v0.1.0，新增，2014-10-05：发布初始版本。


##【目录】
----
[0 发行套件](#0)  
........[0.1 发行套件的选择](#0.1)  
........[0.2 发行套件的安装](#0.2)  
........[0.3 发行套件的设置](#0.3)  
................[0.3.1 升级系统](#0.3.1)  
................[0.3.2 安装驱动](#0.3.2)  
................[0.3.3 美化桌面](#0.3.3)  
................[0.3.4 其他设置](#0.3.4)  
[1 日常办公](#1)  
........[1.1 办公文书](#1.1)  
........[1.2 电邮收发](#1.2)  
........[1.3 电子书阅读](#1.3)  
................[1.3.1 pdf 阅读](#1.3.1)  
................[1.3.2 chm 阅读](#1.3.2)  
[2 娱乐休闲](#2)  
........[2.1 歌曲聆听](#2.1)  
........[2.2 电影观赏](#2.2)  
........[2.3 音频编辑](#2.3)  
[3 网上冲浪](#3)  
........[3.1 网页浏览](#3.1)  
........[3.2 搭梯翻墙](#3.2)  
................[3.2.1 封锁原理](#3.2.1)  
................[3.2.2 跳出死循环](#3.2.2)  
................[3.2.3 google 服务器代理](#3.2.3)  
................[3.2.4 shadowsocks 代理](#3.2.4)  
................[3.2.5 VPN 代理](#3.2.5)  
................[3.2.6 地下网络代理](#3.2.6)  
................[3.2.7 个人专属代理](#3.2.7)  
................[3.2.8 透明代理](#3.2.8)  
[4 系统管理](#4)  
........[4.1 数据备份](#4.1)  
........[4.2 碎片整理](#4.2)  
........[4.3 垃圾清理](#4.3)  
[5 图形图像](#5)  
........[5.1 图片编辑](#5.1)  
........[5.2 色彩提取](#5.2)  
........[5.3 屏幕截图](#5.3)  
........[5.4 屏幕录像](#5.4)  
[6 windows](#6)  
........[6.1 版本选择](#6.1)  
........[6.2 资源下载](#6.2)  
........[6.3 网上购物](#6.3)  
........[6.4 即时通讯](#6.4)  
[7 其他杂项](#7)  
........[7.1 蓝牙收发](#7.1)  
........[7.2 手机管理](#7.2)  
........[7.3 英文翻译](#7.3)  
................[7.3.1 安装最新版](#7.3.1)  
................[7.3.2 词典选择](#7.3.2)  
........[7.4 中文输入](#7.4)  
................[7.4.1 导入搜狗细胞词库](#7.4.1)  
................[7.4.2 安装云拼音](#7.4.2)  
........[7.5 软件开发](#7.5)  
........[7.6 虚拟终端](#7.6)  
........[7.7 升级 BIOS](#7.7)  
........[7.8 有待提升](#7.8)  
[8 完结](#8)  


##【正文】
----
linux，从深海潜艇到高空侦察机、从房间大的工作站到手掌小的手机、从远至美国的 google 服务器到近在客厅的机顶盒，你都能见到它的身影。我无意说服你抛弃娴熟使用的操作系统转投 linux，假如你崇尚自由、渴求本质、热爱折腾，不妨一试！

<h2 name="0">0、发行套件</h2>
linux 本身还算不上完整的操作系统，它仅是个内核（一方面管理协调下层的硬件资源，一方面为上层软件提供基础服务支撑），需搭配系统软件（shell、编译器、包管理器、桌面环境等等）、应用软件（办公软件、网页浏览器、音视播放器、图片编辑器等等）才能成为一套具备日常使用功能的操作系统，即，发行套件。

<h3 name="0.1">0.1 发行套件的选择</h3>
linux 的发行套件多达 140+，但本质上大同小异，选定 kernel、包管理器、桌面环境、shell 后在系统层面就基本定型了，再按不同用途选定对应应用软件那么应用层面也就有了，最后就形成了各类发行套件，比如，盲人的 vinux、教育培训的 ubermix、家庭影院的 OpenELEC、安全渗透的 kali、国人专供的 deepin。所以，基本上，你不要在发行套件的选择上消耗精力，目前的主流发行套件包括：slackware、debian、fedora、arch、gentoo、ubuntu、lfs、openSUSE 等，它们各具特色、追随者众，比如，slackware 是目前存活时间最长古董级的发行套件（经验丰富），fedora 是 redhat 进行新技术实验的发行套件（技术创新），ubuntu 号称零配置开箱即用的发行套件（简单易用）、LFS（linux from scratch）让你从无到有构建个人专属的发行套件（配置灵活）、经验丰富+技术创新+简单易用+配置灵活 = openSUSE！所以，我向你推荐它。

openSUSE 最早是 slackware 在德国的本地化版本，后来因其加入了大量特色功能升格为单独的发行套件，其原名为 suse linux，10.2 版开始更名为 openSUSE。openSUSE 由 novell 公司赞助、社区推动的发行套件，它的相关源码和技术可由 novell 使用，作为 novell 企业版发行套件 SLES 的基础。openSUSE 旨在：a）推进 linux 在全球广泛使用；b）降低 linux 使用门槛，成为易于上手的发行套件；c）成为技术黑客和软件开发人员的首选平台。openSUSE 的 logo 是只可爱的变色龙，以此象征 openSUSE 灵活、敏捷的特性。当然，本文并不局限 openSUSE，适用于任何发行套件。
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/logo.png" alt=""/><br>
(logo)
</div>

另外，关于发行套件的版本更替，通常我会在最新正式版放出半年后再考虑，原因有二：一方面经过半年的大规模外部用户测试，大量 bug 已被发现并修正，一定程度上规避了使用系统的不稳定性；一方面各类应用软件开发人员有足够时间针对新版本的发行套件进行功能升级和兼容性优化，让我真真正正感受到新版本带来的各项提升。

<h3 name="0.2">0.2 发行套件的安装</h3>
既然是普通用户使用的发行套件，势必集成了某种桌面环境以便用户通过可视化界面操作计算机（底层由 x.org 提供图形图像服务，中间由桌面环境负责统一管理各应用软件发起的图形绘制请求并协调 x.org 予以响应）。基本上，各类发行套件都提供 gnome 和 kde 两种桌面环境供君选择（此外，还有 xfce、lxde、ede、rox 等等其他桌面环境可单独下载安装）。gnome 是隶属 GNU 项目群的子项目，全称为 the gnu network object model environment，采用 GTK（由 C 语言编写）作为底层开发库；KDE 全称 kool desktop environment，采用 QT（由 C++ 语言编写）作为底层开发库。gnome 和 kde 是 linux 中最为流行的桌面环境，从操作习惯和界面风格来看，我更喜欢 gnome。

安装发行套件包括如下几步：  

1. 第一步，下载镜像。选择桌面环境（gnome 或 kde）、系统构架（32 位或 64 位）；  
2. 第二步，制作安装 U 盘。U 盘安装既节省光盘介质费用，又能大幅提升安装速度，逐渐成为你安装系统的首选。借由 imagewriter 制作启动盘；  
3. 第三步，安装系统。整个过程一路 next，除分区稍加留意外，基本零难度。

强烈建议你增配一块 64G 的 SSD，结合原配的 300G 的 HD，对提升系统整体性能非常有帮助，因此，我的分区建议，在 SSD 上创建 18G 的 /、4G 的 swap、4G 的 /root/（或者，/home/）、34G 的 /winTPC/ 等分区，在 HD 上创建 300G 的 /data/ 分区：
  * linux 的分区不同于 windows，分区后没有所谓的 C:、D: 盘，而是一个个文件系统，这些文件系统没有具体名称，必须先挂载到某个目录（称之为挂载点）下才能正常使用，分区与目录一一对应；
  * 根目录 / 是安装 linux 操作系统的目录，大小 18G，将其置于 SSD 中有助于提升开关机速度；
  * 操作系统为扩展物理内存容量通常设有“虚拟内存”机制，将不活泼内存页（如，未关闭但长时间没使用的程序）从物理内存移至硬盘的虚拟内存，从而释放宝贵的物理内存空间，swap 分区就是所谓的虚拟内存，一般将其容量规划得等同于物理内存即可，但，只有在物理内存吃紧时（如，启用多个大型程序、运行了存在严重泄漏的程序）系统才会使用 swap，换言之，如果你机器物理内存较大（如，8G），也不一定非要将 swap 分区划为与物理内存一样大，给个 4G 让系统应个急即可。置于 SSD 中有利用提升系统性能。另外，由于不存在由用户直接发起的 swap 分区读写的场景，所以该分区不用挂载目录，由系统自行管理。如果想查看 swap 实时使用情况，可执行
vmstat 1
命令，输出信息中，si 表示 1 秒内写入 sawp 的内存页大小，so 从 swap 中读出的内存页大小，单位为 K；
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%9F%A5%E7%9C%8Bswap%E4%BD%BF%E7%94%A8%E6%83%85%E5%86%B5.png" alt=""/><br>
（查看swap使用情况）
</div>
  * 系统和应用程序的配置文件通常位于如下路径：~/.[app_name]、~/.config/、~/.local/share/、~/.local/share/applications/、/etc/[app_name].conf，基本上都在家目录下，为让重装系统后不丢失各个应用程序的配置，有必要为家目录单独创建一个分区。root 帐号的家目录为 /root/，其他帐号为 /home/，按你常用哪类帐号的习惯创建对应家目录的分区，大小 4G；
  * 在线购物、离线下载、即时通讯三种应用需要用到 windows 环境，在 linux 的虚拟机中安装 windows 是一种简便实现方式。既然是虚拟机，那么性能肯定大打折扣，把 win 虚拟机使用的所有存储均划至 SSD 是弥补性能损耗的措施之一。/winTPC/ 就是 win 虚拟机会用到的分区，在主系统中采用 NTFS 格式（详见后文“6 windows”章节）；
  * 所有非系统数据（如，歌曲、ebook、电影文件）相对静态，可放在 HD 上，所以我将整个 HD 划定单个分区 /data/，用于存放非系统数据，以便定期备份；
  

<h3 name="0.3">0.3 发行套件的设置</h3>
刚装好的操作系统都是默认设置，按个人习惯适当调整才贴心。

<h4 name="0.3.1">0.3.1 升级系统</h4>
linux 上系统升级分两部分，一部分是内核升级，一部分是发行套件升级（即，除内核外的驱动程序、系统软件、应用软件等升级）。

<h5 name="0.3.1.1">预编译内核选择</h5>
升级内核是为了享受新内核带来的安全增强、更多设备支持、以及各类新特性，有两种可选方式：方式一，如果熟悉内核编译选项，那么你完全可以针对自己的设备编译出最大程度发挥设备性能的定制版内核，另文详讲；方式二，如果不具备这些知识，也别急，openSUSE提供了几种常见场景的预编译内核，在软件仓库中选择中意的版本，安装、重启即可。常见的预编译内核包括：

* kernel-default 是系统默认版内核，这是保守选择，能保证在不论是桌面还是服务器上都能成功启用操作系统；
* kernel-desktop 在 kernel-pae 基础上针对桌面进行优化，并屏蔽了只有服务器上才会使用的内核功能，提升启动速度和响应速度；
* kernel-syms 含有内核源码符号，如变量名、函数名、结构名，便于内核跟踪调试；
* kernel-vanilla 是 kernel.org 发布的纯净版内核，清除了发行套件自行添加的补丁。

默认安装的是 kernel-default，无法使用大于 3G 的内存、未进行桌面优化，通常来说，你应改用 kernel-desktop。

安装新内核，执行  

```
zypper in kernel-desktop
```  
之后，你系统中将存有两个内核，kernel-default 和 kernel-desktop，如果系统中存在了多个可用内核，那就需要有个地方去记录、管理可用内核列表 —— /boot/grub2/grub.cfg，该文件中存放了不同版本内核列表，大概结构如下：

```  
### BEGIN /etc/grub.d/10_linux ### 
menuentry 'openSUSE 12.2' …
{
	...AAA...
}
submenu 'Advanced options for openSUSE 12.2' …
{
	menuentry 'openSUSE 12.2, with linux 3.4.11-2.16-default' …
	{
		...
	}
	menuentry 'openSUSE 12.2, with linux 3.4.11-2.16-desktop' …
	{
		...BBB...
	}
}
```  

假定希望选用 kernel-desktop 版内核，那么将 openSUSE 12.2, with linux 3.4.11-2.16-desktop 后花括弧内容全部拷贝覆盖至 openSUSE 12.2 花括弧内，调整后该文档结构大致如下：

```  
### BEGIN /etc/grub.d/10_linux ### 
menuentry 'openSUSE 12.2' …
{
	...BBB...
}
submenu 'Advanced options for openSUSE 12.2' …
{
	menuentry 'openSUSE 12.2, with linux 3.4.11-2.16-default' …
	{
		...
	}
	menuentry 'openSUSE 12.2, with linux 3.4.11-2.16-desktop' …
	{
		...BBB...
	}
}
```  
重启，下次系统将默认选用 kernel-desktop 版内核。登录系统后执行

```  
uname -r
```  
可查看当前使用的内核版本，执行

```  
less /proc/meminfo | grep MemTotal
```  
可查看系统识别的物理内存（输出第一行 MemTotal 字段中显示）。

<h5 name="0.3.1.2">发行套件升级</h5>
在进行发行套件升级前，先说说软件仓库。前面说过，发行套件是集成内核、驱动程序、系统软件、应用程序等一整套可支撑普通用户日常工作、生活需求的操作系统，可见，发行套件充当了软件筛选、软件打包、软件依赖库测试、软件兼容性测试等多个角色，为确保发行套件的健壮性，发行套件厂商（或社区）将它筛选、打包、测试过的软件放在官方软件仓库中，这样，不论哪个厂商开发的应用程序，用户只需到软件仓库中查找、下载、安装即可，不用（像 windows）再到各个软件官网逐一下载，当然，软件仓库中没有的，你仍可到软件官网单独下载，但要注意依赖库是否正确。软件仓库一般放在发行套件官方服务器上，用户通过更新源访问软件仓库。因此，更新源就是软件仓库的路牌。好了，了解了软件仓库、更新源等概念后，我们可以按如下步骤升级发行套件啦。

第一步，添加更新源。更新源的选择一定要严谨，尽量选择针对你使用的特定发行套件（甚至版本）且经过严格兼容性测试的源，这些更新源中收录的软件可能不是最新的但一定是最稳定的。基于这一思想，除了开启发行套件自带的几个默认官网更新源外，我增加了社区制作的各类更新源。这是大而全的更新源合辑，你需要的 99% 软件均可在此找到，其中，包括了两个重要源，一是 nvidia 显卡驱动源、一是 packman 第三方源（收录了大量经过严格测试的新软件）。具体操作，选择 community repositories，勾选所有源后保存即可。此外，社区源之外还有个 M17N 源，它大量收录了软件国际化、本地化等相关库文件，在让你品尝新功能以及满足本地化需求的同时，可能会引入系统稳定性和软件兼容性问题，请谨慎添加，http://download.openSUSE.org/repositories/M17N/openSUSE_13.2 。

添加完更新源后，我们还应注意几点：一、软件安装完成后自动删除安装程序，以节约存储空间，在 software repositories 中取消每个更新源的 keep downloaded packages；二、不同更新源中难免有重复的软件，这时，必须有个机制指示系统选用哪个源中版本——更新源优先级，优先级从 1 到 200，数字越小优先级越高，系统优选优先级高的更新源中的软件，通常来说，收录的软件测试周期越长、测试越严格的更新源应第一优先，即，http://download.openSUSE.org/update/13.2/ 的优先级应置为 1。

另外，如果你的网络环境无法流畅访问境外官网软件仓库，可以转为访问其在朝内镜像。国内还有几家上规模又有良心的 IT 企业，通过企业自身带宽优势，准实时地从发行套件官网同步软件仓库到国内服务器上，冏朝用户可调整更新源，实现从这些企业的服务器上高速访问软件仓库。目前，为各大发行套件建立国内软件仓库镜像的企业有搜狐、东软，高校有北京交大、中国科大、中央音乐学院（歌唱艺术家也玩 linux），开源社区有 LUPA 等，以上机构均为 openSUSE.org 官方注册镜像，具体镜像地址参见 http://mirrors.openSUSE.org ；

第二步，删除无用资源。第一类，系统默认安装的无用软件，比如，gnome 自带小游戏，我是完全不可能碰的，又如，自带的 email 客户端 evolution，而我喜欢更优的 thunderbird，这些软件可以卸载了：  
```  
zypper --no-refresh rm aisleriot cheese empathy evolution gnucash inkscape gnome-mahjongg polari transmission-gtk quadrapassel ibus
```  
第二类，应用程序的调试信息，只要你不对它们进行二次开发，也可以卸载了  
```  
zypper --no-refresh rm \*-debugsource* \*-debuginfo*
```  
当然，这两类无用资源最好在所有应用程序安装完毕之后再删除，不然删了可能又会出现。

第三步，升级系统。一旦指示系统启动升级，系统先在软件仓库（加载的所有更新源）中寻找是否有升级的可能。具体而言，存在三类升级方式：

* 第一种，命令 zypper update。对于本地已安装程序，如果软件仓库中有新版本，新老版本来至同个更新源，并且新老版软件构架相同（如 X86_64、i686、noarch 等等），那么才会执行软件升级操作，否则，即便源中存在新版，系统会提示类似如下信息 The following package updates will NOT be installed: chmsee，以告知 chmsee 虽有新版本但系统不会为你更新。换言之，update 是个非常保守的选项，即便软件仓库中有新版本，该命令也不一定让你得到新版软件。当然，如果你非要安装，也可以先执行 zypper install chmsee 命令，但此时系统还不会真正升级软件，而是反馈你最新版本号为 1.99.08-32.3.i586，若你确定要升级必须执行 zypper install chmsee-1.99.08-32.3.i586；
* 第二种，命令 zypper patch。为系统打补丁，这是提升系统安全性的重要一环，怒建阁下日常定期执行；
* 第三种，命令 zypper dist-upgrade。将系统与软件仓库同步一致，也就是说，本地安装的软件必须与仓库中的绝对一致，换言之，一旦执行该命令，本地软件将存在软件降级（本地版本高而仓库版本低）、软件升级（本地版本低而仓库版本高）、卸载软件（本地安装而仓库没有）、安装软件（系统认为有用，也就是 zypper install-new-recommends 命令输出信息中罗列的软件）等几种可能，特别是当你有通过源码安装过软件时切勿使用该命令。

总之，以上三个命令差异巨大，就日常而言，建议：用 zypper patch 为系统打补丁，用 zypper update 升级系统，用 zypper install program_version_num 升级 zypper update 无法升级的软件；

<h4 name="0.3.2">0.3.2 安装驱动</h4>
windows 下新增硬件外设，通常需要到硬件官网下载驱动，安装重启后系统才能识别新增硬件设备，linux 对驱动的管理，你可以（片面地）理解为全都打包进内核中了，只要是内核版本足够新（这正是前面升级内核的目的之一），99% 的硬件完全可以识别，换言之，你不用针对主板、芯片、网卡、显卡、声卡单独下载安装驱动，因为内核已经集成了它们的驱动，当然，我指的是集成驱动能很好地管理对应硬件设备，如果管理得不是那么好呢？那也可以单独安装，比如，显卡驱动。

我用的 N 卡，以此为例。openSUSE 预置了 N 卡驱动程序的开源版 nouveau，nouveau 由第三方开发，并未得到 nvidia 官方支持，是开发人员对 N 卡官方驱动逆向分析后的重新编码，实现难度巨大，虽效果不尽人意但也值得你尊重。作为普通用户，肯定希望最大程度发挥显卡特性，可以考虑安装 N 卡针对 openSUSE 发布的（闭源）官方显卡驱动吧。先增加 N 卡官方更新源 ftp://download.nvidia.com/openSUSE/13.2 ，再执行前面讲的升级命令即可。

最新的 nvidia 驱动（v340）存在严重 bug，会出现屏幕闪烁、撕裂现象，在官方修正前，你可以禁用 clipped-redraws 和  culling 两个显卡特性来临时解决，具体可在 /etc/environment 配置文件中添加

```  
CLUTTER_PAINT=disable-clipped-redraws:disable-culling
CLUTTER_VBLANK=True
```  

<h4 name="0.3.3">0.3.3 美化桌面</h4>
前面提过，我选装的是 gnome 桌面环境。gnome3 相较先前版本，不论从界面外观还是操作习惯都有非常大的差异，比如，窗口右上角只有关闭按钮，不再有最大化、最小化的概念；比如，托盘从任务栏中剥离出来，默认情况下为隐藏状态；比如，要选择桌面上的某个窗口，先得调出所有窗口的列表，在点击选择需要的那个；比如，不再有桌面图标，等等。如此这些，让很多人无法适应、被人诟病。也许是心态问题，我倒是挺适应这种操作模式的，使用 gnome3 也有几年时间了，虽谈不上驾轻就熟，但也不存在任何使用障碍，非要让我提一点意见的话，嗯～嗯～，好吧，真心希望 gnome 开发团队将横向布局的任务栏改为纵向布局，至于原因，你知道，如今的显示器几乎都是宽屏的，这就意味着屏幕的水平空间充裕而垂直空间紧张，现在又将任务栏水平放置在最顶部，进一步缩小了可用垂直空间，所以，强烈建议将任务栏垂直放置在屏幕左侧（效果类似 ubuntu 的 unity），希望下一版本能有所改善。另外，个人认为，对于一项新生事物（我说的是 gnome3），不妨以“拥抱变化、迎接未来”的心态去尝试，或许，你会发现，原来它才是你的最爱。

扯远了，接着说 gnome 的美化。桌面美化，无非就是选一套符合你审美观的主题，具体包括窗口主题、图标主题、光标主题、图形环境登录界面、系统声音等等，下载、安装、启用即可。

第一步，预准备。主题安装不像想的那么容易，为确保不同发行套件下均能安装成功，请提前作好如下准备：
* 安装时机：主题应尽量在安装完所有软件后再安装，否则可能出现部分软件与当前主题无法适配的情况；
* 各版本 GTK 库：GTK、GTK2、GTK3 等三个版本等基础库必须事前安装；
* 主题引擎：murrine、unico、adwaita、canvas、pixbuf 等几类主题引擎必须安装。若安装主题后仍存在滚动条粗大、按钮错位等情况，再把 gtk2-engine-\*、gtk3-engine-\* 都安装上；
* 安装路径。一般而言，主题文件和图标分别放至全局目录 /usr/share/themes/ 和 /usr/share/icons/，或者分别放至账号目录 ~/.themes 和 ~/.icons 均可。建议优选全局目录，账号目录有一定几率导致主题失效；

第二步，下载主题。推荐两个 gnome3 相关的主题网站：http://gnome-look.org 与 http://linux-lounge.deviantart.com （墙外，参见后文“搭梯翻墙”），慢慢选，喜欢哪个下哪个。个人非常喜欢那种扁、平、薄的风格，GTK 主题选用 Numix-Solarized（http://bitterologist.deviantart.com/art/Numix-Solarized-417575928 ），搭配 faenza 图标主题（http://tiheum.deviantart.com/art/Faenza-Icons-173323228 ）效果非常不错。

第三步，安装主题。将相关主题拷贝至 /usr/share/themes/ 和 /usr/share/icons/ 目录即可。具体而言，GTK 主题 Numix Solarized 解压后的 Numix Solarized/ 目录拷贝至 /usr/share/themes/，faenza 图标主题解压后得到的 Faenza/ 拷贝至 /usr/share/icons/。注意，a）如果无法选择对应主题，请确认是否多套了一层目录；b）/usr/share/themes/ 和 /usr/share/icons/ 目录中系统自带主题和图标切勿删除，否则将导致无法登录图像界面；

第四步，选择主题。运行 tweak tool，参照下图选择窗口和图标主题：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E9%80%89%E6%8B%A9%E4%B8%BB%E9%A2%98.png" alt=""/><br>
（选择主题）
</div>

第五步，启用主题。键入 alt+f2，输入 r 回车，看到没，刚才选择的主题已经生效。最终效果如下：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/Numix%20Solarized%20%E4%B8%BB%E9%A2%98.png" alt=""/><br>
（Numix Solarized 主题）
</div>

第六步，字体美化。openSUSE 中文显示默认采用文泉驿字体，相比之下，更喜欢微软雅黑那种方方正正的饱满字体，但微软雅黑中的英文字体又不咋地，有人发布了一款增强了英文字体的微软雅黑——yahei consolas hybrid 字体，可以下来试试，效果非常不错。双击字体按提示安装，安装完后进入 advanced settings，按如下设置即可：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%AD%97%E4%BD%93%E8%AE%BE%E7%BD%AE.png" alt=""/><br>
（字体设置）
</div>
另外，采用 QT 开发的程序必须借助 QT4 settings 管理程序单独设置：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/QT%20%E7%A8%8B%E5%BA%8F%E5%AD%97%E4%BD%93%E8%AE%BE%E7%BD%AE.png" alt=""/><br>
（QT 程序字体设置）
</div>

第七步，动态壁纸。GNOME3改变了很多传统用户习惯，淡化桌面概念就算之一，默认不再有桌面图标、无法将窗口最小化到任务栏、没有返回桌面按钮，99% 时间你看到的是某个应用程序的全屏窗口，体现了“内容至上”的理念，正因为此，GNOME3 中不再有动态壁纸功能，用户只有 1% 的时间可能看到桌面墙纸，动态壁纸功能理当下线——GNOME3 设计人员托梦告诉我滴 ~\_~。如果你仍然迷恋动态壁纸，可以通过如下方式实现：

首先实现基础功能。将如下 shell 代码拷贝至 auto_wallpaper.sh 文件，其中，两处的 /data/misc/software/misc./gnome3/wallpaper/ 替换为你存放图片的目录，4096 替换成你希望间隔多少秒自动切换一次墙纸：

```
#!/bin/bash 
cd /data/misc/software/misc./gnome3/wallpaper/ 
while [ 1 ] 
  do 
  set - * 
  length=$# 
  random_num=$(( $RANDOM % ($length + 1) )) 
  gsettings set org.gnome.desktop.background picture-uri "file:/data/misc/software/misc./gnome3/wallpaper/${!random_num}" 
  sleep 4096	# 68分钟变化一次桌面墙纸 
done
```

然后实现停止动态壁纸。先找到 auto_wallpaper.sh 脚本的进程 ID（严格地说，应该是启动该脚本的父 shell 进程 ID）：

```
linux-asze:~ # ps -ef | grep auto_wallpaper 
root 3027 1 0 16:58 ? 00:00:00 /usr/bin/gnome-terminal -x /bin/sh -c '/data/misc/software/misc./gnome3/wallpaper/auto_wallpaper.sh'
```

直接杀掉该脚本：

```
kill -9 3027
```

最后实现自动启动。将如下代码拷贝至 auto_wallpaper.desktop，并将该文件移至 ~/.config/autostart/ 目录。其中，/data/misc/software/misc./gnome3/wallpaper/auto_wallpaper.sh 替换为上面保存的 auto_wallpaper.sh 文件多绝对路径：

```
[Desktop Entry] 
Name=auto_wallpaper 
Exec=/data/misc/software/misc./gnome3/wallpaper/auto_wallpaper.sh 
Comment=change wallpaper every so often 
Hidden=false 
Type=Application 
X-GNOME-Autostart-enabled=true
```

说了这么多，作为普通用户，我们关注的还是 openSUSE 如何支撑我们的日常工作、生活需求。接下来看看，那些借助社区力量开发的优秀开源产品。（注，未特别说明，以下介绍的软件均可通过软件仓库查找、下载、安装）

如果你需要的软件在添加的各类软件仓库中都无法找到，可依次尝试如下两个专用搜索引擎：http://software.openSUSE.org/search 和 http://www.rpmfind.net ，若还是无法找到，只有借助通用搜索引擎找到该软件官网，再下载安装。

<h4 name="0.3.4">0.3.4 其他设置</h4>
某些软件在界面上未提供用于设置的 preferences 菜单项（如 gedit、 nautilus），这时只有请出 dconf-editor。windows 的很多底层设置可以在注册表中进行，linux 对应可以在 DBUS 中设置，dconf-editor 就是 DBUS 的图形界面编辑器。dconf-editor 管理的设置很多，大家可以自己琢磨玩玩，如下几类我建议你考虑（部分设置重启生效）：

* gedit 取消自动备份： org - gnome - gedit - preferences - editor，取消 create-backup-copy；
* gedit 显示行号：org - gnome - gedit - preferences - editor，勾选  display-line-numbers；
* gedit 高亮当前行：org - gnome - gedit - preferences - editor，勾选 highlight-current-line；
* 清空回收站时无须再次确认：org - gnome - nautilus - preferences，取消 confirm-trash；
* 文件管理器顶部显示当前路径：org - gnome - nautilus - preferences，勾选 always use location entry；
* 文件管理器 nautilus 以详情列表模式罗列文件列表：org - gnome - nautilus - preferences，default-floder-viewer 选择 list-view；
* 文件列表采用目录优先：org - gnome - nautilus - preferences，勾选 sort-directories-first；
* 文件列表以小图标且显示 ：org - gnome - nautilus - list_view，default-zoom-level 设置为 smaller；
* 文件列表以树形目录显示 ：org - gnome - nautilus - list_view，勾选 use-tree-view。

<h2 name="1">1 日常办公</h2>
现在的企事业单位几乎都需借助电脑办公，医生看病开处方、营业厅办理业务、会计帐务处理等等，电脑已成为各行各业办公的主要途径和手段。下面介绍几类常见的办公需求。

<h3 name="1.1">1.1 办公文书</h3>
word、excel、powerpoint 等三个软件是 windows 中必装的办公文书软件，以支撑我们文字处理、表格制作、汇报演示等工作需要。linux 中我们对应有 writer、calc、impress 等软件，这三个软件（外加 draw、math、base）就是大名鼎鼎的 libreoffice 套件。libreoffice 完全兼容 ms-office 文档，甚至还可以直接转存为 pdf 格式文件，

软件名称：libreoffice

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/Writer.png" alt=""/><br>
（writer）
</div>
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/Calc.png" alt=""/><br>
（calc）
</div>
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/Impress.png" alt=""/><br>
（impress）
</div>

设置调整：tools -> options -> language settings -> writing aids，取消 options 中的所有选项，以禁止拼写检查。

<h3 name="1.2">1.2 电邮收发</h3>
很多人喜欢通过邮件服务提供商官网进行邮件收发，强烈建议改用邮件客户端，避免频繁登录邮箱，同时，还能离线查阅邮件内容。好的邮件客户端除了正常收发邮件外，还应具备地址簿管理、垃圾邮件过滤、多账户管理、日程安排、同步删除远程邮件，甚至为常见邮件提供商智能配置等等高级功能，thunderbird 算是不错的。

软件名称：thunderbird

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/thunderbird.png" alt=""/><br>
（thunderbird）
</div>
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%86%99%E9%82%AE%E4%BB%B6.png" alt=""/><br>
（写邮件）
</div>

<h3 name="1.3">1.3 电子书阅读</h3>
电子书格式类型较多，包括 hlp、lit、wdl、ceb、abm、pdg、epub、pdf、chm 等等，但常见的还是最后两类。下面介绍下 pdf 和 chm 的阅读器。

<h4 name="1.3.1">1.3.1 pdf 阅读</h4>
世上有三件事你无法回避：死亡、税收、阅读 PDF 文档。

软件名称：evince

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/evince.png" alt=""/><br>
（evince）
</div>

使用问题：你知道，正常情况下，被选中的文本段会反色高亮显示，估计是 evince 本地化问题（未用 unicode 编码 -\_-??），某些中文 pdf 文档，反色显示的文字会成乱码，虽不影响真正复制到粘贴板中的内容（换言之，从 evince 中复制出来的文字仍正常），但一定程度上影响了我等喜欢选中一段看一段的用户阅读体验。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%9C%AA%E9%80%89%E5%89%8D%E7%9A%84%E6%96%87%E6%9C%AC.png" alt=""/><br>
（未选前的文本）
</div>
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E9%80%89%E4%B8%AD%E5%90%8E%E7%9A%84%E6%96%87%E6%9C%AC.png" alt=""/><br>
（选中后的文本）
</div>

其他说明：推荐几个常用的软件开发相关电子书下载网站：http://it-ebooks.info 、http://www.freetechbooks.com 。

另外，我对 pdf 修改也有使用需求。很遗憾，linux 下并无稳定、高质量的 pdf 修改开源工具，上古时代的 pdftk、flpsed、pdfedit 一众古董完全派不上场，pdf studio 算是唯一功能达标的，但又是闭源共享软件，不推荐。既然修改不了 pdf，添加注释总可以吧，xournal 就是满足这一需求的软件。

软件名称：xournal

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/PDF%E4%BF%AE%E6%94%B9.png" alt=""/><br>
（PDF修改）
</div>

<h4 name="1.3.2">1.3.2 chm 阅读</h4>
虽然 chm 文档越来越少，但难免还是会遇到，有两个工具可阅读 chm：chmsee 和 kchmviewer。

软件名称：chmsee；

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/chmsee.png" alt=""/><br>
（chmsee）
</div>

<h2 name="2">2 娱乐休闲</h2>
linux 不是 IT 大牛的专属系统，它不仅可以支撑生产运维，同时，也可为你提供日常休闲娱乐。

<h3 name="2.1">2.1 歌曲聆听</h3>
常见的音频格式包括：mp3、ogg、aac、mp4、ape、wav、flac 等，windows 下知名的音频播放器 foobar2000 完美支持这些格式，linux 下的 deadbeef 从解码效果来看，有过之而无不及。

软件名称：deadbeef

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/deadbeef.png" alt=""/><br>
（deadbeef）
</div>

使用问题：

* 一般来说，通过软件仓库安装某个软件，系统会自动关联安装依赖库，以保障软件正常运行，但，deadbeef 依赖的必要插件 deadbeef-restricted-plugins 并未自动关联，需手工自行添加，否则 deadbeef 无法加载歌曲；
* 要让当前播放曲目显示在播放列表窗口中可以：ctrl-j 快捷键，或者，菜单中选择 playback -> scroll follows playback；

另外，关于歌曲的获取，yosong（https://github.com/yangyangwithgnu/yosong ）是个不错的选择。百度音乐上面有很多优质歌曲，但没有白金 VIP 帐号，这些高品质的歌曲都无法下载，yosong 可以帮我绕开百度的各种限制，解析出高品质歌曲的最终下载地址。基本上，现在的 yosong 具备了以下能力：   
0）绕开白金收费会员才能下载无损品质歌曲的限制；   
1）绕开百毒自身版权问题歌曲而无法下载的限制；   
2）绕开非大陆之外区域无法下载的限制；   
3）一键式全站歌曲下载；   
4）绕开高频访问出现验证码的限制。   
如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/yosong%20%E6%AD%8C%E6%9B%B2%E5%9C%B0%E5%9D%80%E8%A7%A3%E6%9E%90.gif" alt=""/><br />
（yosong 歌曲地址解析）
</div>

<h3 name="2.2">2.2 电影观赏</h3>
我看电影有个习惯，喜欢把电影全屏铺满后再看，这样不至于在如今满是宽屏幕的环境中把人物压缩得又扁又胖。另外，针对视频文件名类似的多个文件要能连续播放（也就是连续自动播放连续剧）。linux 下找了一圈都没发现满意的，包括大名鼎鼎的 vcl 和 mplayer，直到有天我遇到 umplayer。umplayer 是基于 mplayer 二次开发的软件，默认支持（即内置相关格式解码器） mkv、wmv、avi、mpg、3gp、mov、rm、mpeg、mp4 等视频格式。

软件名称：umplayer

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%99%AE%E9%80%9A%E6%AF%94%E4%BE%8B.png" alt=""/><br>
（普通比例）
</div>
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%85%A8%E5%B1%8F%E9%93%BA%E6%BB%A1.png" alt=""/><br>
（全屏铺满）
</div>

设置调整：全屏铺满设置，video -> aspect ratio -> disabled；

使用问题：全屏纵向拉伸设置只能针对单部影片有效，无法保持为永久设置，播放其他影片需要重新设置；默认设置下外挂中文字幕乱码显示，你需要在 options - preferences - subtitles 的 subtitles 中勾选 try to autodetect for this language: chinese (zh)，并且在 font and colors 中选择 enable ssa/ass subtitles。

我的听力还没达到不用字幕的层级，难免有时下载回来的字幕时间轴有偏差，所以，字幕工具必须得有。aegisub 是个非常棒的字幕工具，简单易用、上手极快。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%AD%97%E5%B9%95%E5%B7%A5%E5%85%B7%E8%B0%83%E6%95%B4%E6%97%B6%E9%97%B4%E8%BD%B4.png" alt=""/><br>
（字幕工具调整时间轴）
</div>

推荐几个网站。高清电影，http://www.xunleigang.com/forum-2-1.html 、http://www.hd1080.cn/ ；高清美剧，http://www.ttmeiju.com/ ；字幕，http://www.zimuku.net/ 、http://www.subom.net/ 。


<h3 name="2.3">2.3 音频编辑</h3>
听到一首喜欢的歌曲，想把它设置为手机来电铃声，但整首歌曲又太长，最好能把高潮部分提取出来，一来电就进入高潮（-\_-$，你想啥～）。

软件名称：audacity；

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/Audacity.png" alt=""/><br />
（audacity）
</div>

<h2 name="3">3 网上冲浪 </h2>
问：宅男最怕失去啥？答：网络（谁说苍老师？@\_@！）。网络在给我们带来无限乐趣的同时，也在不断地改变着人类生活方式。

<h3 name="3.1">3.1 网页浏览</h3>
浏览器是互联网入口，各大互联网公司必争之地。opera、chrome、firefox 三大浏览器，opera 功能上没有多少过人之处且不开源，丢之；chrome 虽有开源版本 chromium，但很多插件都仅支持 windows 平台而在 linux 下无法使用（包括google自己出品的 Chrome Toolbox），弃之；firefox，开源且以 linux 为第一阵营，凭借其高安全性和可扩充性赢得大量忠实用户。

软件名称：firefox；

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/firefox.png" alt=""/><br>
（firefox）
</div>

你对 firefox 的任何需求，几乎都可以通过其丰富的插件资源得到满足（另一个有如此庞大插件资源的软件当数 vim 了，后面有介绍）。进入 tools -> add-ons 即可在线查找需要的插件，找到后点击在线安装即可，安装完成需重启浏览器以让新装插件生效。下面介绍几款我觉得非常有用的插件。

**下载管理**，flashgot。aria2c，linux 环境的彪悍下载利器，支持从不同协议（http(s)、ftp、bt、磁力等等）的不同来源下载同个文件，速度非同一般。aria2c 是个命令行程序，我需要个插件，将其整合进 firefox 中，flashgot 可以做到。flashgot 本身是个页面资源下载工具，它可以解析当前页面所有可下载资源的地址，将要下载地址传递给系统中已安装的外部下载工具（如，aria2c、curl、wget），实现资源排量高速下载，这非常适用那些需要下载网页上所有图片的场景。对我而言，享受的是 flashgot 的副作用，在 firefox 中直接调用 aria2c。使用很简单，在 flashgot 中选择使用 aria2c 作为外部下载工具，接着按下 alt 同时点击下载链接即可，如下所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/FF%20%E6%95%B4%E5%90%88%20aria2c.gif" alt=""/><br>
（FF 整合 aria2c）
</div>

**对象拖拽**，quickdrag。若拖拽链接则直接打开，若拖动文本则在当前搜索引擎中搜索。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%AF%B9%E8%B1%A1%E6%8B%96%E6%8B%BD%E6%8F%92%E4%BB%B6%20quickdrag.gif" alt=""/><br>
（对象拖拽插件 quickdrag）
</div>

另外，我不太喜欢立即激活新页面，本来 firefox 中有个选项（preferences -> tabs -> when I open a link in a new tab, switch to it immediately）可用于此设置，但长年无效，只能直接修改它的配置项：地址栏中输入 about:config，查找 browser.tabs.loadDivertedInBackground 配置项，双击使其为 true 即可。

**鼠标手势**，all-in-one gestures。我常用的右键向左拖动表示退回、向右拖动表示前进。如下所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E9%BC%A0%E6%A0%87%E6%89%8B%E5%8A%BF%E6%8F%92%E4%BB%B6%20all-in-one%20gestures.gif" alt=""/><br>
（鼠标手势插件 all-in-one gestures）
</div>

**双击关闭 tab**，close tab by double click。无须多说，个人习惯；

**侧边显示**，all-in-one sidebar。将收藏夹、下载管理、插件管理、访问历史等统一收纳到侧边条中，如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/all-in-one%20sidebar.png" alt=""/><br>
（侧边显示插件 all-in-one sidebar）
</div>

**恢复关闭页面**，Undo Closed Tabs Button。下载安装好后，先要通过 customize 将 undo 图标拖动到 firefox 工具栏中才能看到。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%81%A2%E5%A4%8D%E5%85%B3%E9%97%AD%E9%A1%B5%E9%9D%A2%E6%8F%92%E4%BB%B6%20Undo%20Closed%20Tabs%20Button.gif" alt=""/><br>
（恢复关闭页面插件 Undo Closed Tabs Button）
</div>

**在线视频下载**，1-Click YouTube Video Download。随着在线视频的繁荣，国外的 YouTube、国内的 PPTV 等一大批视频网站上沉淀了很多有价值的视频，考虑到天朝宽带排名全球 96 位的现状，为了不影响观影体验，我有很强的驱动力将在线视频下载到本地。

YouTube 上的视频，可由插件 1-Click YouTube Video Download 实现下载。安装好该插件重启 firefox 后，进入某个具体视频页面，在视频左下角多了个 Download 按钮，点击该按钮你将看到不同分辨率的视频下载地址列表，见下图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/YouTube%20%E5%9C%A8%E7%BA%BF%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD%E6%8F%92%E4%BB%B6%201-Click%20YouTube%20Video%20Download.gif" alt=""/><br>
（YouTube 在线视频下载插件 1-Click YouTube Video Download）
</div>

此外，国外 vimeo、metacafe、intv 甚至 facebook 等等网站上的视频，我推荐你使用在线工具 http://en.savefrom.net/ 解析视频地址；国内的 PPTV、优酷、土豆、奇艺等等视频网站，可以通过硕鼠 http://www.flvcd.com 解析。

**添加搜索引擎**，Add to Search Bar。互联网是个巨大的知识库，你需要的任何知识都可以从中获取，前提是有个给力的搜索引擎。在我看来，好的搜索引擎应该：检索范围广泛、收录页面快速、检索结果无屏蔽、原创内容优先、智能分析相似关键字。

搜索引擎如何选择？根据搜索内容的不同，我会依次使用如下几个引擎进行查找：

1. 英文资料，先 http://www.duckduckgo.com 后 http://www.google.com ，前者剔重算法完胜后者，而且搜索过的关键字绝对不记入 cookie。（从大陆发起的访问自动被转向到香港服务器 http://www.google.com.hk ，要访问美国服务器可用如下网址 http://www.google.com/ncr ，其中，ncr 为 no country redirect，即不根据访问请求发起国家进行重定向）；
2. 中文技术资料，先 http://tw.search.yahoo.com 后 http://www.google.com.tw ； 

啰嗦几句，台湾人的技术文章多以原创为主，不像冏朝清一色的转载，特别是，很多国外经典计算机书籍引入冏朝后，被所谓的大学教授翻译得比日文还难读（《thinking in c++》，多经典的一本书，翻译得老子想骂人），这时，可以考虑找对应台译版（台版《thinking in c++》由蔡明志先生翻译），虽说有些术语叫法不同，但基本体现了著作原意。

如果你要用台湾搜索引擎查找技术资料，得注意以下几点：

* http://tw.search.yahoo.com 和 http://www.google.com.tw （及其搜索结果）均为墙外网站，要想正常访问必须搭梯，具体参见后文“搭梯翻墙”；
* 为提高搜索命中率，尽量用台湾术语（如，面向对象-物件导向）；
* 务必输入繁体字（可在 ibus 输入法中设置），否则将会出现很多朝内搜索结果；

另外，但凡中译书籍，建议直接海购繁体中文版，前面说过台湾人翻译的质量远胜囧朝，再次悲哀 :-(。

话外音，国外将冏朝中文叫作 simplified chinese，而将台湾中文叫作 traditional chinese，也就是说，在老外眼里，冏朝用的是删减后的中文，而台湾用的才是老祖宗传下来的纯正传统中文。

添加搜索引擎。安装好 Add to Search Bar，在搜索引擎首页的输入框中右键，选择 add to search bar 即可，如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/Add%20to%20Search%20Bar.png" alt=""/><br>
（Add to Search Bar）
</div>

添加后，在浏览器的搜索引擎列表中查看所有搜索引擎：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%90%9C%E7%B4%A2%E5%BC%95%E6%93%8E%E5%88%97%E8%A1%A8.png" alt=""/><br>
（搜索引擎列表）
</div>

搜索操作习惯。你可以在 firefox 右上角的搜索引擎列表中选择喜欢的引擎直接搜索，也可以在页面上（借助 quickdrag）直接拖拽要搜索的关键字启用当前引擎进行搜索；

**代理开关**，Autoproxy。Autoproxy 本身不具备代理功能，它通过一个在线配置文件，实时分析用户发起的网站访问请求中，哪些必须走代理访问、哪些可以直接访问。具体请见“搭梯翻墙”章节，Autoproxy 辅助 GoAgnet 可实现完美翻墙。

**HTTP 抓包**，Live HTTP Headers。作为一名伪 geek，深挖本质是必不可少的特质，有了它，任何网页请求都逃不过你的法眼：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/HTTP%20%E6%8A%93%E5%8C%85.gif" alt=""/><br />
（HTTP 抓包）
</div>

**自定义客户端类型**，User Agent Switcher。某些网站会限制客户端类型，比如，你公司的 OA 系统，必须是 win + IE 才能访问。服务端通过解析 HTTP 报文中的 User-Agent 字段进行判断是否满足要求。这时，你可以用 User Agent Switcher 插件欺骗服务端，达到随意指定客户端类型的目的，比如，指定为 win7 + IE10 可以伪装成一台办公网内的普通电脑，指定为 ios7 + Safari5 甚至可以伪装成一台 iphone 手机，访问 http://www.useragentstring.com/ 确认是否生效。可伪装类型的完整列表见 http://www.useragentstring.com/pages/useragentstring.php 。未开启 User Agent Switcher 时，访问 http://www.useragentstring.com/ 侦测到我的系统为 Mozilla/5.0 (X11; Linux i686; rv:31.0) Gecko/20100101 Firefox/31.0，开启 User Agent Switcher 后，再次访问 http://www.useragentstring.com/ 侦测到的系统则变为我指定的 Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1)，如如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E8%87%AA%E5%AE%9A%E4%B9%89%E5%AE%A2%E6%88%B7%E7%AB%AF%E7%B1%BB%E5%9E%8B.gif" alt=""/><br />
（自定义客户端类型）
</div>


**像 vim 一样使用 FF**，vimFx。作为一个无鼠论的 vim 重度用户，我希望 vim 常用的基本操作能在 FF 中同样适用，vimFx 让我梦想成真。同质的插件不少，之所以选用 vimFx，原因有三：  
0）vimFx 不会破坏 FF 自身的任何快捷操作，你随时可以用 FF 自身快捷键进行操作，比如，FF 用 ctrl-k 快速定位光标到搜索栏；  
1）vimFx 支持可视化的方式进行快捷键配置；  
2）vimFx 支持快速移动。vim 用户肯定用过 easymotion 插件，vimFx 就是 FF 的 easymotion，可以把页面上任何你能点击的元素都用不同字母标识出来，随后键入对应字母即可实现元素点击事件，完全摆脱移动鼠标、点击鼠标的麻烦，太性感了。 

我常用的快捷操作如下。FF 自身相关：
- shift-?，显示 vimFx 界面
- esc，恢复默认状态
- /，查找关键字
- n，焦点移至下个关键字匹配项
- N，焦点移至上个关键字匹配项
- o，光标定位至地址栏
- ctrl-k，光标定位至搜索栏（FF 快捷键）
- R，刷新当前页面含 js、css、img 在内的所有元素  

tab 页相关：
- t，新建 tab 页
- x，关闭当前 tab 页
- u，恢复最近一次关闭的 tab 页（修改 vimFx 默认配置）
- ctrl-pgup，切换至前个 tab 页（FF 快捷键）
- ctrl-pgdn，切换至后个 tab 页（FF 快捷键）  

URL 相关：
- ctrl-l，把当前页面上所有能获取焦点的元素均用字母进行标识，键入对应字母后在当前 tab 中打开对应 URL（修改 vimFx 默认配置）
- l，把当前页面上所有能获取焦点的元素均用字母进行标识，键入对应字母后在新建 tab 中打开对应 URL（修改 vimFx 默认配置）  

页面滚动相关：
- gg，滚动至页首
- b，滚动至页尾。默认的 G 无效，不得不重新设定（修改 vimFx 默认配置）
- j，页面下移
- k，页面上移
- [space]，页面下翻一页（FF 快捷键）
- [shift-space]，页面上翻一页（FF 快捷键）

全键盘操作真是太自然了。下面的示例，访问 https://github.com/yangyangwithgnu/ ，在新建 tab 中打开 the_new_world_linux 的链接，接着查看该链接的页面内容：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%83%8F%20vim%20%E4%B8%80%E6%A0%B7%E4%BD%BF%E7%94%A8%20FF.gif" alt=""/><br />
（像 vim 一样使用 FF）
</div>

**随意控制任意网站**，greasemonkey。如果说各色插件给予了 FF 无限扩充的能力，那么 greasemonkey 则赋予了你随意操控指定网页的力量。说得玄幻、实则靠谱。FF 为你呈现的每个页面，先从服务器上获取了该页面的代码（HTML、CSS、JS 等等），再在本地进行解析（以及渲染），如果在解析前，有某种机制告诉 FF 说，“稍等片刻，把我这儿的第三方 JS 加入到你刚获取的页面代码中，一并解析”，那么，借助第三方 JS，基本上，你就可以随意控制该页面在 FF 中展示的效果。这里“稍等片刻”和“一并解析”的机制，正是由 greasemonkey 所提供的。我们通常把这里说的第三方 JS 称为“用户脚本”（user scripts），你可以自行编写符合 greasemonkey 规范的用户脚本，当然也可以直接使用其他人写好的，比如，https://greasyfork.org/ 、https://userstyles.org/ 、https://openuserjs.org/ 、https://monkeyguts.com/ ，这几个网站中托管了大量用于不同场景的用户脚本。

这里以百度音乐下载为例，向你展示 greasemonkey 的强大。你知道，百度音乐上的每首歌曲均有标准、超高、无损等三种品质，要想下载无损品质必须是收费用户（如，歌曲 http://music.baidu.com/song/122674119 ），现在，greasemonkey 配合适合的用户脚本，你只需登录普通非付费帐号即可下载到无损歌曲。

首先，访问 https://addons.mozilla.org/en-us/firefox/addon/greasemonkey/ 在线安装 greasemonkey，安装后重启 FF，你会在 FF 右上角附近看到一个猴子图标（若是灰色则应点击将其开启）；

然后，访问 https://greasyfork.org/en/scripts/3953-baidu-music-download 点击 install this script 按钮安装用户脚本，该脚本可实现无损歌曲下载；

接着，访问待下载歌曲页面 http://music.baidu.com/song/122674119 ，在关闭 greasemonkey 状态下，默认、正常的该页面上只有一个下载按钮，点击后提示你登录 VIP 付费帐号方可下载无损品质，在开启 greasemonkey 状态下，你将看到多出一个下载按钮，用普通帐号登录后，点击其后将会罗列出不同品质的下载选项，选择无损即可直接下载，如下所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E9%9A%8F%E6%84%8F%E6%8E%A7%E5%88%B6%E4%BB%BB%E6%84%8F%E7%BD%91%E7%AB%99%E5%AE%9E%E7%8E%B0%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E7%99%BE%E5%BA%A6%E6%AD%8C%E6%9B%B2.gif" alt=""/><br />
（随意控制任意网站实现免费下载百度歌曲）
</div>
如果你希望下载某个歌手的所有专辑的说所有歌曲，那么只得找 yosong（https://github.com/yangyangwithgnu/yosong ）帮忙咯。


<h3 name="3.2">3.2 搭梯翻墙</h3>
> _Everyone has the right to freedom of opinion and expression; this right includes freedom to hold opinions without interference and to seek, receive and impart information and ideas through any media and regardless of frontiers._
>
> ---- \<\<Art. 19, Universal Declaration of Human Rights, 1948\>\>.

为让大家保有天朝优越感，+- 屏蔽了大量“非法”网站，有境内/境外的、有纯技术的、有爱情动作的、有轮子功的，反正 +- 不喜欢的通通借由 GFW 这堵墙屏蔽掉。当然，也有主动屏蔽囧朝访问请求的，比如，sourceforge.net 非常反感囧朝的封闭，你朝子民别来我这儿。裆从小就教育我们，哪里有压迫哪里就有反抗，话说屏蔽之前，天朝的宅男还可以下载几部码片看看打发时间，嘚，看吧，让你屏蔽，没事做了，那就研究下怎样翻墙吧。

<h4 name="3.2.1">3.2.1 封锁原理</h4>
+- 最常用的封锁手段有二：关键字过滤、DNS 劫持。

关键字过滤。你也别谈“滤”色变，全国时时刻刻这么大的网络流量交换，GFW 不可能做到全量、实时过滤分析，一是它没这么强悍的处理能力、二是这一过程严重影响网速。GFW 过滤，只能全网随机抽查，或者，有针对地对指定区域、指定 IP 进行，如果哪天你觉得小区里就你网速慢，恭喜，随机到你家。GFW 对选中 IP 的网络数据包进行实时解析，一旦发现敏感关键字，则短暂封锁终端 IP，导致所有网络访问中断。显然，要过滤关键字，必须满足数据包以明文传输这一必要条件。如果我们的浏览器支持加密访问网页，那么 GFW 永远不可能解析出关键字。默认情况下，我们通过 http 协议进行网页访问，这是明文，而 https 协议，则是密文。换言之，如果哪个浏览器默认支持 https，则可完全突破“关键字过滤”这种封锁手段 —— firefox；

DNS 劫持。当用户输入 http://www.google.com 希望电信运营商解析出服务器真实 IP，以便访问 google，运营商在 +- 作用下停止解析这个URL，导致用户访问失败，这就是 DNS 劫持。针对这种封锁手段有两种解决方式：方式一，不依赖运营商而靠自己获取解析域名及其对应真实 IP；方式二，借助境外运营商进行域名解析。

* 方式一，自己解析域名及其 IP，可以借助 SmartHosts 实现。SmartHosts（http://smarthosts.googlecode.com/svn/trunk/hosts ），由众网友共同维护的一个 hosts 文件，里面存放着大量被墙域名及其 IP，将其内容追加到本地 /etc/hosts 文件中，此后，hosts 中罗列出的所有 URL 你可以正常高速访问了。但是，存在两个问题：A）SmartHosts 中的每条记录（URL 与 IP）都是各热心网友一条条手工添加的，不可能覆盖完所有被墙网站，肯定会出现一些你需要访问但又不在此列表中的网站；B）SmartHosts 更新周期不定，有时 3 天、有时 30 天，所以你需要不时去关注，有更新是及时添加至本地 hosts 文件中（最近更新时间 2013-12-07 12:16）。这种方式效果有限，你应该把精力放在方式二上。
* 方式二，借助境外运营商进行域名解析，这是非常具有弹性的解决方案，只有它才能实现完美翻墙。接下来我将介绍几种基于这一思路发展出来的翻墙方式，后一种均依赖前一种，你须依次了解，切勿跳越。

<h4 name="3.2.2">3.2.2 跳出死循环</h4>
翻墙，你得借助专用工具、使用证书，遇到问题时还得搜索相关解决办法，而这一切信息都在墙外，也就是说，本来你想用这些工具实现翻墙，又不得不先翻墙才能获取这些工具，这就成了个死循环。所以，我得先介绍一种体验式的翻墙方式，这种翻墙方式不追求速度快、流量大、适用广、加密强等等特性，哪怕只能用 1 个小时，关键是在墙内要能直接能获取。

从我的经验来看，国内的收费 VPN 代理最适合（先别纠结啥是 VPN）。一般来说，收费 VPN 服务商为招揽用户，通常会放出一些免费试用 VPN 帐号让用户买单前体验一把，虽然试用帐号存在限定流量、限定流速、禁止 P2P 下载等各种约束，但通过它我们能获取后续其他强大翻墙工具。在百毒（google.com 在墙外）中搜索“VPN 试用”会出来很多收费 VPN 服务提供商，比如，https://www.wojsq.com/ ，用 163.com 邮箱（gmail 在墙外）注册个试用帐号，成功后你会收到帐号和密码的邮件，该帐号每月有 1G 流量（更多免费 VPN 可访问 http://ilvpn.com/free-vpn/ 获取）。接下来，在 networking settings 界面中点击左侧的 + 按钮新建 VPN 配置，interface 选 VPN 后 create...，选 point-to-point tunneling protocol (PPTP) 后 create...，接着在新界面中，connection name 中设定本 VPN 的代理名（如，wojsq），在 VPN 选项卡 gateway 中设定代理服务器 IP （https://www.wojsq.com/server/query 最上两行为试用帐号可用的 IP），user name 和 password 中分别设定邮件中写明的 VPN 用户名和密码，在 advanced... 中，authentication 只选定 MSCHAP 和 MSCHAPv2，security and compression 中选定 MPPE 加密、BSD、deflate、TCP 三种压缩模式，最后保存即可。这时，你的 VPN 配置已完成，接下来，点击 gnome 桌面右上角的网络连接图标，你会看到 VPN connections 下罗列出刚才创建的 wojsq，选中它系统便开始进行 VPN 连接，如果你的网络连接图标上多出一把小锁，说明 VPN 连接成功，到 http://www.ip38.com/ 确认下是否网络访问出口 IP 是否成为国外 IP，若是则翻墙成功。

这种流速低、流量少、稳定性差的翻墙方式虽然存在诸多不足，但成功为我们开启了进入自由世界的大门，为高级代理提供了基础环境，**本章后续介绍的其他代理涉及到工具和证书都在墙外，请务必在开启本节的 VPN 让系统处于已翻墙环境**，否则无法访问。

<h4 name="3.2.3">3.2.3 google 服务器代理</h4>
google 有一套 WEB 应用程序引擎 Google App Engine（GAE），这套引擎部署在 google 位于美国的服务器上，全球任何开发人员可以向 google 免费申请在该引擎上部署自己的应用。本来，这就一普通的开放服务而已，但是，在天朝这种网络环境下，思维发散的程序员发现：GAE 位于美国服务器上，程序员能在 GAE 上部署服务端程序，如果服务端能接收客户端发送过去的网页访问请求，那完全可以让服务端作为一个中转站，借助美国运营商进行域名解析（绕开朝内运营商），一旦获取网页数据后再传回给客户端。所以，goagent 诞生。

goagent 让 google 成为你的代理，高速且稳定访问所有被墙网站绝不是问题。当然，goagent 使用前提是能正常访问 google，前面介绍的 SmartHosts 已解决该问题，下面重点讲解。

在进行具体操作前，先定义几个对象。goagent 包括客户端程序和服务端程序两部分，客户端程序简称为 GCP（goagent-client-programme），服务端程序简称为 GSP（goagent-server-programme），浏览器简称为 FF（firefox），墙外目标网站简称为 dest。goagent 实现的代理逻辑大致如下：FF 发起墙外 dest 网页访问请求，为绕开国内电信运营商，FF 走代理模式，将请求发至 GCP（127.0.0.1:8087），GCP 将请求转至 GSP，GSP 按 GCP 指示访问网站 dest，由于 GSP 位于美国，所以 GSP 可以顺畅地获取 dest 网页，一旦 dest 网页被 GSP 获取完整，GSP 立即传回给 GCP，GCP 再传给 FF，最终在 FF 中显示出完整页面。

完整过程需要九步，如果你觉得麻烦，好吧，作为牙医界的男性服务人员，我为动手能力相对较弱的朋友准备了一份开箱即用的 goagent，前往 https://github.com/yangyangwithgnu/goagent_out_of_box_yang 下载即可，用它你可以直接跳至第七步，真的不用谢，“关怀小白，随处是爱”。只要时间允许，我会尽可能把这份开箱即用的 goagent 同步至最新原版。如果你想自己动手，具体操作步骤如下（提醒你，务必在前面实现的已翻墙环境中进行）：

第一步，申请 GAE 空间，部属 goagent 服务端程序。用 google 帐号登录 http://appengine.google.com ，前面步骤按提示填写，直到填写短信验证码步骤，朝内三家运营商都屏蔽了 google 的短信，你只能通过向 google 提交在线表单，请工作人员将验证码通过邮件发给你，访问 http://appengine.google.com/waitlist/sms_issues ，表单填写内容大致如下：
>hi,  
>my mobile phone can not receive sms for verification code! plz send the code to yangyangwithgnu@yeah.net. thx man~

2 小时 8 分 16 秒后收到回复：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/GAE%E7%94%B3%E8%AF%B7%E5%9B%9E%E5%A4%8D.png" alt=""/><br>
（GAE 申请回复）
</div>
昏，还验证个啥，工作人员直接就将 GAE 使用权分配给我了（太给力了，效率啊）；

第三步，创建 APP。用 GAE 帐号登陆 http://appengine.google.com/ ，点击 create application 按钮创建 APP，APP 名按自己喜好设定（如，yangyanggnu0、yangyanggnu1），若要创建多个 APP（最多 25 个），重复本步骤；

第四步，下载 goagent（https://github.com/goagent/goagent ）。解压到 goagent/。goagent/ 包含 local/ 和 server/ 两个子目录，local/ 存放有平时运行本地代理转发的客户端代码，server/ 为需要用你 google 帐号上传至 GAE 的服务端代码。

第五步，上传服务端程序至 GAE。由于 goagent 被广泛用于翻墙，GFW 加强了对其干扰，手段之一就是阻碍 goagent 的服务端程序上传，所以，要么你在 VPN 全局翻墙的环境下上传，要么在 goagent 客户端程序的护航下上传。前者清晰易懂，后者你需要在上传前确保客户端持续运行，执行

```
python goagent/local/proxy.py
```

然后新开一个虚拟终端执行：

```
python goagent/server/uploader.py
```

整个过程耗时 1 分钟左右，如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E4%B8%8A%E4%BC%A0%20goagent%20%E6%9C%8D%E5%8A%A1%E7%AB%AF%E7%A8%8B%E5%BA%8F%E8%87%B3%20GAE.gif" alt=""/><br>
（上传 goagent 服务端程序至 GAE）
</div>

第六步，修改配置信息。既然是将 goagent 当作你自己开发的源码上传至 GAE，那么所有的 appid 都应替换成注册 GAE 时所写的应用程序名，例如，我注册时应用程序名设定的是 yangyanggnu0 和 yangyanggnu1，那么需要将 goagent/local/proxy.ini 文件中的 appid = 改写为 yangyanggnu0|yangyanggnu1；另外，设置 obfuscate = 1 开启流量混淆以正确解析出可用 GGC IP；PAC 存在漏洞，把 [pac] 下的 enable = 0 禁止 PAC 以封堵该漏洞；

第七步，设置浏览器代理地址。goagent/local/proxy.ini 文件中配置的监听 IP 为 127.0.0.1、端口为 8087，该信息表明，要走 goagent 代理，应将浏览器 firefox 的所有网站访问请求发至 127.0.0.1:8087，那么，在 goagent 客户端程序 goagent/local/proxy.py 作用下，网页访问请求将通过 google 服务器代理访问。firefox 可通过 edit -> preferences -> advanced -> network -> connection -> settings 设置代理服务器地址为 127.0.0.1，端口为 8087，重启 firefox 即可生效。

第八步，翻墙出城。至此，只要运行 goagent 的客户端程序 proxy.py，那么 firefox 的所有访问均通过 google 代理访问。goagent 有如下依赖，请逐一安装：python2、python-gevent、python-greenlet、python-vte、python-pyopenssl、python-pycrypto、mozilla-nss-tools。进入 proxy.py 所在目录，执行

```
python google_appengine/goagent/local/proxy.py
```

将出现如下输出：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%89%A7%E8%A1%8Cgoagent%E6%9C%AC%E5%9C%B0%E4%BB%A3%E7%90%86%E7%A8%8B%E5%BA%8F.png" alt=""/><br>
（执行 goagent 客户端程序）
</div>
接着，尝试用 firefox 访问墙外的 youtube.com，你会看到代理程序努力从 google 服务器上获取代理数据，如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E4%BB%8Egoogle%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E8%8E%B7%E5%8F%96%E4%BB%A3%E7%90%86%E6%95%B0%E6%8D%AE.png" alt=""/><br>
（从 google 服务器上获取代理数据）
</div>
回头看看 firefox，咿～～，怎么会出现如下错误提示呢：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%9C%AA%E5%AF%BC%E5%85%A5%E8%AF%81%E4%B9%A6.png" alt=""/><br>
（未导入证书）
</div>
别担心，代理本身是成功的，这个错误是因未将 youtube.com 安全证书导入 firefox 所致。在 firefox 中，依次 进入 edit -> preferences -> advanced -> encryption -> view certificates -> authorities -> import，选择证书 goagent/local/CA.crt，在确认对话框中勾选 websites、email users、software developers 等三类信任，重启 firefox 后，再访问 youtube.com 看看，呵呵，久违的 youtube.com 是不是又回来啦：）
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/youtube.png" alt=""/><br>
（youtube）
</div>

每次启动 goagent 后，你需要耐心等待一两分钟，才可正常使用 goagent 的代理服务。你知道，作为门槛最低的翻墙工具，goagent 普及度越来越高，这肯定会引来 GFW 的重点关注。前面提过，goagent 要正常使用得有个前提，运行 goagent 的客户端必须能访问 GAE，那么，GFW 要让 goagent 失效最简单的办法就是封锁所有连接 GAE 的请求。道高一尺、魔高一丈，goagent 相应改变策略，不再直连 GAE，而是先连入 GGC，通过 GGC 再接入 GAE，所以，goagent 查找可用 GGC 是能否成功翻墙的关键。简单科普下 GGC，google 是一家面向全球用户的公司，数据中心在美国，要想让各国用户高效享受到 google 提供的各项服务，最直接的办法是在各地建立当地的数据（或者服务）镜像，这就是所谓的 Google Global Cache，即 GGC，在逻辑上，类似 CDN。每次启动 goagent 后，你应该通过 goagent 先访问某个网页（很可能浏览器上无反馈，不影响），以便让其尽早搜寻可用 GGC 的 IP，一旦输出信息中的 good_ipaddrs 大于 0 时，则说明 goagent 成功搜寻到可用 IP。这就是你得等待片刻才能成功翻墙的原因。

goagent 对证书安装成功与否的识别有小 bug，已安装成功却识别为失败，所以，在你启动 goagent 时会提示“install root certificate failed, Please run as administrator/root/sudo”，你可以安全忽略该警告信息，不影响使用。如果有洁癖，可以手工如下安装：

```
rm -rf ~/.pki
mkdir -p ~/.pki/nssdb
# 安装时提示输入两次密码，直接两次回车，无需设置密码
certutil -d ~/.pki/nssdb -N
```
重启 goagent 后该警告消失。

对了，你可能发现访问 google 子域名有异常，这是因为 goagent 让所有 google 及其子域名默认不走代理。前面说过，goagent 生效的前提是客户端能正常访问google 服务器，理论上，访问 google.com 及其所有子域名都用不着走代理，即便在代理模式下，访问呢 google 子域名时 goagent 也根本不介入。但是，如果我又想通过代理访问某个 google 子域名怎么办？比如，想买 nexus 4，即便你开了 goagent，访问 play.google.com 会得到如下提示“Sorry! Devices on Google Play is not available in your country yet...”。前面提过，goagent 客户端程序的配置文件 goagent/local/proxy.ini，该文件中有两个 withgae 字段，该字段就是用于圈定那些强制走代理模式的 google 子域名。换言之，该字段指定那些属于 google.com但又强制走代理的子域名。在 proxy.ini 中所有 withgae 字段尾部追加 play.google.com 子域名，用 | 分割，即，...|play.google.com，保存 proxy.ini 后，重新运行 goagent 即可访问 play.google.com，如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/Nexus%204%20(16GB)%20-%20Google%20Play.png" alt=""/><br>
（Nexus 4 (16GB) - Google Play）
</div>

第九步，代理快速启停。上一步说过，到此我们所有网站访问请求都通过了 google 代理，这对那些没有被墙的网站访问场景来说未免多余，如果有个工具能实现当访问墙内网站时直接访问、访问墙外网站时走代理，那这个世界将变得更美好。想起前面讲 firefox 插件时提到的 autoproxy 么？对，autoproxy 就具备这种自适应代理的能力，请先自行下载安装 autoproxy，装好后，autoproxy 将以一个“福”字出现在 firefox 右上角，该插件屏蔽 firefox 自身的代理设置界面。首先，进入配置界面 proxy rule -> add rule subscription，选择 gfwList (P.R.China)，该文件中存放了部分加密后的被 +- 屏蔽的网址，以后，凡是在这个列表中的走代理，不在的直接访问；接着，进入 proxy server -> edit proxy server -> add proxy server，添加代理 goagent、IP 为 127.0.0.1、端口为 8087、协议 HTTP，重启firefox；最后，进入 proxy server -> edit proxy server -> choose proxy server，default proxy 选择 goagent、subscription 选择 gfwList (P.R.China)、when no matching 选择 no proxy。

autoproxy 有三种模式，自适应模式（红色图标）、强制代理模式（绿色图标）、无代理模式（灰色图标）。自适应模式，就是我刚才说的，位于 gfwList (P.R.China) 中的网址走代理，不在其中的直接访问；强制代理模式，不管墙内墙外，访问所有网站均通过代理；无代理模式，就是不走代理全直接访问。由于 gfwList (P.R.China) 中记录的被墙网站数量有限，如果用自适应模式，那么大量不在此列表中的被墙网站你实际上用的无代理模式，肯定无法访问，所以，一般而言，优选强制代理模式。

小结下，第一次可能麻烦点，如果以上九步都成功，那么你需要的免费、高速、稳定的梯子就已经制作完成。你只需保留 goagent 的 local/ 目录，其他可安全删除，平时，需要翻墙，只需到 goagent/local/ 目录下执行

```
python proxy.py
```
即可，或者直接将其加入自启动项 /etc/rc.d/after.local 中：

```
python /data/misc/software/app/goagent/local/proxy.py&
```
其中，最后的 & 很重要，让该命令后台执行，如果不加上，很可能导致你无法登录图像环境。

goagent 是 GAE 的上层产物，为更好地使用 goagent，所以 GAE 的某些属性我们应当有所了解。GAE 分收费版和免费版，我们使用的免费版，自然有些限制：一个 google 帐号对应一个 GAE 使用权，一个 GAE 使用权可以创建最多 25 个 APP；流量方面，每个 APP 每天 1GB、每分钟 56MB；URL 请求方面，每个 APP 每天 657000 次、每分钟 3000 次。一旦的某个 APP 超过以上配额，该 APP 后续请求均将失败，直到当日太平洋时间 0 点（北京时间 15:00） GAE 自动重置后方可恢复。以上配额一般情况下是够用的，如果的确有更多访问需求（如，youtube 粉），可以创建多个 APP，每多创建一个 APP 则多获取一份配额，同时，你需要重新执行第五步将 goagent 服务端程序上传至新增 APP 中，然后执行第六步将新增 APP 名添加进 proxy.ini 中，用 | 将多个应用分割开，类似这样 yangyanggnu0|yangyanggnu1|yangyanggnu2|yangyanggnu3。你可以登录 https://appengine.google.com 查看各 APP 流量使用详细情况。

至此，goagent 优雅地解决了浏览器翻墙的问题，但，这只达到我总预期的 70%。对于绝大部分人来说，这已足够了，我，的确很难归属到“绝大部分人”中。某些论坛，你得先注册后才能访问帖子内容，为防机器人，同个 IP 短时间内禁止重复注册，由于 goagent 的低使用门槛，我天朝用它翻墙的用户不少，所有用户的出口 IP 均为 GAE 集群的 IP，难免短时间内多个用户通过 goagent 在同个论坛中进行注册，这时，其他 goagent 用户再去注册将被视为“同个 IP 短时间内禁止重复注册”；另外，+- 会隔三岔五干扰下，goagent 难免间歇性罢工，所以，我需要一种与 goagent 互备的代理。

<h4 name="3.2.4">3.2.4 shadowsocks 代理</h4>
前面介绍的 goagent 只支持 HTTP(S) 协议代理，并不支持 socket 协议，shadowsocks，支持 socks5 的代理工具。shadowsocks 用 python 编写开发，非常轻量级，仅依赖库 python-M2Crypto 和 python-setuptools 两个库。你需要用 python 自己的包管理工具 python-pip 来安装 shadowsocks，执行

```
pip install shadowsocks
```
完成 shadowsocks 的安装。

安装完后，系统中多客户端 sslocal 和服务端 ssserver 两个程序，后者用于部署 shadowsocks 代理服务器对外提供代理服务，这里不关注。前面提过，代理，实际上需要一个代理服务器，同个它进行访问请求的中转，shadowsocks 也不例外，要成功连接代理服务器，必须传递如下信息至服务器：

* "server"，服务器名称
* "server_port"，服务端监听端口
* "local_address"，本地中转地址，通常为 127.0.0.1
* "local_port"，本地监听端口，通常为 1080
* "password"，接入服务端密码
* "timeout"，以秒为单位的连接超时时长
* "method"，加密方式，通常为 aes-256-cfb
* "fast_open"，是否开启 TCP_FASTOPEN 以减少延迟，通常为 false
* "workers"，工作线程数量，通常为 1 

以上信息保存至 \*.json 证书文件中。如下是一 \*.json 证书文件示例（含前后大括弧），取名 1080.json：

```
{ 
    "server": "31.220.50.8", 
    "server_port": 36580, 
    "local_address": "127.0.0.1",
    "local_port": 1080, 
    "password": "goagent", 
    "timeout": 512, 
    "method": "aes-256-cfb", 
    "fast_open": false, 
    "workers": 1 
}
```
接下来，运行客户端程序

```
sslocal -c 1080.json
```
将成功连接代理服务器。到这步，shadowsocks 还无法为你提供代理服务。前面介绍 goagent 时提过用 autoproxy 设置 firefox 浏览器本地中转地址及端口，同理，shadowsocks 也需要用 autoproxy 设置自己的本地中转地址及端口，通常本地中转地址为 127.0.0.1、端口为你 \*.json 文件中 local_port 字段指定的值、协议类型为 socks5，如下图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E8%AE%BE%E7%BD%AE%20shadowsocks%20%E6%9C%AC%E5%9C%B0%E4%B8%AD%E8%BD%AC%E5%9C%B0%E5%9D%80.png" alt=""/><br />
（设置 shadowsocks 本地中转地址）
</div>
这时，在 autoproxy 中可使用 goagent 和 shadowsocks 两种代理：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E9%80%89%E7%94%A8%20shadowsocks%20%E4%BB%A3%E7%90%86.gif" alt=""/><br />
（选用 shadowsocks 代理）
</div>  

现在，你肯定关注如何获取 shadowsocks 免费证书。我为你准备了几个网站：http://www.v2ex.com/go/shadowsocks 、http://www.fyhqy.com/356/ 、http://www.ssh91.com/freessh.html 、http://ssnode.com （需邀请码）、http://ss.cevin.me （需邀请码）、http://user.ss-vpn.com （需邀请码）、 https://cattt.com/index.php （需邀请码）、https://heidong.in/ （需邀请码）、http://boafanx.tabboa.com/boafanx-ss/ ，感谢他们。一方面为留住访问量，一方面避免流量滥用，通常，这些公益网站会定期更新免费帐号的 server_port 和 password 信息，导致我在用的 SS 帐号时不时失效，我又不得不登录这些网站重新获取新帐号，真是麻烦。好吧，我，作为一个发育成熟的成年男性懒人，不能再这样过下去了，所以，基本上，我需要一个自动化工具，它得帮我做几件事：0）从各网站搜集 SS 帐号并测试帐号的可用性、代理出口所在区域、代理网速；1）将可用帐号转换成 sslocal 的命令行选项并输出至屏幕，让我复制后可直接运行；2）将可用帐号转保存成 sslocal 的 \*.json 证书文件。所以，我写了个程序 autoshadower，你可以从 https://github.com/yangyangwithgnu/autoshadower 获取。你可以不带任何命令行选项直接运行：  
```
$ autoshadower
```
autoshadower 为你测试它能获取的帐号是否可用，若可用它会在屏幕上输出 sslocal 的命令行选项，你直接复制运行即可，类似  
>
    \(^o^)/. this SS certificate available. now you can issue SS proxy as follow:
    sslocal -s "la11.wfg.pw" -p 47265 -k "efmoe.panny" -b "127.0.0.1" -l 1080 -m "AES-128-CFB" -t 512
>

你将第二行复制粘贴至命令行中运行即可：

```
$ sslocal -s "la11.wfg.pw" -p 47265 -k "efmoe.panny" -b "127.0.0.1" -l 1080 -m "AES-128-CFB" -t 512
```
或者，采用 autoshadower 为你生成的证书文件：

```
$ sslocal -c ~/1080.json
```
同理，要想测试帐号的速度，--mode 指定为 s 即可。简单得很。

```
$ autoshadower --mode s --path ~/downloads
```
如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/autoshadower%20%E8%87%AA%E5%8A%A8%E8%8E%B7%E5%8F%96%20SS%20%E5%B8%90%E5%8F%B7.gif" alt=""/><br />
（autoshadower 自动获取 SS 帐号）
</div>  

怎么样，shadowsocks 代理还不错吧。shadowsocks 还有个特性，多路代理，你可以同时连接多个代理服务器。前面样例中我把本地中转地址的端口 local\_port 设置为 1080，你完全可以用 autoshadower 生成的多个 SS 帐号（如，一个美国的、德国、法国、香港），每个帐号对应一个 \*.json 文件（如，1080_us.json、1081_de.json、1082_fr.json、1083_hk.json），文件中的本地中转地址的端口 local_port 分别设置为 1080、1081、1082、1083，然后再在 autoproxy 中设定四个本地中转，这样你就可以按需要使用不同的代理了。

shadowsocks 与 goagent 互补，至此，达到我总预期的 80%。但它俩只能让我翻墙看看网页，仅此而已，无法让浏览器之外的软件翻墙。比如，Cygwin，一套用于将 linux 软件移至到 Windows 下的开发环境，在安装 Cygwin 时，它会自动联网下载环境中必须的头文件、编译器等等资源，而这些资源存放在墙外服务器上，Cygwin 又无法通过 HTTP 协议访问墙外资源，所以资源下载失败。换言之，shadowsocks 和 goagent 实现的翻墙并非全局性的。我需要支持整个系统的全局代理。

<h4 name="3.2.5">3.2.5 VPN 代理</h4>
要实现整个系统的全局代理，你需要更生猛的翻墙利器 —— VPN。VPN（Virtual Private Network），初衷是为在外出差员工使用内网资源，虽然物理上是异构网络环境，但通过 VPN 虚拟成同一网络环境。为保障数据安全，VPN 服务端必须要有客户端发来的证书认证通过后才能进行数据交换，并且数据流全是加密传输，这一过程的副作用可以用于翻墙。

VPN 协议有三种实现：PPTP、L2TP/IPsec、OpenVPN ，安全性最强（数字证书两端双向认证、256 位不可逆加密交换数据）、支持面最广（linux、BSD、OS X、WINDOWS、Android、iOS）、稳定性最高（完全无视防火墙的各类限制）当属  OpenVPN。可以在 http://openvpn.net/index.php/open-source/downloads.html （无法访问？用前面的 goagent 翻墙啊，多好的实践机会）下载最新版本 openVPN 源码（Android、iOS 版本请到各自 APP store 中搜索下载），源码安装、重启，系统中多出一个虚拟网卡设备，一旦运行 openvpn 程序，它会自动修改你系统的路由表，让所有网络数据请求优先走虚拟网卡，这就达到实现了全局代理的目的。现在，你需要找 VPN 服务提供商获取数字证书。嗨嗨嗨嗨，别走啊，免费的在这儿 http://www.vpngate.net/en ，这里有全球各大非盈利机构开放给大家使用的免费 VPN 服务器，根据不同国家、不同带宽、不同性能你可以按需选用，或者 http://www.vpnbook.com/freevpn 也不错。VPN 的三种不同实现使用的证书不用，我们用的 openVPN 对应该网页上的 OpenVPN Config file 链接，进入后你将看到域名证书和 IP 证书两类证书，每类内部又分使用 UDP 和 TCP 两种子类，换言之，一个采用 openVPN 协议的 VPN 服务器共有四个证书，一般来说，你应选用 TCP 的 IP 证书。比如，我选用位于日本、IP 为 84.210.204.5 的机器，点击该行 OpenVPN Config file 链接进入证书下载页面，找到类似 OpenVPN Configuration File: 84.210.204.5 (TCP 995) 的链接点击即可下载得到 vpngate_84.210.204.5_tcp_995.ovpn 数字证书文件：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/openVPN%20%E8%AF%81%E4%B9%A6%E7%B1%BB%E5%9E%8B.png" alt=""/><br>
（openVPN 证书类型）
</div>
接着运行

```
openvpn vpngate_84.210.204.5_tcp_995.ovpn
```
进行 VPN 连接，出现 Initialization Sequence Completed 说明认证完成，OK，找个 IP 查询的网站（ip38.com）确认下访问 IP 是否变成日本的了。如果发现网站无法访问，或者网速太慢，可以换用其他 VPN 服务器试试。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/openVPN%20%E5%AE%9E%E7%8E%B0%E6%95%B4%E4%B8%AA%E7%B3%BB%E7%BB%9F%E5%85%A8%E5%B1%80%E4%BB%A3%E7%90%86.gif" alt=""/><br>
（openVPN 实现整个系统全局代理）
</div>  

openVPN 方式，加之前面的 google 服务器代理方式 和 shadowsocks 代理，解决了我 95% 的问题。openVPN 解决了 goagent 无法实现系统全局代理的问题，但还是有几个问题：问题一，http://www.vpngate.net/en 上的公共免费 VPN 经常失效，需要我重新下载新的证书，挺麻烦；问题二，这些公共免费 VPN 任何人可能轻易获取，有些按区域进行版权保护的网站会主动屏蔽从这些公共 VPN 发起的请求（这事儿跟天朝的 GFW 没关系），比如 YouTube 上的 music 频道，只能特定地域的 IP 才能观赏，从这些公共 VPN 发起的视频访问请求均被忽略。针对问题一，没什么说的，失效了又去下载新的；针对问题二，说白了，就是 shadowsocks 和 google 服务器代理两类方式完全无法设定以某个指定国家或者地区的 IP 作为代理出口 IP，VPN 代理方式相对好一点，http://www.vpngate.net/en 多少有 20 多个国家可供选择，但仍然缺乏弹性，比如，无法选用台湾、马来西亚、瑞典的代理出口 IP。再举个例，百度音乐上的所有歌曲都是区域版权保护的（仅限大陆用户），留学国外的朋友想要听歌就悲摧了，必须得找个国内 IP，从墙外翻墙内，goagent 使用的是 google 在美国的服务器，用 goagent 肯定没戏，openVPN 可用的公共 VPN 又没有国内的。我需要可以随意指定出口 IP 的代理方式。

<h4 name="3.2.6">3.2.6 地下网络代理</h4>
前面介绍的几种代理方式，都有个共同的特点：第三方先贡献出一台墙外服务器，然后允许你以该服务器作为出口，访问目标网页，出口服务器在获取完整目标网页后再传回给本地。goagent 的出口服务器是 google 的 GAE 引擎所在服务器、shadowsocks 和 openVPN 的出口服务器是各大机构免费开放的 VPN 服务器，由此可见，这些出口服务器是实现翻墙的关键。

有报道称，接入互联网的 PC 数已达 13 亿，分布在全球各地，如果，我说如果，有某种机制，一旦建立相互信任关系后，位于墙外的 PC1 能允许墙内 PC2 将自己作为出口服务器进行目标网页访问，那也是可以实现翻墙，若是可行，13 亿台 PC，你只需选择希望的国家或地区的那台 PC 建立信任，随意指定出口 IP 的代理方案完全可以落地。tor 诞生。 

顶级黑客为保证自身安全，对网络匿名访问有非常高的要求，通常：他们先在自己的 PC 上安装虚拟机，然后虚拟机中通过 VPN 代理进入 tor 的地下网络，最后从 tor 的出口中继节点发起网络访问。这样一层套一层的方式，实现绝对匿名访问。tor 项目初衷是为用户创建一套高度匿名网络访问的服务，任何国家、任何计算机设备均可加入将自己设置为一个中继节点，所有中继节点形成了一张巨大的地下网络，你的任何网络访问请求，均可通过这张地下网络多次中转，实现不可回溯的匿名访问，由于这个地下网络中的节点数目非常庞大，用户可以自由选用任何地区的 IP 进行网络访问。接入地下网络前，tor 会让你先连接上索引服务器，由于地下网络中的中继节点数量非常多，所以必须通过索引服务器查找应该连接哪些节点；一旦连接上索引服务器，它将为你分配三个中继节点，入口中继、中转中继、出口中继，这三个中继组成一条地下网络访问路径，你的网络访问请求路径变成客户端-入口中继-中转中继-出口中继-目标网站，回到我们引入地下网络代理的背景，如何指定任意国家的 IP 进行代理访问？这看似不可能实现的任务，在 tor 中易如反掌，只需手工指定路径中的出口中继节点指定为你需要的区域即可。下面我们看下具体操作。

第一步，下载并安装 tor、vidalia。tor 是命令行工具，那些被 windows 毒害的用户患有命令行恐惧症，为解救他们，开发人员在 tor 外开发了一套图形界面的壳 vidalia，通过 vidalia 可在图形界面下操纵 tor。你可以在 http://www.torproject.org/dist （墙外）找到最新版的 tor 和 vidalia 源码，下载后分别源码安装；

第二步，指定出口中继节点。重点来了，我们引入 tor 地下网络的目的是想实现按自己意愿指定某个国家的 IP 作为访问代理，只要正确配置即可。tor 的配置文件，若是源码安装的，则为 /usr/local/etc/tor/torrc，若从预编译包中安装，则为 /etc/tor/torrc 或 /etc/torrc，vidalia 的配置文件为 /root/.vidalia/torrc。我们以 tor 为例，看看两种指定出口 IP 的方式。

* 方式一，按国家代码进行指定，在 tor 配置文件中增加如下信息：

```
# 按国家指定出口中继节点 
ExitNodes {MY} 
# 严格按 ExitNodes 设定选用出口中继，即便没有可用中继导致创建地下网络路径失败也要严格选用 
StrictNodes 1
```
其中，我希望出口 IP 位于马来西亚，所以在 {} 设定为 MY，你可以换成任何你希望的国家或地区，比如想要台湾 IP，可以设定为 TW，完整国家代码参见 http://zh.wikipedia.org/wiki/%E5%9C%8B%E5%AE%B6%E5%9C%B0%E5%8D%80%E4%BB%A3%E7%A2%BC 。

* 方式二，按节点名进行指定，在 tor 配置文件中增加如下信息：

```
# 按节点名进行指定 
ExitNodes voxility,axigy1
# 严格按 ExitNodes 设定选用出口中继，即便没有可用中继导致创建地下网络路径失败也要严格选用 
StrictNodes 1
```
其中，我希望出口 IP 位于罗马尼亚，所有选用 voxility 这个位于罗马尼亚的出口中继节点名，你可以在 http://www.torservers.net/exits.html 找到当前各国在线的节点名，按需选用，你也可以指定多个出口节点名，用 , 分割，形成候选列表，避免单个节点故障影响你的使用。

关于出口节点的选择，你一定要谨慎！不见得进入地下网络就一定安全。天朝虽无法绝对封锁 tor 的地下网络，但可以把自己隐藏到地下网络中，伪装成一个普通中继节点，这就是所谓的“蜜罐”。另外，除了天朝外还有些社会主义国家也有他们自己的 GFW，比如伊朗、叙利亚、朝鲜等等，如果，你把朝鲜选作出口节点，很好，费了九牛二虎之力翻到墙外，你会发现更多网站无法访问了，就好像你挖条地道越狱，好不容易挖通了，却发现是在隔壁监狱 @\_@！因此，你需要告诉 tor 切勿选用这些国家的中继节点：

```
# 禁用以下国家的中继节点
ExcludeNodes {IR},{SY},{KP},{CN},{MO},{HK}
```

第三步，设置浏览器让其通过地下路径进行网络访问。前面介绍 goagent 时我们已经设置过浏览器，让浏览器走 goagent 代理模式，这里的设置与前面差不多，点击插件 autoproxy，进入 preferences -> proxy server -> edit proxy server -> add proxy server，添加代理名 tor、IP 为 127.0.0.1、端口为 9050、协议 socks4，保存后重启 firefox，这时你在 autoproxy 中可以看到两个可选代理，见下图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%9C%A8%20firefox%20%E4%B8%AD%E5%A2%9E%E5%8A%A0%20tor%20%E4%BB%A3%E7%90%86%E6%A8%A1%E5%BC%8F.gif" alt=""/><br>
（在 firefox 中增加 tor 代理模式）
</div>

第四步，进入地下网络。tor 威力太大，近年被 GFW 彻底封杀，你用普通方式是无法接入索引服务器，必须借助所谓的前置代理。顾名思义，前置代理，指你系统中先得有某种可用的代理，以此代理作为前置跳板，绕开 GFW 再连接至 tor 的索引服务器。只有 socket 或者真正的 HTTPS 代理才能作为前置代理，所以，前面介绍的 goagent 是不满足的（它是 HTTP 代理），而 shadowsocks、VPN 以及 tor 的网桥是满足的（她们都是 socket 类型代理）。接下来，我们从后往前依次验证哪种方式最适合成为 tor 的前置代理。

**首先，尝试通过网桥进入地下网络**。何为网桥？按普通逻辑，第一步，客户端先接入 tor 的节点索引服务器，第二步，节点索引服务器按客户端配置选择三个满足要求的节点，第三步，客户端通过由这三个节点组成的地下网络路径进行匿名代理访问；现在由于 GFW 的干扰，第一步失败，这时，自然会有种思路，先别管我客户端配置说要求哪种类型的三个节点了，你先随便给我个能用的节点，好让我借助该节点连接进索引服务器再说后面的事儿，这个节点，就是网桥。地下网络中的普通中继节点是以公共形式存放在索引服务器上，网桥实际上是种私有中继节点，也就是说，你先用私有中继节点（即网桥）接入索引服务器，接着获取地下网络三个节点的网络路径，然后抛弃私有中继、采用地下网络路径进行访问。目前有两种获取网桥的方法。方法一，直接去官网获取 http://bridges.torproject.org/bridges ，简单得很，输入验证码即可获取网桥，好吧，我承认，这是我见过最复杂的验证码，你可以把网页放大到最大程度，或许你可以看清；方法二，用你的 google 邮箱给 bridges@torproject.org 写封邮件，主题和正文都为 get bridges，且正文必须是纯文本（你的邮件签名应该禁止掉），几分钟后将收到 tor 项目组自动反馈的邮件，内容正是你需要的网桥，类似：

```
88.83.241.14:9001 e040f24bfdd1e4aab4fed15db47d8c22dfac454d 
```
其中，三部分依次为网桥的 IP、网桥的端口、网桥的指纹。有了网桥，你需要将其添加进 tor 的配置文件中：

```
# 使用网桥
UseBridges 1
# 设置网桥
Bridge 88.83.241.14:9001 e040f24bfdd1e4aab4fed15db47d8c22dfac454d  
```
这时，你可以先尝试下能否接入索引服务器，命令行执行：

```
tor
```
如果长时间停留在 Bootstrapped 5%: Connecting to directory server，那么说明你刚获取的网桥已经被 GFW 封锁，如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E7%BD%91%E6%A1%A5%E8%BF%9E%E6%8E%A5%E5%9C%B0%E4%B8%8B%E7%BD%91%E7%BB%9C%E5%A4%B1%E8%B4%A5.gif" alt=""/><br>
（网桥连接地下网络失败）
</div>
本次尝试失败！你别惊讶，想想也正常，你能轻松获取网桥，GFW 的运维人员也能轻易获取，他们可是一群天天只干这事儿的人，新出一个网桥，他们就封锁一个。你更别妥协，我们用网桥的目的是为了接入索引服务器，通过前面几节的介绍，你已经具备 VPN 系统全局代理的能力，网桥不行咱就不用网桥，你完全可以在全局代理的环境下不用网桥接入代理服务器。

**接着，尝试通过 VPN 进入地下网络**。先把上一步添加的网桥信息全部注释掉，然后执行 openVPN 建立系统全局代理环境，最后执行 tor 进入地下网络。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/VPN%20%E8%BF%9E%E6%8E%A5%E5%9C%B0%E4%B8%8B%E7%BD%91%E7%BB%9C%E6%88%90%E5%8A%9F.gif" alt=""/><br>
（VPN 连接地下网络成功）
</div>
本次尝试成功！由入口、中转、出口三个节点组成地下网络访问路径就创建好了，为确保绝对安全，tor 周期性变更路径中的三个节点，也就是说，这个时段是 node1-node2-node3 组成的路径，下个时段则变成 node11-node22-node33，达到访问不可回溯的目的。

**最后，尝试通过 shadowsocks 进入地下网络**。假定你的 SS 本地中转地址为 127.0.0.1:1080，在 tor 的配置文件 /etc/tor/torrc 中增加：

```
# SS 作为前置代理
Socks5Proxy 127.0.0.1:1080
```
这样，SS 便成为了 tor 的前置代理，先运行 SS 再运行 tor，如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/SS%20%E4%BD%9C%20tor%20%E5%89%8D%E7%BD%AE%E4%BB%A3%E7%90%86.gif" alt=""/><br>
（SS 作 tor 前置代理）
</div>
本次尝试成功！注意，SS 前置代理应持续保持连接，否在 tor 将中断。

综上，网桥方式完全行不通；近期 GFW 对 VPN 封锁加剧，找到免费可用的 VPN 非常困难；SS 方式速度快、免费资源多，优先选用。

经过以上四步设置，以后，你要想进入地下网络，先运行 SS 创建 socket 代理环境，再以 SS 为前置代理运行 tor 进入地下网络，最后设置 autoproxy 走 tor 地下网络路径，搞定！你可以访问 http://check.torproject.org 以确认是否通过地下网络访问。

<h4 name="3.2.7">3.2.7 个人专属代理</h4>
前面介绍的各类代理有个通病，代理出口带宽是你和其他人共用的，比如，goagent，你和其他人共用 GAE 提供的代理；openVPN，共用 vpngate.net 的代理；shadowsocks，共用那些免费 SS 提供商给出的代理；tor，相对好些，你可以按不同区域选择代理。总的来说，我需要只为我一个人提供代理的机制。这个需求，goagent 和 shadowsocks 都可实现，shadowsocks 对环境要求苛刻些，所以，以 goagent 为例讲解。

回忆下前面介绍 goagent 章节，goagent 分为 local/ 和 server/ 两部分，当时我们把 server/ 上传至 GAE，通过 local/ 与 server/ 数据交互让 GAE 成为代理机实现翻墙。由此可见，goagent 能翻墙成功的关键是朝内暂时还可以访问 GAE，如果那天 GFW 把访问 GAE 的网络封锁了，那 goagent 将失效。

逻辑上来说，server/ 可以上传至任何服务器，只有那台服务器未被墙且具备 server/ 运行环境，那么，在 goagent 作用下，该非 GAE 服务器也可以成为我提供的代理服务，这就是所谓的 non-GAE 模式。为此，在 GFW 这堵墙越建越高的未来，goagent 作者建议，non-GAE 模式是 goagent 的使用趋势。

首要任务，申请合适的免费空间。空间必须满足两个条件，一是提供 PHP 以支持 goagent 的 server 正常运行，一是未被 GFW 封锁以实现数据交互。推荐 http://www.ecvps.com 、http://www.hostinger.com.hk 、http://nazuka.net 、http://binhoster.com 、http://www.1freehosting.com 、http://www.dhmart.info 几个，优选 ecvps.com。ecvps.com 有如下承诺：
>20GB Diskspace  
>Unlimited Bandwidth  
>Support PHP, MYSQL  
>Zend Optimizer  
>Torrents, Proxy, Adult allowed!  
>Kansas City Datacenter ( USA Located )  
>No ADS  
>1000Mbps Internet Connection  
>Directadmin ( control panel )  
>Instant Activation  
>Remove Account if no bandwidth using for 7 days  

简直是霸气侧漏，不限带宽、提供 PHP 和 mysql、允许代理、绝无广告、立即激活。唯一限制是连续 7 天无流量将删帐号。无需代理直接访问 http://www.ecvps.com/freehosting/ ，点击 order now 后在 Use a subdomain from EcVps 中填写二级域名（如，yangyangwithgnu），点击 click to continue 后填写用户注册信息，点击 complete order 完成空间申请。按理说，填完申请也就应该顺利分配空间了，但 ecvps.com 为防止恶意注册启用了反欺诈检测，如果你的信息存在虚假，将会申请失败，告知如下：
>MaxMind has deemed your order to be potentially high risk and therefore it has been held for manual review.  
>If you feel you have received this message in error, then please accept our apologies and submit a support ticket to our Customer Service Team. Thank you.  

按它提示，必须发一张申诉单请后台人员人工分配空间，申请地址 http://www.ecvps.com/client/submitticket.php?step=2&deptid=12 ，内容要尽量诚恳，比如，
>hi admin,  
>I'm a student who learning webdesign, so I hope to get a free hosting, ecvps.com is so good by word of mouth. But always "MaxMind has deemed your order to be potentially high risk" there, help me, thx.  

申诉单的紧急程度选高些，priority 选为 high。另外，一定要在工作时间内（周一到周五的 09:00 – 17:00）提交，否则，你的申请单将石沉大海。ecvps.com 承诺 20 分钟内邮件反馈，告知你后台管理地址为 https://server.ecvps.net:2222/ ， 登录用户名和默认密码，FTP 的 hostname 为 yangyangwithgnu.ecvps.net，二级域名 http://yangyangwithgnu.ecvps.net ，如果你要绑定一级域名还会用到的 Nameserver，还有 email 的 pop3 和 smtp 信息。

接着，部署 goagent 的 server 到免费空间。下载最新版 goagent（https://github.com/goagent/goagent ），在 goagent/server/php/ 下有 index.js、index.php、index.py、relay.php 等四个文件，为防止其他人盗用流量，前三个文件中均有一行设置密码的代码

```
$__password__ = '123456';
```
将其更改（如，abcdefgh）。登录后台管理地址 https://server.ecvps.net:2222/ （切勿用代理访问），点击 files 菜单可查看文件列表，在 public_html/ 下创建 goagent/ 子目录，进入该子目录后将 index.js、index.php、index.py、relay.php 四个文件上传至此。

然后，设置本地配置文件。到 goagent/local/ 将 proxy.ini 的部分默认设置如下，其他部分保持默认设置不变（英文逗号表示注释）：

```
; 同时支持 GAE 代理
[gae]
enable = 1
appid = yangyanggnu0|yangyanggnu1 ; 替换成你的 appid

; 封堵可访问任意文件的漏洞
[pac]
enable = 0

; 同时支持 non-GAE 代理
[php]
enable = 1
password = abcdefgh ; 同 index.php 中的密码一致
fetchserver = http://yangyangwithgnu.ecvps.net/goagent/index.php ; 你 index.php 文件的路径
```
其中，注释已经很清晰了，唯一提醒的，这份 proxy.ini 可以同时支持 GAE 和 non-GAE 两种模式的代理。

最后，设置浏览器本地中转代理。参照“3.2.3 google 服务器代理”章节对浏览器的设置，唯一区别是，先前的 GAE 模式监听端口为 8087，这里的 non-GAE 模式监听端口为 8088，如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/goagent%20%E7%9A%84%20non-GAE%20%E6%A8%A1%E5%BC%8F%E4%BB%A3%E7%90%86.png" alt=""/><br />
（goagent 的 non-GAE 模式代理）
</div>  

后续，运行 proxy.py 时，根据浏览器选择的不同代理，本地的单个 goagent 可以在 GAE 和 non-GAE 见随意切换。这样，你个人专属的代理就搭建完成了。

<h4 name="3.2.8">3.2.8 透明代理</h4>

回想下，firefox 能成功翻墙，除了 goagent、shadowsocks 等等代理工具大力协助外，它自身支持代理功能也是个关键，即，firefox 自身可配置将所有网络请求先转发至本地代理软件（如，shadowsocks 的 socks5://127.0.0.1:1080 ），如果某些软件自身无法配置代理，有办法让这类软件也享受翻墙功能么？

在我的使用场景中，zypper 和 git 最为常见。前者是 openSUSE 的包管理工具，应用软件增删改、系统升级、安全补丁安装等等都离不开它，虽然大部份源可以选用国内镜像，但像是 packman 这类著名第三方源至今缺少国内镜像，在 GFW 的干扰下，运气好时还能蜗速访问 packman 源，运气不好，直接无法连接；类似，github.com 是一个代码版本控制、发布管理的在线托管网站，我在客户端通过 git 与之通信，GFW 的干扰，速度也是慢得无法忍受。代理，是解决上述问题的最好（可能也是唯一）手段。遗憾的是，zypper 和 git 都不支持代理，无法设置将网络访问请求转发至 socks5://127.0.0.1:1080 。这时，你可能会先想到 openVPN 这种全局代理，没错，是个思路，我不太喜欢这种方式，一方面 GFW 对 openVPN 封锁得非常彻底，很难找到可用的证书，另一方面，全局代理强制其他无翻墙需求的软件必须走代理，影响效率。我需要更优的方案。

linux 上的任何软件，不论实现方式、开发框架、编程语言，只要有网络访问请求，最终会调用 libc 中的网络相关函数，如果有某种机制，能够发现应用程序即将调用 libc 中的网络相关函数，在调用前，先将传递给网络相关函数的实参从真正目标地址篡改成本地中转地址 socks5://127.0.0.1:1080 ，那么，逻辑上，该应用程序就间接具备了翻墙功能。这就是所谓的透明代理。透明代理，首推 proxychains（https://github.com/haad/proxychains ）。

以 shadowsocks 为例，简单配置，编辑 ~/.proxychains/proxychains.conf：  
```  
[ProxyList]
socks5 127.0.0.1 1080
```  
即可。下图为通过透明代理工具 proxychains 为不支持代理的软件 zypper 提供 shadowsocks 代理服务：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E9%80%8F%E6%98%8E%E4%BB%A3%E7%90%86%E4%BD%BF%E7%94%A8%20zypper.gif" alt=""/><br />
（透明代理使用 zypper）
</div>  
上图输出的 |D-chain|-<>-127.0.0.1:1080-<><>-195.135.221.134:80-<><>-OK 信息，说明把真实地址 195.135.221.134:80 篡改为本地中转代理地址 127.0.0.1:1080 了，从而实现代理功能。

好了，翻墙部分就这样，说得多了些。就我而言，大部分时间只要浏览器能翻墙即可，虽然以上四种方式都可达到目的，但我优选 goagent，一是毕竟使用的是 google 的服务器，机器性能、网络带宽、在线时长都较好，二是 goagent 只影响浏览器，不会强制让我其他应用程序（如下载工具）走代理；当 goagent 被干扰（如，陆四期间）不可用时，换用 shadowsocks；需要全局代理时用 openVPN；需要指定地域的出口 IP 时用 shadowsocks + tor；需要个人专属的代理就用 non-GAE 模式的 goagent；要为那些自身不支持代理的软件提供代理功能就派 proxychains 上场。


<h2 name="4">4 系统管理 </h2>
linux 系统管理是很大一个领域，有专门的一群从业者靠此养家糊口，我无法在此进行详细讲解，仅以几类常规操作抛砖引玉。

<h3 name="4.1">4.1 数据备份</h3>
随着对电脑的依赖，我们多多少少积累了些重要资料，可以说这些资料是形成我们“个人能力”的主要来源，一旦丢失，多年的工作经验、生活点滴均将化为烟云，这是我们一笔无形的财富。硬盘老化、操作系统异常、电脑遗失等等都会导致资料丢失，为避免损失，应该养成定期备份数据的习惯。

就我个人经验来看，数据备份要注意以下几点：

* 第一，存放备份的介质。数据备份，不是在电脑内置硬盘上的一个分区备份到另一个分区，否则即便有所谓的备份，一旦内置硬盘出问题，原始数据和备份数据都将挂掉。建议准备两个独立硬盘（一个 500G 移动硬盘外套硬盘盒——小盘、一个 500G 台式机硬盘外套硬盘盒——大盘）用于存放双备份数据，每次备份操作时将原始数据分别备份至这两个外置硬盘中，其中，小盘保存打包压缩后的备份数据，而大盘保存直接备份数据（未打包、未压缩）且不再用于备份之外目的（数据重要性不言而喻，我个人非常看作数据备份的，花一定成本购买两个硬盘及硬盘盒用于日常备份完全值得的，当然，仁者见仁、智者见智）；
* 第二，内置硬盘的分区。电脑内置硬盘在分区规划时，应单独创建一个文件系统，专门用于存放需要定期备份的数据（这里的几个说法容易混淆，概念澄清下，外置硬盘中用于存放备份而来数据的分区不妨称之为 backup 分区，内置硬盘中用于存放我们重要资料的需要被定期备份出去的分区称之为 data 分区）；
* 第三，其他项。A）全备，每次将所有数据资料全量备份而非仅备有差异部分（非增备）；B）直备，保持数据资料完整目录结构，直接备份到外置硬盘的 backup 分区，说白了就是直接复制，不进行任何再加工；C）先备后删，每次备份操作，应完成本次备份后再删除老备份，避免备份过程出问题导致历史备份丢失；D）异地存放，大型生产系统均有异地灾备系统，同样，我们存放备份数据的介质已应异地存放（如，个人电脑若长期放在家里，则建议把备份介质放在单位）；E）月备，数据备份的周期要视你具体数据量和数据更新频率而定，个人而言，100G 的数据量，备份耗时差不多 1 把小时，我一般每月备份一次（小提示，将工作、生活上需要定期做的事项按不同执行周期分类梳理到一张电子表格中，不时看看，你会发现，原来我是那么井井有条——引至《爱我何需理由》，作者：自恋小王子（这是笔名，真名吴凤辉 ：-）。

**打包压缩备份**

在备份软件方面，无须其他特殊软件，只要有 tar、gzip、bzip2 几个常见命令即可。下面依次以直接打包备份、打包压缩备份、打包压缩带进度备份三种方式，由浅入深介绍具体备份操作。

第一步，直接打包备份。为了保持目录结构，通过采用打包命令tar进行备份。比如，将 /data/ 目录备份到名为backup_120g的外置硬盘上，备份文件命名为 data_backup.tar，那么完整命令及参数如下：

```
tar -p -P /data -cf /media/backup_120g/data_backup.tar
```
其中，-p 表示完全保持 /data/ 目录下所有文件的文件属性，-P 表示使用绝对路径（否则 tar 忽略所有路径中的第一个 /，将其转换为相对路径，并给出警告 Removing leading `/’ from member names），-cf 表示需要创建一个备份文件且命名为 backup.tar。

数据备份的时间点往往是我们最为关心的信息，所以习惯上备份文件名应该加上时间戳。linux 的 date 命令能根据不同参数生成指定日期信息，如下命令可在备份文件名中添加备份操作发起的日期：

```
tar -p -P /data -cf /media/backup_120g/data_backup@`date +%m-%d`.tar
```
其中，包裹命令 date 的”`”符号是 tab 键正上方那个键，而非单引号。以指示 shell 优先执行整个命令行中该符号对包裹的命令（即，date +%m-%d）。

如果外置硬盘空间有限，/data/ 中又包含部分不那么重要的数据（如，临时目录 tmp、windows 虚拟机共享目录 share_folder/），那么备份时可以将这些目录排除掉，通过 tar 的 --exclude 参数即可实现：

```
tar -p -P /data --exclude=/data/misc/tmp --exclude=/data/misc/software/vm/win_7/share_folder -cf /media/backup_120g/data_backup@`date +%m-%d`.tar
```
其中，--exclude 参数语法非常特殊（其他命令中的该参数也是如此），注意几点：A）命令中的所有参数必须为绝对路径而非相对路径，且不能用 ~ 等等缩写字符；B）所有路径最后不能以 / 结尾。

第二步，打包压缩备份。如果排除了部分不重要数据后外置硬盘空间仍然紧张，可以考虑对打包文件进行压缩。linux 上常见的压缩命令包括 gzip 和 bzip2 ，由于两者采用的不同压缩算法，导致前者压缩率较低但速度较快，后者压缩率较高但速度慢，但相关用法差不多，请按需择优选用（本例以 gzip 为例，若需 bzip2 则直接替换即可）。打包和压缩是两个独立操作，写两条命令多麻烦啊！不用，借助 linux 强大的管道和重定向机制，可以在一条命令中以非常自然的方式实现：

```
tar -p -P -cf - /data --exclude='/data/misc/tmp' --exclude='/data/misc/software/vm/win_7/share_folder' | gzip > /media/backup_120g/data_backup@`date +%m-%d`.tar.gz
```
别被这些奇怪符号吓着，管道符 | 用于实现“打包一点压缩一点”，重定向符 > 用于实现“压缩一点写一点到备份文件中”，这样，串起来就是“不停打包、不停压缩、不停写文件”的流水作业，理解了吧！其中，上个命令中 -cf 后面跟的是备份文件名，本命令中改为“-”，就在告诉 shell 说，“先别急着写文件，你（shell）把我（tar）刚生成的数据流传递给后面负责压缩的兄弟（gzip），它知道该写哪个文件，谢谢哈～”。说明两点，A）你是否注意到备份文件的扩展名为 .tar.gz，不仅本例，涉及 linux 主题的网站提供的下载几乎都采用这种命名方式，这叫命名约定，通常来说，如果仅打包不压缩则扩展名为 .tar，如果打包且采用 gzip 压缩则扩展名为 .tar.gz，如果打包且采用 bzip2 压缩则扩展名为 .tar.bz 或 .tar.bz2；B）其实 tar 命令使用 --gzip 和 --bzip2 参数可以直接实现打包压缩，无须像上例，采用管道和重定向来实现，但，为精确显示整个备份进度率，必须采用这种变通方式，请接着看。

第三步，打包压缩带进度备份。要显示备份进度，必须得事前知道待备份数据（/data/）的大小，可通过 du 命令实现：

```
du -sb /data --exclude='/data/misc/tmp' --exclude='/data/misc/software/vm/win_7/share_folder'
```
其中，-s 表示计算 /data/ 整个目录包括子目录下所有文件的大小总和，-b 表示计算结果以 byte 为单位（或者 -k、-h 等）显示，单位的精度越高，计算百分比进度时越精确。

待备份目录大小知道了，如何计算进度？上面介绍过，打包、压缩、写文件都在借助管道传递数据流，如果能查看到管道中已经传递的数据量大小，用此大小除以总大小不就能显示出当前备份进度了么？铛铛铛铛哒～，pv 现身，顾名思义 pv 就是 pipe viewer，明白了吧，管道查看器，它是监测管道数据的超级武器，没事多用用、系统更健康。

```
tar -p -cf - /data --exclude='/data/misc/tmp' --exclude='/data/misc/software/vm/win_7/share_folder' | pv --size xxx | gzip > /media/backup_120g/data_backup@`date +%m-%d`.tar.gz
```
其中，xxx 部分填入前面du命令输出结果（待备份目录 /data/ 总大小），不带单位则表示以 byte 为单位（-k 以 kb 为单位、m、g、t 亦然）。效果如下：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%8F%AF%E8%A7%86%E5%8C%96%E5%A4%87%E4%BB%BD%E8%BF%9B%E5%BA%A6.png" alt=""/><br />
（可视化备份进度）
</div>  

好了，到此包括打包、压缩、排除不重要目录、打时间戳、显示进度等特性在内的 linux 常规备份操作就介绍完了，一条命令啰哩吧嗦说了一大堆，大妈命～～。内容是多了点，一次没看明白就多看几次，其实也不复杂，我们一起看看简化模型吧（啰嗦的平方就是在下，谢谢，：O）。

```
du -sk /source
tar -p -P -cf - /source | pv --size xxxk | gzip > dest.tar.gz
# 若仅打包不压缩则将上条命令中的gzip改为cat即可
```
有备份就有恢复，相对备份操作而言，恢复就太简单了。仍用tar命令，参数不同而言：

```
tar -xv -f dest.tar.gz -C .
```
其中，-x 表示执行解压解包操作，采用哪种解压算法由 tar 自行侦测后决定，-v 表示显示以及解压出的文件列表，-f 表示该参数后面紧跟的就是待解压的文件名，-C 表示该参数后面紧跟是解压后的文件存放路径。

这次真的说完了，没想到我对朴实的 tar 如此动情，不知不觉谈了这么多关于她的点滴。在介绍她的同时，我也再次品味到了 UNIX 哲学 —— 分工明确、各司其职、齐心协作。

**直接备份数据**

相较压缩备份，直备就简单多了。貌似 cp 配合 pv 可以实现带进度的拷贝：

```
cp src/big.file /proc/self/fd/1 | pv --size XXX | cp /proc/self/fd/0 des/back.file
```
但，实际上，由于使用了 /proc/self/fd/1，该方式只适用于拷贝单个文件，不适合整个目录，如果显示单个文件的拷贝进度，完全可用 rsync、scp 等自身就有进度显示的命令替代。其实，显示拷贝进度的算法不难，单独起个线程，实时当前拷贝总量/计算待拷贝总和，再将结果以百分百和进度条显示打印出来即可。要不咱就到 gnu.org 下载 cp 源码，自己把显示进度的代码添加进去？别急，我肯定不是第一个有此想法的人，先duckduckgo.com 下，果然有人为 cp 写了显示进度的增强补丁，直接下载后替换本地 cp 命令（zwicke.org/web/advcopy/advcpmv-0.5-8.21-static.tar.xz）。具体命令模型如下：

```
cp -grp src/* des/ && cp -grp src/.[^.]* des/ 
```
简单解释下，系统自带的 cp 命令（以及 rm、mv 等）存在两个致命伤：一是上面提到的无法显示拷贝进度、剩余时间等用户关注信息，一是无法处理隐藏文件。针对问题一，用改良后的增强版 cp 命令结合其独有的 -g 命令行参数即可解决，针对问题二，需要用 src/.[\^.]\* 方式特殊处理，所以，上面命令中分别依次（&& 目的所在）拷贝非隐藏文件（src/*）和隐藏文件（src/.[\^.]\*）。

拷贝大量文件的过程是否可靠？别急，直备完了再检查下数量和大小。检查待备份目录中文件数与直备目录文件数是否一致：

```
ls -lR src/ | grep "^-" | wc -l && ls -lR des/ | grep "^-" | wc -l 
```
检查待备份目录总大小与直备目录是否一致（单位 byte）：

```
du -sb src/ && du -sb des/
```

备份，介绍完毕。

<h3 name="4.2">4.2 碎片整理</h3>
要理解碎片，必须先了解硬盘基本结构和硬盘读写机制两个概念。之后，再看看不同操作系统写文件的策略，你自然会明白碎片在 linux 下是啥东东。

硬盘基本结构。硬盘内部是由多张磁片和一个机械臂组成，磁片上最小单位是扇区，一旦硬盘停止工作后（如，关机），机械臂将复位到第一个扇区处。对于扇区而言，不论写入数据有多小，一旦占用了某个扇区后，其他数据就不能再写入通过扇区，即便该扇区还有空余空间（这就是为什么我们说一个大文件要比拆分为多个小文件的合计要小一些的原因）。每次读或写操作之前，机械臂先移动寻找到要访问的扇区，这个过程称之为“寻址”，由于机械臂移动是个物理动作，如果读写操作老是在不同扇区间不停移来移去，势必会增长读写操作耗时。

文件布局策略，决定了是否产生磁盘碎片。

windows 采用的文件布局策略——所有文件相互紧靠布局，相邻文件间不会出现任何空闲扇区。我们假定有 A、B、C 三个文件，按 windows 的文件管理策略，依次连续占据 0～3 号扇区、4～7 号扇区、8～9 号扇区，这时，用户编辑了文件 B，增加了文件内容，导致文件 B 体积增大了 2 个扇区的大小，由于文件 B 后紧接文件 C，此时以无空闲扇区，只能将增加部分内容写入最靠前的空闲扇区，即，10 号和 11 号两个扇区，这时，10、11 号扇区就形成了碎片。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/windows%E6%96%87%E4%BB%B6%E7%AE%A1%E7%90%86%E7%AD%96%E7%95%A5.png" alt=""/><br />
（windows文件管理策略）
</div>
以后，一旦用户需要访问文 件B，系统先寻找到 4 号扇区，将 4～7 号扇区读入内存，再寻找到 10 号扇区，将 10～11 号扇区读入内存，最后将这 6 个扇区合并供用户使用（当然，这一过程对用户是透明的）。设想一下，刚装好系统时硬盘上有 5000 个文件，其中1000个在后来系统使用过程中被人为或程序调整过大小，那么这 1000 个文件个个都被截成几段，这就形成了大量“碎片”，文件越多、文件写入次数越多，产生的碎片就越多。

linux 采用的文件布局策略——所有文件分散布局，相邻文件间预留空闲扇区。对比上例，linux 在创建文件时，将文件 A 置于扇区 0～3、文件 B 置于扇区 6～9、文件 C 置于扇区 12～13，由于文件 B 和文件 C 之间有两个空闲扇区，在文件 B 增大 2 个扇区时，直接占用扇区 10 和扇区 11，不会形成碎片。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/linux%E6%96%87%E4%BB%B6%E7%AE%A1%E7%90%86%E7%AD%96%E7%95%A5.png" alt=""/><br />
（LINUX文件管理策略）
</div>
显然，按 linux 的策略，无论硬盘中有多少文件、写入多少次，系统基本不会产生碎片。再回到前面的问题，linux 碎片整理代表什么？代表没事找抽～～

有童鞋问，如果文件增大扇区数大于该文件后空闲扇区数时会是啥情况？good news，linux 有一套智能算法，让文件分散布局得足够合理，只要文件系统使用率不超过80%，该算法基本能保证每个文件后有足够空闲扇区可用，实现零碎片；bad news，一旦使用率超过 80%，碎片仍会出现，这时，虽然少量碎片对性能有一定影响，但至少剩余的空闲磁盘资源仍然被合理利用起来了。访问缓慢、浪费空间，两害，取其轻。

如果你是偏执狂，非要消除那不足 20% 文件产生的碎片，可以这样，先将该文件系统上所有文件剪切至其他文件系统，再剪切回来，可在一定程度上消除碎片。

<h3 name="4.3">4.3 垃圾清理</h3>

再先进的系统用久了也会产生各类垃圾，既有临时文件、备份文件、访问历史这类系统运行过程中自己产生的，也有崩溃日志、cookies、会话文件这类各应用程序生成的，这些垃圾文件，不仅占用了存储空间而且影响系统性能，定期清理很有必要。bleachbit 来了。

bleachbit 可按系统和各个应用软件分类清理垃圾，纳入 bleachbit 管理的软件上千种，常见的 bash、firefox、flash、GIMP、GNOME、java、libreoffice、X11 等等都在其中。除了如下几项：bash - history、firefox - cookies、firefox - passwords、firefox - session restore、firefox - site preferences、firefox - url history、thunderbird - passwords、system - memory、system - free disk space，最后一项的名字不太准确，不是说释放磁盘空间，而是 0 写那些已被删除的文件所在的扇区，此操作非常耗时，对于自用的电脑来说没什么必要。

在 bleachbit 清理垃圾前，建议你关闭涉及清理的应用程序，避免因资源征用导致清理不彻底。另外，bleachbit 很朴实，不像 360 那样好大喜功，实施完后不会显示为你清理了多少空间，如果你想实时查看空间释放情况，可以同时运行

```
watch -n 1 df -h
```
效果如下：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/bleachbit%20%E6%B8%85%E7%90%86%E7%B3%BB%E7%BB%9F%E5%9E%83%E5%9C%BE.png" alt=""/><br />
（bleachbit 清理系统垃圾）
</div>


<h2 name="5">5 图形图像</h2>
我们活在五彩斑斓的世界，色彩组成了世间万物。计算机是真实世界的数字扩展，当然也应该多彩绚丽。

<h3 name="5.1">5.1 图片编辑</h3>
玩单反的朋友用 photoshop，玩单反又玩 linux 的朋友用 gimp。gimp 是 linux 下著名的图形处理工具（同时，由它衍生出来了一种功能强大、设计灵活的通用图形库gtk，gtk 被 gnome 选作基础库，成为 gnome 环境中图形应用程序的开发标准），功能与 photoshop 不分上下。

软件名称：gimp

界面截图：后面绿色区域是桌面背景啦，另，图中大象的玩弄、抚摸以及搓揉权归属吴凤辉先生，特此声明！
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/GIMP.png" alt=""/><br />
（gimp）
</div>

<h3 name="5.2">5.2 色彩提取</h3>
有时看到很好的配色方案想要把色彩记录下来，这时就需要一款提取色彩值的工具。

软件名称：gpick

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/gpick.png" alt=""/><br />
（gpick）
</div>

<h3 name="5.3">5.3 屏幕截图</h3>
截图是很常用到的一种工具，我认为一个好的截图工具至少应具备能截取视频图片、能放大像素以让用户精确截图、预置常用的截图模式（即，除截取鼠标选中区域外，能针对窗口、菜单、提示气泡等直接截取）等功能点。shutter 号称 linux 下最强截图工具，支持我提的几点要求，值得推荐。

软件名称：shutter；

界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/shutter.png" alt=""/><br />
（shutter）
</div>

其他说明：shutter 有个小 BUG，在该软件中设置了快捷键无法生效，会报错 WARNING: DBus connection to org.freedesktop.compiz failed --> setting keyboard shortcuts may not work when using compiz。要解决该问题，可设置系统的全局快捷键，通过全局快捷键从命令行启动 shutter 完成不同模式截图操作：进入系统快捷键设置界面 system settings -> keyboard -> shortcuts -> custom shortcuts -> +，在 name 中输入快捷键名（如 screenshot win），command 中输入具体命令（如，shutter --window --min_at_startup），保存，点击 new accelerator，接着你点击需要设置的快捷键（如 F4），这样即可完成 F4 调用 shutter 实现截取整个窗口的功能，同理，shutter --select --min_at_startup 截取指定区域、shutter --full --min_at_startup 截取整个屏幕、shutter --web=http://www.csdn.net --min_at_startup 截取完整网页。另外，选择快捷键时注意不要与系统常见默认快捷键冲突。

<h3 name="5.4">5.4 屏幕录像</h3>
说了屏幕截图肯定要说屏幕录像，如果是一副图抵得上 100 个字，那么一段视频就是100 副图。录屏工具生成的视频格式非常重要，最高压缩比的视频文件体积都不小，能表达连续动作又能比视频文件体积小的文件格式是什么？gif 格式。byzanz 可以将录屏内容直接输出到 gif 文件中。byzanz 是个命令行工具，但操作不难。

```
byzanz-record -d 16 -c test.gif
```
其中，-d 表示以秒为单位的录屏时长，-c 表示包括录制鼠标。

真心喜欢这个软件，但受限于需要手工指定屏幕位置以及录屏时长，灵活性相对欠缺。就我而言，存在三个硬伤。

硬伤一，无法针对选定区域录屏。byzanz 支持在命令行参数中输入屏幕坐标来指定录屏区域，这在实际操作过程中非常麻烦。如果有个命令行程序可以获取鼠标在屏幕上拖拉矩形区域的坐标，并输出坐标结果，那么不就可以将坐标输出给 byzanz，实现对指定区域录屏的效果。一翻搜索后，果然找到名为 xrectsel 的工具（https://github.com/lolilolicon/xrectsel ），下载安装好。结合 byzanz 和 xrectsel 写了个脚本 byzanz-record-region.sh 实现针对选定区域录屏，代码如下：

```
#!/bin/bash

# recording duration
DURA=256

# output file name
RANDOMSTR=$(cat /dev/urandom | tr -dc 'a-zA-Z0-9' | fold -w 4 | head -n 1)
OUTPUT="record_screen($RANDOMSTR).gif"

# Sound notification to let one know when recording is about to start (and ends)
beep() {
paplay /usr/share/sounds/gnome/default/alerts/glass.ogg &
}

echo 'choose region by mouse ...'

ARGUMENTS=$(xrectsel "--x=%x --y=%y --width=%w --height=%h")
if [ 0 -ne "$?" ]
then
	echo 'ERROR! command xrectsel execute failure. maybe you have not install xrectsel(https://github.com/lolilolicon/xrectsel) at all. check it. '
	exit 1
fi

echo "byzanz will start to record $DURA seconds after 4 seconds, [ctrl-c] stop."
sleep 4
echo 'BEGIN >>>>'

# catch the ctrl-c, to tell byzanz stop
trap 'echo " "' 2

beep
byzanz-record --cursor --delay=0 --duration=$DURA ${ARGUMENTS} $OUTPUT 2>/dev/null
beep
echo "END <<<<"
echo "you get $OUTPUT"
```

硬伤二，无法针对指定窗口录屏。有了前面的思路，我们只需找个能获取指定窗口坐标的命令行工具，将坐标结果输入给 byzanz 即可。搜索下，有个 xwininfo 的工具，结合 byzanz，写了个脚本 byzanz-record-window.sh 实现针对指定窗口录屏，代码如下：

```
#!/bin/bash

# recording duration
DURA=256

# output file name
RANDOMSTR=$(cat /dev/urandom | tr -dc 'a-zA-Z0-9' | fold -w 4 | head -n 1)
OUTPUT="record_screen($RANDOMSTR).gif"

# Sound notification to let one know when recording is about to start (and ends)
beep() {
paplay /usr/share/sounds/gnome/default/alerts/glass.ogg &
}

echo 'choose windows by mouse ...'

XWININFO=$(xwininfo)
read X < <(awk -F: '/Absolute upper-left X/{print $2}' <<< "$XWININFO")
read Y < <(awk -F: '/Absolute upper-left Y/{print $2}' <<< "$XWININFO")
read W < <(awk -F: '/Width/{print $2}' <<< "$XWININFO")
read H < <(awk -F: '/Height/{print $2}' <<< "$XWININFO")

echo "byzanz will start to record $DURA seconds after 4 seconds, [ctrl-c] stop."
sleep 4
echo 'BEGIN >>>>'

# catch the ctrl-c, to tell byzanz stop
trap 'echo " "' 2

beep
byzanz-record --cursor --delay=0 --duration=$DURA --x=$X --y=$Y --width=$W --height=$H $OUTPUT 2>/dev/null
beep
echo "END <<<<"
echo "you get $OUTPUT"
```

硬伤三，无法按需主动停止录屏。byzanz 是实时写文件，所以直接 ctrl-c 中断任务即可。

为便于后续使用，先把这两个脚本赋予可执行权限：  
```  
chmod u=rwx byzanz-record-window.sh
chmod u=rwx byzanz-record-region.sh
```  
再移至程序目录：  
```  
cp byzanz-record-window.sh /usr/bin/
cp byzanz-record-region.sh /usr/bin/
```  
以后，要对窗口录屏可运行 ./byzanz-record-window.sh 脚本，要对选择区域录屏可运行 ./byzanz-record-region.sh，输出结果位于当前工作目录中。

<h2 name="6">6 windows 应用</h2>
无论如何，在当前环境下完全摒弃 windows 是不现实的，主要原因之一，某些市场占有率极高的软件并无对应 linux 版本，就我而言，至少三类应用：在线购物、即时通讯、离线下载。

有些 linuxer 认为引入 windows 程序会玷污 linux 的纯洁性，宁愿放弃某些应用，也不愿和 windows 沾边。个人认为，任何事情不要走极端，我们玩 linux，是为了享受它带来的开放、自由、创新，但同时，也不要人为丢弃 windows 提供的特有服务，毕竟，我们使用电脑是为了解决实际问题，而不是向谁证明“我是一名纯正的 linuxer”。当然，如果有功能类似的软件，肯定会优先选用 linux 版本，这点无须质疑。我们需要借助 windows，这倒不是 linux 系统本身不够完善，而是某些应用软件开发商只发布了 windows 版本，且那些软件又掌握着其所在领域的垄断权，以至于第三方即便有心也无力在 linux 下开发类似软件。

linux 和 windows 两种操作系统有各自的可执行文件格式（前者为 ELF、后者为 PE）、有各自的应用程序编程接口（前者为 SUS、后者为 win32 API），因此，针对某种操作系统开发的应用程序理论上二进制是无法在直接在另外的系统上直接运行。当然，那些采用解释性语言开发的程序，只要目标系统上有对应解释器或虚拟机是可以的；又或者，编译性语言使用某种平台无关的中间层库，也可以在一定程度上达到移植的目的。但是，这两种场景的前提是能获取源码，对于不能获取源码的应用程序，目前有两类解决方式：转换层方式（模拟 Windows 操作系统）和虚拟机方式（模拟计算机硬件）。

我们说的第一类解决方式，是在 linux 中部署一套为 windows API 转换层，我们让应用程序在转换层中运行，应用程序继续调用 windows 提供的 API，转换层接收到 API 请求后将具体执行操作传递给 linux 系统，linux 执行完后返回的转换层，转换层将请求执行结果反馈给 windows 应用程序，完成一次 API 请求，这样重复往返多次不同 API 调用，最终模拟完成整个应用程序执行过程。这种方式虽然可行，但也不完美：a）操作系统本身就是由大量 API 组合而成，如果实现了所有 windows API 那差不多实现了 windows 系统，从工作量和复杂度上来说，这不是哪个开源社区能够负担得起的，所以，目前做得最好的转换层（wine）也仅实现了部分 API，这意味着，不是所有 windows 程序都可以在转换层中运行，这是一个问题；b）既然是模拟 API，那么从执行效率（实时性）、执行结果（正确性）上看，肯定与直接在 windows 中执行存在明显差距，时常会出现程序异常退出、运行缓慢等等问题，这对实时性要求较高的应用（在线游戏）来说，是用户无法接受的。正因为此，不推荐该方式。

第二类解决方式是安装虚拟机，在虚拟机中安装一个 windows 操作系统，这就像和你直接安装的 windows 一样，这样就有了一整套完整的 windows API，所有应用程序均可正常运行。如果在 linux 中出现 windows 应用让你胃口不佳、疲软乏力、夜不能寐，你得自我开导，你可以把它想成 java 应用要运行在 JVM 中，所以 windows 应用运行在 windows 虚拟机中，windows 就是你 linux 中的一个运行环境，与 OpenOffice、thunderbird、firefox 等等软件一样，这下是不是轻松了许多。

virtualbox，著名的开源虚拟机（别管它的东家：）。VB 将客系统（虚拟机内的操作系统，我们这里就是 winTPC，一种 win7 官方精简版本）的所有硬件请求直接透传至底层硬件平台，而非通过主系统（运行虚拟机的操作系统，我们这里是 openSUSE）中转，这样，在 VB 中你就有一套完整的 win 环境了。但是，虚拟机毕竟不是物理机，性能肯定有损耗，所以，你应该从以下几方面弥补：
* 客系统应采用固定大小硬盘空间分配方式。虚拟机有多种存储空间使用模式，固定大小和动态调整两种最常用。比如，划拨 32G 空间给客系统，客系统内客系统数据量有 2G，那么，如果是固定大小模式，这 32G 的空间主系统已无法再使用，即便客系统只用了 2G；而动态调整模式，主系统仍然可以用余下的 30G 空间。显然，在存储资源利用率上，后者更优。但是，另一方面，动态调整模式需要客系统每次写数据时有些附加计算，所以，从运行效率上来看，你应优选前者，当出现存储资源不够时再在 VB 管理界面中手工设置
* 客系统 winTPC 能访问的分区应位于 SSD。SSD 相较机械硬盘在 I/O 读写上占有绝对优势，提升客系统 I/O 率；
* /winTPC/ 采用 NTFS 文件系统格式。windows 采用 NTFS 格式的文件系统，linux 采用 EXT4 这类非 NTFS 系统，为了避免虚拟机读写文件时作格式转换，应为 /winTPC/ 选用 NTFS。你把整个 /winTPC/ 分区选进 win 虚拟机作为其虚拟硬盘，win 中你将整个虚拟硬盘划给唯一的分区，即系统盘（即 C:），由于只有很少几种场景会使用到 win，需要安装的应用程序也就不多，即便全部安装在系统盘也无妨，所以，D:、E: 都用不着。linux 主系统与虚拟机 windows 客系统交换或共享数据有怎么办？你可以在主系统中创建一个目录 /data/share/，在虚拟机设置中将其指定为共享目录，之后在 win 客系统中你将看到一个网络硬盘 E:，这样，你在 win 客系统中安装的迅雷的下载文件存放路径就可以选它了：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%85%B1%E4%BA%AB%E7%9B%AE%E5%BD%95.png" alt=""/><br />
（共享目录）
</div>
* 使用主系统的 I/O 缓存。settings - storage - controller SATA - use host I/O cache；
* VB 支持 Intel VT-x 和 AMD-V 两种虚拟化技术，你应启用它们。首先，你得进入主系统 BIOS 从硬件层面开启虚拟化特性，然后，再在 VB 中设置，settings – system - acceleration，勾选 enable vt-x/amd-v 和 enable nested paging；
* 将虚拟硬盘视为固态盘。settings - storage - controller SATA - [your_hd].vdi - solid-state drive。

<h3 name="6.1">6.1 版本选择</h3>
在我的使用场景中，windows 系统的用途变得非常单一，仅为我提供在线购物、即时通讯、离线下载三类服务，所以，在 windows 版本选择上，我希望越精简越好，以达到尽可能少占用计算和存储资源的目的。那么，现在有几种选择：winXP，体积倒是小，2001 年的系统，太古老，缺失很多现代功能，再加上微软从 2014 年 4 月 8 日停止对其更新，稳定性较差，不想用；winPE，windows 预安装环境，一种不用安装、直接插入 U 盘就可使用的 windows 版本，通常用于系统恢复，缺失很多核心功能，不可用；新雨林木风版 win7，著名的第三方精简 windows，系统内核都被动过手脚，谁知道有没有后门木马，我可是要在线购物啊，风险太大，不敢用。微软于 2011 年初发布了一款在 win7 基础上简化而来的瘦身版 windows 操作系统，winTPC（Windows Thin PC，http://www.microsoft.com/wintpc ），用于在老旧设备上享受 win7 的基础功能，相较 win7，winTPC 装完后的裸系统，硬盘空间从 8.7G 减至 2.7G，内存使用率从 621M 减至 505M，安全性、功能性、轻便性都达标，就它了，非常适合我的使用场景。

winTPC 下载地址 http://download.microsoft.com/download/C/D/7/CD789C98-6C1A-43D6-87E9-F7FDE3806950/ThinPC_110415_EVAL_x86fre.iso ，下载后在 VB 中安装 winTPC。

默认情况，winTPC 只能试用 90 天，到期后，每次登录系统将提示激活，桌面背景也会变为纯黑且无法调整，甚至连 office 套件都将无法使用。激活，装完系统应该做的第一件事。先下载证书 https://bitbucket.org/Leask/windows-thin-pc-active/downloads （墙外），然后将 pkeyconfig-embedded.xrm-ms、Security-SPP-Component-SKU-Embedded-VLBA-ul.xrm-ms、Security-SPP-Component-SKU-Embedded-VLBA-ul-oob.xrm-ms 三个证书文件拷贝至 C:\，最后以 admin 权限（computer - manage - local user and group - users，双击 administrator 后，取消 account is disable）执行（无法找到命令行程序？随便打开一个目录，在窗口的地址栏中输入 cmd 回车）：

```
slmgr.vbs /ilc c:\pkeyconfig-embedded.xrm-ms
slmgr.vbs /ilc c:\Security-SPP-Component-SKU-Embedded-VLBA-ul.xrm-ms
slmgr.vbs /ilc c:\Security-SPP-Component-SKU-Embedded-VLBA-ul-oob.xrm-ms
slmgr.vbs /ipk XGY72-BRBBT-FF8MH-2GG8H-W7KCW
slmgr.vbs /xpr
```
以上命令 CMD 均为异步执行，换言之，表面上看 CMD 中命令已经返回了，但实际该命令仍在后台执行，所以，请依次执行完上一条命令等待确认对话框后再执行下一条，切勿全量复制至 CMD 中执行。重启后即可永久激活 winTPC。

winTPC 裁剪了大量非必要的服务和功能，其中包括中文语言包，若缺失将导致中文乱码，所以，必须自行安装中文包。先下载中文包 http://forums.mydigitallife.info/threads/27977-Windows-Embedded-Standard-7-Windows-Thin-PC-language-packs （墙外），然后将中文语言包 chinese_language_package.cab 拷贝至 C:\，最后 admin 权限执行

```
dism /online /add-package /packagepath:C:\chinese_language_package.cab 
```
后重启生效。

VB 中安装 windows 虚拟机的效果如下：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/virtualbox%E4%B8%AD%E8%BF%90%E8%A1%8C%E8%BF%85%E9%9B%B7.png" alt=""/><br />
（virtualbox 中运行迅雷）
</div>

要像使用原生 windows 那样使用装在 VB 中的 winTPC，你还得注意以下几方面。

内核管理。VB 对内核版本非常敏感，一旦有内核升级，必须对 VB 核心模块进行重新编译。别担心，不需要你具备程序员的能力，VB 会自动执行，你，负责为它准备相关编译工具：编译器 gcc、构建工具 make、内核头文件 kernel-devel，这三个工具均可通过软件仓库安装。一旦就绪，用 root 权限执行

```
/etc/init.d/vboxdrv setup
```
即可；

显卡管理。要让 VB 中的 winTPC 支持 3D 显卡加速，必须安装内置增强包。增强包只有在 windows 的安全模式下才能完整安装，windows 虚拟机启动时按 F8 进入安全模式，选择 virtualbox 菜单 devices - install guest additions 进行内置增强包的安装；

USB 管理。要让 VB 完全支持 USB 设备，除了安装内置增强包外，还应安装外置增强包。VB 官网下载 VirtualBox Extension Pack 外置增强包，从 VB 控制界面 file - preferences - exensions 中选择安装外置增强包，从 machine - settings - usb  中选中 enable usb controller 和 enable usb 2.0 (EHCI) controller，保存后重启主系统（对，不仅 VB 重启）。一般情况下，你插入的 USB 设备先是被主系统识别，要让客系统识别，必须在客系统中将其勾选出来，如果某个 USB 设备你只会在客系统中使用，这冗余一步未免麻烦，这时可以设置 USB 设备过滤器，让主系统自动移交控制权给客系统，比如，我的建行 U 盾“DMWZ Co. eSafeE_H”，如下图设置后，它将自动出现在客系统中：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/USB%20%E8%AE%BE%E5%A4%87%E8%BF%87%E6%BB%A4%E5%99%A8.png" alt=""/><br />
（USB 设备过滤器）
</div>
另外，有时你可能会遇到客系统提示无法获取 USB 设备控制权的提示“Failed to create a proxy device for the USB device. (Error: VERR_READ_ERROR)”，十有八九是你主系统中未正确设置将该设备的读写权限，给拥有者、群组、其他三类用户均分配读写权限

```
chmod a=rw usbname1 usbname2
```
重启 VB 即可。

<h3 name="6.2">6.2 资源下载</h3>
在我看来，优秀的下载工具至少应具备如下功能：支持主流公有下载协议（bt、ed2k、ftp）、支持不同协议从多个来源下载同个文件（如，你通过 ftp 协议下载文件 big_file.iso，下载工具智能分析找出其他协议在不同渠道中是否有同个 big_file.iso 文件，实现从原地址下载的同时也从所有其他尽可能多的地址下载同个 big_file.iso）、支持断线续传，所以，老牌下载工具 wget 已无法满足需求，推荐三个下载利器推荐：aria2、MLDonkey、uGet，优选 aria2，非常强大的下载利器，不过是命令行程序，以后考虑为它写个 GUI 前端，喜欢 GUI 的选用 uGet。

如果你是在国外网络环境中，有这几个工具之一也就足够了，但在冏朝就没那么单纯了，下载一定需要离线。目前有两款离线下载工具迅雷和 QQ 旋风。你知道，迅雷被 +- 和谐了，基本无法下载爱情动作片，所以仍然用迅雷的骚年，戒爱吧。我最近开始用 QQ 旋风，发现其优势有四：一是即便同样被视为违规资源但完全不影响下载速度，二是 QQ 旋风有个网页版支持跨平台（所以 linux 下诞生了 xfdown），三是资源消耗奇低，四是完全兼容迅雷私有协议 thunder:// 的下载地址。

前一节介绍的 VB 虚拟机 winTPC，直接安装 QQ 旋风即可。

<h3 name="6.3">6.3 网上购物</h3>
网上购物涉及两类操作，网银支付和在线交流，前者就是各大银行的在线支付程序，后者指的是淘宝旺旺软件，典型的两类 windows 原生应用，请参考上例在 windows 虚拟机中安装对应软件即可。唯一需要注意的 U 盾的识别，插入 U 盾后，先到 VB 中 setting - usb，勾选 enable usb controller，再到 windows 虚拟机中 devices - usb devices 列表中选中对应 U 盾，这样，windows 就能正确识别 U 盾了。其他 USB 设备的识别与之类似；

啰嗦两句网银支付。目前看来，朝内绝大部分银行仅支持 windows + IE 平台在线支付，完全忽视非 windows 用户的存在，强烈谴责“为保障您的资金安全，我行建议您在 windows 系统中完成交易”，举着安全大旗招摇过市（windows 安全？你银行服务器莫非装的高大上 windows server 2K8），相反，国外各大银行遵循标准化，支持在各类操作系统、浏览器上进行网上交易，如，美国花旗、汇丰，更有甚者（德国的银行业），银行对外开放 API，允许用户自行开发交易程序，怎么没见这些银行发生安全事故！当然，不是所有朝内银行都是“如此重视安全”，浦发银行是少数几家支持跨平台交易的银行，大家风范，值得推荐（不过营业网点较少，二三线城市几乎没有）。

http://www.openbanks.info 是一个专注于探讨网银跨平台主题的网站，有兴趣可以逛逛。

<h3 name="6.4">6.4 即时通讯</h3>
常见的 IM 工具包括飞信、QQ、旺旺，这三个 IM 都有对应的 linux 版本，但，不论是官方发布的还是第三方通过逆向工程实现的，从功能完整性、运行稳定性、界面友好性来看，均与 windows 原生版本存在巨大差距，实际使用效果并不理想。如果的确要用，建议参照上例，在 windows 虚拟机中安装运行。

或许是冏朝的 linux 用户量过少（linux 在全球桌面领域占有率仅为 2%，且主要分布在万恶的欧美等资本主义国家），国内软件开发商基本采用忽略态度，即便发布了 linux 版的程序，要么长年不更新（QQ for linux 从 2009 年 1 月发布后从未更新过，http://im.qq.com/qq/linux/download.shtml ）、要么不对外发布（aliwangwang for linux，仅用于淘宝公司内部测试，http://ge.tt/8sppgia ），在此呼吁各大开发商，请对 linux 予以正确的认识和重视，尊重我们选择操作系统的权利。（不得不承认，QQ 在囧朝不仅是 IM 工具，而是一种通讯渠道，如果你真离不开它，可以考虑web QQ（http://web.qq.com ）

<h2 name="7">7 其他杂项</h2>
前面介绍了各种常用软件，除此之外，还有些我个人经常用到但有不能归入前面分类中的软件，暂且放置于此。

<h3 name="7.1">7.1 蓝牙收发</h3>
电脑与手机通过蓝牙协议收发文件是最常见的蓝牙应用场景之一，下面将以笔记本电脑和手机收发图片为例进行介绍。

openSUSE 默认已经安装好相关蓝牙管理程序（核心程序 gnome-bluetooth 和 bluez），请确认正确、完整安装。在开始之前，我们先要进行文件共享设置，以便笔记本接收手机发送的图片。运行 personal file sharing 程序，按参照下图选中所有勾选框：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%85%81%E8%AE%B8%E8%93%9D%E7%89%99%E6%8E%A5%E6%94%B6%E6%96%87%E4%BB%B6.png" alt=""/><br />
（允许蓝牙接收文件）
</div>

就蓝牙收发图片的一般流程而言，我们先配对好两个蓝牙设备，在源设备中选中图片，选择通过蓝牙发送给目的设备，目的设备接收文件。但，openSUSE 蓝牙程序的 bug，如果我们以待发送文件为操作对象进行发送操作，那么系统将提示失败，换言之，不论我是从笔记本发送到手机，还是从手机发送到笔记本，只要选择文件再通过（笔记本或手机）菜单“经蓝牙发送”均会失败，必须通过另一种变通方式来实现蓝牙收发文件——手机存储浏览。也就是说，不管笔记本或手机哪个是源、哪个是目的，我们都应该先通过蓝牙浏览手机存储（如，手机的 micro-sd 卡），然后像在笔记本自身移动图片一样，通过复制、粘贴方式在笔记本硬盘与手机存储卡之间移动图片，从而实现笔记本与手机间通过蓝牙相互收发文件。具体演示步骤如下。

首先，运行 bluetooth，出现如下界面：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%9C%AA%E6%B7%BB%E5%8A%A0%E9%85%8D%E5%AF%B9%E8%93%9D%E7%89%99%E8%AE%BE%E5%A4%87.png" alt=""/><br />
（未添加配对蓝牙设备）
</div>
然后，点击“+”添加配对手机：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%B7%BB%E5%8A%A0%E6%89%8B%E6%9C%BA%E2%80%9C%E6%9D%8E%E5%A4%A7%E8%88%85%E2%80%9D.png" alt=""/><br />
（添加手机“李大舅”：-）
</div>
接着，点击右下角 browse files... 浏览手机存储卡，下图为手机存储文件列表：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%89%8B%E6%9C%BA%E5%AD%98%E5%82%A8%E5%8D%A1%E6%96%87%E4%BB%B6%E5%88%97%E8%A1%A8.png" alt=""/><br />
（手机存储卡文件列表）
</div>
最后，后续在笔记本和手机目录间剪切文件即可实现蓝牙文件传送。

随便说下，为增强系统的安全性，平时不需要时最好将蓝牙关闭（笔记本和手机都关了），省电不说，至少其他人看不到你设备上的任何资料，个人隐私还是要注意滴～

<h3 name="7.2">7.2 手机管理</h3>
不用羡慕 windows 下的各色 XX 手机助手，只要你是 android 手机，手机与 PC 在同个局域网内，那么可由 AirDroid 软件实现 android 手机的远程管理。为便于描述，我们将被管理的 android 手机称之为被管手机，将远程控制被管手机的终端称之为控制端。具体操作步骤如下：

第一步，在被管端运行 AirDroid，程序将随机生成控制端访问该被管端的验证码，以及控制端访问的 IP（用于无互联网环境）和 URL（用于有互联网环境）地址。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E8%A2%AB%E7%AE%A1%E7%AB%AF%E7%94%9F%E6%88%90%E9%AA%8C%E8%AF%81%E7%A0%81.png" alt=""/><br />
（被管端生成验证码）
</div>

第二步，在控制端用浏览器访问 http://web.airdroid.com ，并输入上面的验证码：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%8E%A7%E5%88%B6%E7%AB%AF%E8%BE%93%E5%85%A5%E9%AA%8C%E8%AF%81%E7%A0%81.png" alt=""/><br />
（控制端输入验证码）
</div>

第三步，在控制端随心控制被管端：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E6%8E%A7%E5%88%B6%E8%A2%AB%E7%AE%A1%E7%AB%AF.png" alt=""/><br />
（控制被管端）
</div>

再发散思维两点：1）控制端类型不限（PC、手机、pad 等等），操作系统不限（linux、mac、windows 等等），你可以用 openSUSE 笔记本作为控制端、可以用windows phone 手机作为控制端、甚至可以用 iphone 作为控制端，只要能正常运行浏览器即可。换言之，由于苹果移动设备未开放蓝牙功能导致一直无法让老婆的 iphone 手机与你的 android 手机之间传输相片的问题将被 AirDroid 完美解决；2）控制端与被管端只需在同个局域网内，不一定非要访问互联网。

<h3 name="7.3">7.3 英文翻译</h3>
不管你英文有多好，难免会遇到几个生词，英文翻译工具必不可少。stardict，中文名星际译王，国人出品的著名翻译工具，可惜作者个人原因，项目年久失修，后来，俄国人基于 stardict 新建 goldendict 项目，经过几年发展，已成为 linux 上的标配翻译工具，以至于很多发行套件默认安装该软件。goldendict 在功能上有很多创新，词态识别、智能去噪、同义词、相似拼写、正则查找，这些特点很难在同质软件中看到；在设计上低耦合、高内聚，聚焦实现高效单词查找功能，单词本身由各类词典负责，只要词典选得好，基本上，goldendict 无敌了。

<h4 name="7.3.1">7.3.1 安装最新版</h4>

添加源 http://download.opensuse.org/repositories/office:/goldendict/openSUSE_13.2/ ，安装最新版 v1.5。你知道，一般情况下，我优选源码安装，但，对于最新版的 goldendict，如果源码安装的，会出现键盘鼠标控制权无法释放、剪贴板内容变更引发屏幕取词等奇怪问题，所以，这次，强烈建议你安装预编译包而非源码安装（或许 openSUSE 针对 goldendict 作了优化）。当然，如果你非要坚持，也可以尝试，先安装依赖库：：  
```  
zypper --no-refresh in libvorbis-devel hunspell-devel libqt4-devel libxtst-devel phonon-devel libbz2-devel libao-devel libavutil-devel libavformat-devel libqtwebkit-devel recordproto-devel
```  
由于 openSUSE 源中不含 liblzo，必须源码安装该库的头文件和 *.so 库：  
``` 
wget 'http://www.oberhumer.com/opensource/lzo/download/lzo-2.09.tar.gz'
tar -xv -f lzo-2.09.tar.gz -C .
cd lzo-2.09/
./configure --enable-shared && make && make install # 生成 *.so 库
cp -r include/lzo/ /usr/include/
```  
下载最新版源码，qmake 构建即可：  
```
git clone git://github.com/goldendict/goldendict.git
cd goldendict
qmake CONFIG+=no_epwing_support
make && make install
```  

<h4 name="7.3.2">7.3.2 词典选择</h4>

babylon（巴比伦）和 lingvo（灵悟）是两款著名商业翻译工具，由于其商业属型，必须采用各自专属的私有格式词典才能正常使用（前者是 \*.bgl，后者是 \*.dsl/\*.lsa/\*.dat），相对封闭保守，而 goldendict 则开放得多。goldendict 是个翻译框架，自己不提供任何词典，但是，它支持 babylon、lingvo 以及其他多种格式词典。这下可了不得了，google 一大把 babylon 和 abbyy lingvo 的词典，你可以按互译语言、专业领域、词汇总量等等按需选用。

就我而言，对词典有几个要求，英译英、词汇全、图解示意、情境例句、关联词汇、真人发音（含英式和美式），首推《牛津高阶英语学习词典第八版》（http://pan.baidu.com/share/link?shareid=443301&uk=3189859145#path=%252Fgoldendict_dictionary 下的 En-En_OALD8/），牛津出品、品质保障，该词典共计收录 78534 个词汇，对于每个单词，先有清晰易懂的英文解释（孩纸，中文解释英文生词的方式，对你没好处），再配以生动形象的图片注释，接着又将该生词放入多条情境例句之中，然后罗列出多个与之相关词汇供你交叉学习，最后听下英美真人发音，这样，全套流程下来，你想忘记这个生词，难！如果觉得不够，同级别的，《朗文当代英语词典第五版》（En-En_Longman_DOCE5/）和《韦伯斯特大学词典第十一版》（En-En_Merriam_Webster11/）也不错。

如果需要英汉双解，http://www.babylon.com/free-dictionaries/languages/chinese/ 这儿有些词典。

词典导入很简单，edit - dictionaries - sources - files - add，选择字典所在目录，勾选 recursive，点击 rescan now 进行导入即可。

由于复数、过去式等等词态的存在，一个单词可能存在多种变化，比如，books、looked，goldendict 中是无法直接查找对应单词的，必须导入词态规则库以便 goldendict 正确识别。你的发行套件中可能带有词态规则库，别用，建议使用 goldendict 自制的，位于 http://sourceforge.net/projects/goldendict/files/better%20morphologies/1.0/ （墙外，en_US_1.0.zip 文件），下载后解压出来，edit - dictionaries - morphology - change 选择该词态规则库目录，然后在 available morphology dictionaries 中选中即可。

如果觉得上面这些本地词典更新及时性不够，你还可以添加各类在线词典，比如，有道：edit - dictionaries - websites - add，name 中填入 youdao，address 中填入 http://dict.youdao.com/search?le=eng&q=%GDWORD%&keyfrom=dict.top 。虽然这里告诉你了如何添加在线词典，但我必须得提醒你，尽量不用！从我的使用经验来看，一旦启用在线词典，将会随机出现键鼠无响应、屏幕取词失效等问题。

真人发音建议你使用 mplayer 播放，edit - preferences - audio - playback - use external program，填入 mplayer。由于某些真人发音存放在 *.wav 格式音频文件中，如果你发现播放无声，可以在命令行中用 mplayer 播放某个 *.wav 看看有何报错，一种常见情况是解码库未安装完整，比如，openSUSE 13.2 中缺少 libmad：  
```  
zypper --no-refresh in libmad0
```  

另外，goldendict 也支持屏幕取词，即，先用鼠标选中某个词组，接着在指定时间段内按下对应快捷键，最后弹窗显示该词组的解释。goldendict 限定只能在 alt、ctrl、shift、win 中选择（个人觉得不合理，这几个都是常用的功能键），ctrl+win 相对适合我。逻辑上，鼠标选中生词和按下快捷键两个动作必须同时完成才能开启屏幕取词，比如，你要对 hello 取词，鼠标点击 h 的同时必须得按下 ctrl+win，接着鼠标右拉五个字符选中整个单词，才会取词成功，麻烦。幸好，goldendict 给了个选项，让用户可以先单独选中生词而不用同时按下快捷键，只要在之后指定时间内补按快捷键也行，我一般设定为 2s（edit - preferences - keys may also be pressed afterwards within ...）。

简单演示屏幕取词功能，界面截图：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%B1%8F%E5%B9%95%E5%8F%96%E8%AF%8D.gif" alt=""/><br />
（屏幕取词）
</div>

当然，goldendict 仍有提升空间，比如，帮助文档太匮乏。

<h3 name="7.4">7.4 中文输入</h3>
个人认为，影响 linux 在朝内推广的最大阻碍得算输入法，其实，只要你姿势对了，中文输入不会有任何负担。为支持扩展，linux 下的所有输入类软件均分为输入框架和输入法两个部分，这样，既可以为某个输入框架创造自己的输入法，又可以把某个输入法复用于不同输入框架。

目前主流输入框架包括 scim、ibus、fcitx。scim 是老牌输入法，但项目早已停滞，长年不见更新；ibus，虽然被 gnome 默认集成，但开放性略微欠缺；fcitx，俗称小企鹅输入法，拥有大量用户群，github.com 上仍在活跃开发，有模糊拼音、常用词汇、智能匹配、主动学习、颜文字等特点，很好用。严格地说，fcitx 是输入框架，必须在此框架中选用拼音、五笔等具体输入法后才能正常输入，对于拼音用户，fcitx-pinyin、fcitx-googlepinyin、fcitx-sunpinyin 都是不错的选择，我，选用自带的 fcitx-pinyin。

openSUSE 默认源中的 fcitx 版本较低，先添加含有 fcitx 最新版 v4.2.9 的源 http://download.opensuse.org/repositories/M17N/openSUSE_13.2/ （优先级置为最高），再从中安装：  
```  
zypper in fcitx fcitx-pinyin fcitx-pinyin-tools # fcitx-pinyin-tools 是词库格式转换工具
```  
安装完后重启电脑，fcitx 将随系统自启动，将鼠标移至系统右下角，若出现一个键盘图标，说明 fcitx 安装成功。接下来，在 fcitx 图标上右键选择 configure 可对其进行详细设置，比如，外观颜色、候选词组显示数量、候选词组纵向列表显示等等，其中，最重要的是，选用拼音输入法，具体而言，在 input method 的 tab 中点击 +，取消 only show current language，选择 pinyin 和 english (us)。重启 fcitx，试试，有基本的输入功能，也有颜文字（先中文分号再键入 y (๑´ڡ`๑））这类特殊输入能力，对我而言，存在两个问题：一是无法用 tab 和 shift-tab 遍历候选词库、一是候选词库太单薄。问题一，几经折腾仍然无解，影响不大，暂缓；针对问题二，必须优先解决。

<h4 name="7.4.1">7.4.1 导入搜狗细胞词库</h4>
很多词组无法通过拼音首写字母快速输入，比如，词组“春秋窃曲纹绣”，你用默认词库试试，输入 cqqqwx，得到的第一候选词组是“从全球趣味性”，这是由于，fcitx 自带拼音输入法只含有基本词汇，你得逐字选择后形成自定义词组，fcitx 通过自学习可以识别，下次输入时会将其作为首选项。这么多专用词组都得从头创建有够麻烦，哪儿有现成可以让我直接导入就好了（跟前面的 goldendict 是不是异曲同工之味，开源世界，你感受下吧）。

搜狗拼音基于大数据收录了大量词组，取之于民用之于民，它的所有细胞词库可供大家自由下载 http://pinyin.sogou.com/dict/ 。这下来劲了，搜狗拼音的词库太有诱惑了，想法导入 fcitx。前例中的“春秋窃曲纹绣”明显是刺绣工艺词库（http://pinyin.sogou.com/dict/detail/index/6924 ）中的词组，以此为例，讲解如何让 fcitx 识别。

第一步，下载钟意的细胞词库并放至指定目录：  
```  
cd ~/
mkdir scel/
# 将下载回来的细胞词库放至 scel/
```  

第二步，将搜狗细胞词库转换为全拼/词语对应表的普通文本：  
```  
cd scel/
mkdir org/
for i in *.scel; do scel2org $i -o org/$i.org; done
```  

第三步，将多个对应表合并成一个对应表：  
```  
cat org/*.org > all_in_one.org
```  

第四步，对应表中内容剔重：  
```  
sort all_in_one.org > tmp.org
uniq tmp.org > all_in_one.org
```  

第五步，基于 fcitx 字码表将对应表转换成 fcitx 的词库：  
```  
wget https://raw.github.com/fcitx/fcitx/master/src/im/pinyin/data/gbkpy.org
createPYMB gbkpy.org all_in_one.org
```  
这步中你将获得最终词库 pyphrase.mb 及其配套字码库 pybase.mb。

第六步，将词库及字码库移至 fcitx 目录并重启 fcitx：  
```  
mv pyphrase.mb ~/.config/fcitx/pinyin/
mv pybase.mb ~/.config/fcitx/pinyin/
fcitx -r
```  
这时，再输入 cqqqwx，“春秋窃曲纹绣”已作为第一候选项出来了。经过以上几步，搜狗细胞词库成功导入 fcitx！

现在，你肯定想把所有的搜狗细胞词库全量下载回来，重复上面一至六步，让 fcitx 识别尽可能多的词组。搜狗细胞词库有 14 大类，每类至少又有 100+ 个词库，天，下载工作量太大了，可不能把哥给累着了，刚好其他人制作的一份全集，虽然是 2010 年的，将就用用，https://code.google.com/p/hslinuxextra/downloads/detail?name=fcitx-sougou-phrase-full.7z&can=2&q= （墙外），把解压出来的 pyPhrase.org 移至 scel/，然后再将你关注领域最新的细胞词库下载回来，融入 pyPhrase.org，执行上面几步即可。如下图所示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E9%9B%86%E6%88%90%E6%90%9C%E7%8B%97%E7%BB%86%E8%83%9E%E8%AF%8D%E5%BA%93.gif" alt=""/><br />
（集成搜狗细胞词库）
</div>

<h4 name="7.4.2">7.4.2 安装云拼音</h4>
前面导入的细胞词库相对静态，不可能天天更新，还得需要个云拼音功能。如下安装  
```  
zypper in fcitx-cloudpinyin
```  
所谓云拼音，实际就是在线拼音输入法，目前支持百度在线拼音和谷歌在线拼音，默认选用的是墙外的谷歌，你得手工改选为百度：configure - addon - cloud pinyin - cloud pinyin source - baidu。重启 fcitx 即可。

云拼音输入法与本地输入法是融合呈现候选词组而不是互斥的，云拼音只会把第一候选词组放倒本地输入法候选词组列表中，以蓝色高丽表示：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E9%9B%86%E6%88%90%E7%99%BE%E5%BA%A6%E4%BA%91%E8%BE%93%E5%85%A5%E6%B3%95.gif" alt=""/><br />
（集成百度云输入法）
</div>


<h3 name="7.5">7.5 软件开发</h3>
这个时代，上规模的软件项目已不可能用简单的文本编辑器完成，IDE 是必然选择。linux 下 IDE 大致分为两类：品牌机和组装机。品牌机中有些（开源）产品还不错，比如：codeblocks、netbeans、eclipse、anjuta 等等，对于初涉 linux 开发的朋友而言是个不错的选择（我指的是 codeblocks），但对于老鸟来说总有这样那样的欠缺。听闻 linus torvalds 这类大牛用的是类 emacs 和一堆插件拼装而成的 IDE，为向大牛致敬，加之那颗“喜欢折腾”的心，组装机是我的选择。首要任务，选择编辑器。linux 上存在两种编辑器：神之编辑器 emacs，编辑器之神 vim。关于 emacs 与 vim 孰轻谁重之争已是世纪话题，我无意参与其中，在我眼里，二者都是创世纪的优秀编辑器，至少在这个领域作到了极致，它们让世人重新认识了编辑操作的本质——用命令而非键盘——去完成编辑任务。我是人类，选用 vim。（...此处省略64页半...），详见《所需即所获：像 IDE 一样使用 vim》（https://github.com/yangyangwithgnu/use_vim_as_ide ），作者是帅鸽 \^\_\*。基于该文配置后，vim 可实现如下 IDE 效果：
<div align="center">
<img src="https://github.com/yangyangwithgnu/the_new_world_linux/blob/master/pics/%E5%9B%BE%E5%BD%A2%E7%8E%AF%E5%A2%83%E4%B8%8B%20IDE%20%E6%80%BB%E6%8F%BD.png" alt=""/><br />
（图形环境下 IDE 总揽）
</div>

<h3 name="7.6">7.6 虚拟终端</h3>
命令行，是体现 linux 强大的主要渠道，是驾驭 linux 的缰绳。在服务器领域， 99% 的任务只能依靠命令行执行完成，即便在现代桌面领域中，至少也有 30% 的任务离不开命令行。gnome3 自带虚拟终端是我操纵命令行的唯一环境，支持复制粘贴、支持多tab、支持外观自定义等等功能已经满足我日常需要。另外，介绍几个有用的命令行快捷键，将在一定程度上将提高你的效率：ctrl-c，结束当前进程；ctrl-z，挂起当前进程；ctrl-d，结束输入；ctrl-shift-c，拷贝选中文本；ctrl-shift-v，粘贴文本；ctrl-w，删除光标左边的一个单词；ctrl-u，删除光标当前至行首字符；ctrl-k，删除光标当前至行尾字符；ctrl-a，光标移至行首；ctrl-e，光标移至行尾。

<h3 name="7.7">7.7 升级 BIOS</h3>
为减少硬件故障率，定期升级 BIOS 是非常有必要的。一般而言，PC 厂商只发布 windows 版本和 dos 版本的 BIOS 升级程序，并无 linux 版本。linux 环境中倒是有个刷 BIOS 的开源工具叫 flashrom，但该工具支持的芯片有限，即便对于支持的芯片，风险也比在 windows 下高得多，对于刷 BIOS 这种高危操作，一旦失败将导致无法开机甚至机器报废，必须找一种安全保险的作法。

换个思路，既然你 PC 官网提供了 windows 版本和 dos 版本的 BIOS 升级程序，说明只要我们能提供 win 或 dos 环境，那么升级程序就能运行。在只装有 linux 的机器上，有三种提供 win 环境的方式：

* 方式一，前面介绍过 windows 虚拟机，但，BIOS 升级程序会先判断机器芯片是否匹配升级要求，由于运行在 virtualbox 中，所以升级程序只会读取到 virtualbox 伪装后的硬件信息，并非真实机器芯片信息，所以，通常来说，升级程序会提示你芯片不匹配后自动退出。该方式不可行，无法采纳；
* 方式二，再装个 windows，与现有 linux 形成双系统，进入新装的 windows 中进行 BIOS 升级操作。该方式可行，但耽误时间、浪费空间、污染环境，不想采纳；
* 方式三，我们知道，为让 windows 用户体验 linux，各大发行套件厂商有各自的 live-cd 或 live-usb，这就是让用户不用实际安装 linux 但又能使用 linux 的一种技术，同理，是否有所谓的 windows live-usb 呢？当然有，WinPE（Windows Preinstallation Environment），windows 预安装环境，朝内有人基于WinPE进行封装开发了一款名为“老毛桃U盘启动盘制作工具”的软件（http://www.laomaotao.net ），通过该软件可提供 Windows 环境。该方式简单、方便，优先采纳。

由于“老毛桃 U 盘启动盘制作工具”是个 windows 软件，先需要在 win 虚拟机中下载并安装，再插入 U 盘保证虚拟机中的 win 系统能正确识别（若有问题请见前面虚拟机中相关描述章节），然后在 win 中运行“老毛桃”将 U 盘制作成 windows live-usb，最后将 BIOS 升级程序拷贝至U盘中。重启机器，U 盘引导进 windows 预安装环境，运行升级程序即可完成 BIOS 升级操作。（另，如果是 dos 版的BIOS升级程序，方法类似，只是在 U 盘引导完成后的提示界面中，选择进入 dos 环境而非 WinPE 环境）。

<h3 name="7.8">7.8 有待提升</h3>
讲了这么多，不是说 openSUSE 就很完美了，有些细节做得还不到位，有待提升。比如，显示器亮度调节问题，只有在纯命令行（非图形界面的模拟终端）下有效；又如，virtualbox 运行时无法休眠（可待机）；再如，多屏幕投影时，无法实现多个屏幕内容一致。如此等等，虽大方面不影响使用，但如果发行商能及时修正，在这个各大发行套件血拼的时代，谁重视用户体验，谁将会赢得人心。

<h2 name="8">8 完结</h2>
一旦决定移居 linux，你得入乡随俗：查看自带手册熟悉软件操作、借助命令行弥补图形界面不足、多用键盘少用鼠标提升操作效率、了解并遵循不成文约定习惯、修改源码让软件满足你特殊需求、明白没有最好只有最适合的道理、取至社区并回馈社区、保持一颗热爱折腾的心。总之，thinking in linux。

linux 下的惬意生活，美丽新世界！
