<p align="center">
  <a href="#">
    <img alt="JiYu Trainer" src="https://raw.githubusercontent.com/imengyu/JiYuTrainer/master/JiYuTrainerLogo256.png" width="128">
  </a>
</p>
<p align="center">
  <img alt="JiYu Trainer Title" src="https://raw.githubusercontent.com/imengyu/JiYuTrainer/master/JiYuTrainerTitle.png">
</p>
<p align="center">不再被极域电子教室控制</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/language-C++-blue.svg"></a>
  <a href="https://github.com/imengyu/JiYuTrainer/releases"><img src="https://img.shields.io/badge/version-1.7-greeb.svg"></a>
  <a href="https://github.com/imengyu/JiYuTrainer/blob/master/LICENSE"><img src="https://img.shields.io/badge/liscence-MIT-orange.svg"></a>
</p>

---

简介
---

本软件研发目的就是为了对抗极域电子教室，如果您的学校机房使用极域电子教室来控制学生电脑的话，本软件很可能会帮到你。极域电子教室全屏再见！

> 讲师讲课无聊啰嗦缓慢？想自己试试操作，却被该死的全屏广播控制，什么都不能干？拔掉网线后虽然自由了但是又看不到老师的演示了？

如果你被以上问题困扰，本软件可能是您非常想要的。

这是一个可以使 **极域电子教室全屏广播失效** 的软件，也就是说，在被老师全屏广播时，会将其自动调整为窗口模式，你不仅可以自由操作电脑，也还可以看老师的演示，自由+学习两不误，这不是很爽的事情吗？其还可以防止被老师控制（有点狠），以及自动关闭 “**黑屏安静**” 这种东西；由于本软件是将全屏调整为窗口，因此老师并不会发现你断线或是进行了非法操作。

如果你喜欢这个软件，不妨向你的好友推荐一下吧！

如果你觉得这个软件不错，不妨加个小星星⭐吧，你的喜欢是对我最大的支持！

功能
---
* 在不影响极域正常运行的情况下将 全屏的广播 转为 窗口广播 模式，您不仅可自己操作，也可看老师讲解课程。
* 内置强杀、启停极域 StudentMain.exe 进程功能，无需依赖其他软件。
* 内置破解极域解锁卸载密码功能，支持新版极域。
* 反监视功能，经测试，开启反监视，教师端就无法监视您所用的电脑。
* 防控制功能，防止教师通过极域控制您所用的电脑。
* 监控极域远程执行命令，您可以自由选择是否允许教师端远程执行的命令。
* 更多功能开发中……

下载
---

* [下载软件最新版已编译版本](https://raw.githubusercontent.com/imengyu/JiYuTrainer/master/Release/JiYuTrainer.exe) 
* [备用地址](http://jiyutrainer.imyzc.com/JiYuTrainer.exe) 

提示：**由于本软件会对极域电子教室进行必要的操作（远程注入、替换模块），某些杀毒软件可能会报毒，您可能需要关闭杀毒软件或添加白名单**。

---

![截图](https://raw.githubusercontent.com/imengyu/JiYuTrainer/master/ScreenShots.png)

操作方法
---

本软件专为小白设计，默认情况下，您不需要修改任何参数，直接运行exe，并最小化即可，软件会自动进行操作。

> 附加说明：本软件不依赖任何运行库，您只需复制一个 **JiYuTrainer.exe** 至目标电脑即可运行，本软件已将需要的DLL打包，它会自动进行安装。 

[完整帮助文档](https://raw.githubusercontent.com/imengyu/JiYuTrainer/master/帮助.png)

---

#### 已测试极域电子教室版本：

* 2010版 （5.01.64.942 / 5.01 Baseline）
* 2016豪华版 （2.07.0.13488 / 2.07 CMPC） 

*(这是现在学校使用最广泛的两个版本，其他版本应该也可以正常运行。假如你的学校使用其他版本的极域而本软件不能正常运行的话，你可以向我提供极域样本，我会尽力修改程序以适配更多的极域电子教室版本)*

#### 操作系统版本: 
* 系统最低需求: Windows XP SP3, 支持 Win7/Win8/Win10


编译以及生成
---

| 支持的编译工具：||
|:-|:-:|
| [Visual Studio](https://www.visualstudio.com/) 2017 | (推荐) |
| gcc 4.7+ (需要自己配置环境) | (不推荐) |
|**如果需要编译驱动模块，您还需要安装:**||
|[WDK8](https://www.microsoft.com/en-us/download/details.aspx?id=42273) 或以上||

> 提示：如果使用 Visual Studio 2019，无法编译支持XP的程序集，如果要编译支持XP，必须使用 Visual Studio 2017 ，并且设置生成工具为 v141xp


使用的第三方库
---

*第三方库已经包含在项目中，不需要您自己安装*

- [curl](https://github.com/curl/curl) (用于自动更新模块)
- [mhook](https://github.com/martona/mhook) (用于 JiYu HOOKER 模块)
- [MemoryModule](https://github.com/fancycode/MemoryModule)
- [XZip-XUnZip](https://github.com/yuanjia1011/XZip-XUnZip)

其他
---
如果您在使用软件过程中发现Bug、软件上的问题、更好的建议或者要求，也可以提issue，欢迎向我反馈！<br>
您也可以联系我本人 Email:kalierincn@outlook.com （请备注 **来自JiYuTrainer，改进自Kalicn**）

许可
---

[MIT License](https://github.com/imengyu/JiYuTrainer/blob/master/LICENSE) (free, open source)


