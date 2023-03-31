# Project Unmask
Release Page: [https://chasedre.am/2023-04-01-project-unmask](https://chasedre.am/2023-04-01-project-unmask)

![](/assets/2023-04-01-project-unmask/poster_21031.jpg)
<p align=center>塞尔达传说：魔力面具复原海报 新人库帕</p>

![](/assets/2023-04-01-project-unmask/poster_pjum.png)
<p align=center>Project Unmask宣传海报 扭TYPE-小光</p>

## 赛博沧海拾遗
![](/assets/2023-04-01-project-unmask/screenshots.jpg)
神游未发售游戏——**塞尔达传说：魔力面具（魔吉拉的面具）** 沉寂19年首次披露！
{:.lead}

## 游戏介绍
钟楼镇里流传的一个谣言正在变为现实——三天内月亮将撞击地球！我们的小英雄林克不得不在剩下的72小时内找出避免地球遭此厄运的方法，而当林克发现幕后的指使是拥有强大邪恶魔力的魔吉拉面具时，一场与时间赛跑的拯救世界的勇者之旅开始了……
> ——神游在线（iQue@Home）

## 项目说明
2003年，神游科技（iQue）与任天堂合作，致力于将任天堂的主机和游戏进行本地化引进，并计划将大量的任天堂中文化游戏引入国内，但因为诸多障碍和问题的存在，最终未能如愿。

2004年，神游曾经在官网等物料里宣布了**塞尔达传说：魔力面具（魔吉拉的面具）**的发售情报，该作原本在计划内会成为继**塞尔达传说：时光之笛（时之笛）**之后，第二部中文化并在国内正式上市的塞尔达系列作品。

但是**魔力面具**因为未知原因最后并未发售，在当时成为了国内游戏史上“最黑暗的一天”，可惜并未引起广泛重视。时至今日，成功发售的任天堂国行游戏依旧寥寥无几。
<br><br>

抱着对于作品无奈流产的遗憾，以及对官方在过去对于中文市场所做的努力被白白埋没的不甘，当我们注意到在Gigaleak中意外泄漏了**iQue Player版魔力面具**的早期工程和一些资料的时候，一个拯救出早已被埋入茫茫历史尘埃的赛博文物的计划萌生在了心头。

我们首先联系到了已经初步尝试编译的外国神游爱好者，在得到掌握相关技术、且对这份历史产生兴趣的协作者的意愿后，几个志同道合的人所组成的跨国小组便成立了起来，修复工程也就此正式展开。

然而，修复的过程并非一帆风顺，大家彼此在现实中都有各自要忙的事，无法将太多精力投入其中。

面临原始ROM的程序和破解相关问题、外国友人对于导入中文的经验不足等挑战，项目曾停滞了很长一段时间，直到一些新成员的加入才得以继续。

而后，原始ROM过于早期，还有一些程序上的BUG，且神游相关的文档也存在一些错漏、或是排版等相关问题。我们在这方面也付出了很多精力，才使得ROM能够顺利运行、并显示排版合理的文本。

在导入完成后，大家也早就精疲力竭，但此时ROM还没有经过实际游玩测试过。因此又花费了许多时间去测试游戏中的实际显示效果，并修复了相关问题，这才在这款游戏公开的19年以后，成功复原出了现在这份尽可能符合神游当年发售质量的“完美版本”。


## 人员名单
### 简体中文本地化
* iQue Engineering（神游工程队）

### Project Unmask
* 修复人员

  无敌阿尔宙斯、Jhynjhiruu、新人库帕、
  \*\*\*\*\*\*\*\*、洗涤子
* 协助人员

  SnDream、\*\*\*\*\*、扭TYPE-小光

## 运行情况
本项目基于美版，兼容iQue Player、模拟器、N64实机。

兼容美版存档文件。
### 实机(烧录卡)
* iQue Player：
  * 实机测试，正常运行。
  * 关于破解及ROM安装，请阅读：[又一个神游机iQue Player破解指南](https://chasedre.am/2023-03-31-yet-another-ique-player-hacking-guide/)。
* 64drive烧录卡：
  * 实机测试，正常运行。
* EverDrive-64 X5/X7：
  * 未测试，理论支持？
* EverDrive 64 Pro：
  * 该烧录卡为EverDrive-64的国产抄版，正常运行。

### 模拟器
* RMG：
  * `v0.3.8` 正常运行。
* Project64：
  * `Dev-4.0.0-5911-a640ecf` 正常运行。*高清纹理包通关。*
  * `Dev-4.0.0-6089-9093b42` 修改内核设置后正常运行。
* OpenEmu：
  * `v2.3.3` 修改内核设置后正常运行。*99%完成度通关。*
* m64py（不推荐）：
  * `v0.2.5` 修改内核设置后正常运行。注意切换图形插件到GLideN64。

## 模拟器须知
* Windows/Linux桌面用户推荐使用RMG(Rosalie's Mupen GUI)。
* macOS用户推荐使用OpenEmu。
* 模拟器的图形插件**必须**使用GLideN64。

### 针对OpenEmu/m64py
OpenEmu/m64py均使用较旧的mupen64plus内核，其对"动态重编译器"的实现似乎不支持本ROM。

如无法正常运行，请禁用NoCompiledJump。

- OpenEmu
  1. 编辑 `Library/Application Support/OpenEmu/Mupen64Plus/mupen64plus.cfg`
  2. 找到 `NoCompiledJump` ，将其后的参数由 `false` 改成 `true` 。

- m64py
  - Settings --\> Emulator --\> 勾选"No Compiled Jump"

- **如果**RMG无法正常运行
  1. 编辑 `RMG/Config/mupen64plus.cfg`
  2. 找到 `NoCompiledJump` ，将其后的参数由 `false` 改成 `true` 。

### 针对Project64

部分版本的Project64，对"重编译器"的实现似乎不支持并本ROM。

如无法正常运行，请修改为解释器内核。

- 英文界面
  1. Options --\> Configuration --\> 取消勾选"Hide advanced settings"
  2. 进入左侧的"General settings: Advanced" --\> 勾选"Always use interpreter core"

- 中文界面
  1. 选项 --\> 设置 --\> 取消勾选"隐藏高级设置"
  2. 进入左侧的"选项：高级" --\> 勾选"总是使用注释器内核"

## 游戏说明
1. 该ROM基于Gigaleak泄漏的iQue Player版魔力面具早期工程编译，整合神游的翻译文本，并修复了各种问题。但由于正式版本按计划推出已经不知道是哪个平行宇宙发生的事，因而无法保证该修复版本游戏内的效果和正式发售版百分百相同，敬请见谅。
2. 修复原始ROM无法在模拟器/N64烧录卡存档的问题（iQue Player版存档方式与N64原版不一致），该ROM目前在模拟器/烧录卡/iQue Player破解机上都能够正常存档。
3. 修复原始ROM无法在长湾海岸正常触发剧情的问题（iQue Player版专属BUG）。
4. 修复原始ROM伊卡纳溪谷精灵之泉背景颜色异常的问题（N64原版问题，仅欧版修复了该BUG）。
5. 加入了原始ROM被阉割的振动功能（iQue Player硬件不支持振动），可以在模拟器/N64硬件的手柄上实现振动。
6. 该游戏当初大多数部分以美版为基准翻译，受时代限制，当时的神游的文风、字体、译名风格均与现在有所不同，游玩时请充分考虑这一点，具体翻译标准请以最新官方中文版的塞尔达传说系列游戏中出现的翻译为准。

## 联系反馈
* 电子邮箱：[me\<AT>chasedre\<DOT>am](mailto:me@chasedre.am)
* Github：[https://github.com/chasedream1129/project-unmask](https://github.com/chasedream1129/project-unmask)

## 游戏下载
* 发布主页: [https://chasedre.am/2023-04-01-project-unmask](/2023-04-01-project-unmask)
* 宣传视频：[https://www.bilibili.com/video/BV1FL411D7Y8](https://www.bilibili.com/video/BV1FL411D7Y8)
* 互联网档案馆：[https://archive.org/details/project-unmask](https://archive.org/details/project-unmask)
* Github：[https://github.com/chasedream1129/project-unmask](https://github.com/chasedream1129/project-unmask)
