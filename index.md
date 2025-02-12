# Smart-Space's Pages

Smart-Space blog

- - -

## 关于作者

作者目前是一名西工大本科生，属于教育实验学院/未来技术学院（HC）

- - -

## 项目

### TinUI

> 为Tin项目提供现代化虚拟组件

TinUI是基于tkinter的一个控件，借鉴了HTML和uwp（winUI）组件，用来绘制现代化的虚拟组件，优化tkinter窗口的显示效果和速度。

关于**TinUI**的[站内介绍](https://smart-space.com.cn/project/TinUI)

---

### Tin | TinText

<img src="https://smart-space.com.cn/img/TinLogo.png" width="300" height="300" alt="Tin的logo">

Tin's logo

Tin是一种**富文本标记语言**，像Markdown、html等语言，可以被指定的程序渲染成富文本。Tin的定位与Markdown一样，因为Tin基于tkinter（Python）开发， 无法实现像html那样的超文本类型渲染。

开发的起点虽然是tkinter，但是Tin同样提供了优秀的渲染效果和一定的交互能力。此外，相比于html和Markdown（主要是Markdown），Tin还有如下特点：  

1. 内置组件，可以使用文本框以外的组件进行渲染
2. 容器概念，实现加密、询问等交互功能
3. 即时性，通过<stop>、<jit>等标签，可以让读者跟随作者的思路阅读文本

> ~~相关链接：[Tin知识库](http://tinhome.baklib.com/)。如果因Baklib的原因无法访问，可以使用[临时知识库地址](http://tinhome.baklib-free.com/)。~~

关于 **Tin** 的[站内介绍](https://smart-space.com.cn/project/Tin)

> 在2024年8月，同样是基于python.tkinter，重新实现了TinML。
> 
> 新的TinML比旧版更实用、更规范、更简洁。

TinML的新一版实现直接命名为——[TinText](https://tintext.smart-space.com.cn)。

[下载地址 TinText](https://github.com/Smart-Space/TinText/releases/)

---

### TinEngine

> ~~隶属于Tin项目~~

~~TinEngine是实现对Tin标记进行渲染的重要组件，是最标准也是最基础的Tin标记实现。TinGroup的渲染功能均使用了TinEngine的渲染文本框（TinText），部分功能界面也是使用TinEngine加上Python实现。~~

~~TinEngine基于tkinter的Text开发，主体使用系统原生组件（ttk style）搭建，通过加入tkinter拓展以及自研内容丰富TinText的渲染效果和交互功能。此外，TinText还能够加入网页（HTML3、HTML5）的支持，拓宽TinEngine的使用范围。~~

~~TinEngine的技术功能和HTMLlayout一样，都可以实现现代的软件界面（UI）的快速搭建和显示，但TinEngine应用于能耗更少的tkinter（Python）程序中。TinEngine也可以作为文本文章阅读的渲染工具。~~

~~TinEngine在[Tin知识库](http://tinhome.baklib-free.com/)中通过使用接口的方式，以pyd文件的形式公开，因为不允许篡改Tin标签内容，所以使用pyd文件加载到Python（Cpython）程序中。TinEngine是半开源的，一些相关的框架可以在CSDN上找到[我的文章](https://blog.csdn.net/tinga_kilin/category_10332845.html)。~~

~~关于**TinEngine**的[站内介绍](https://smart-space.com.cn/project/TinEngine/index.html)~~

在新的TinML实现中，沿用了TinEngine的概念，但是有一点区别：

1. 开源

2. 实时解析、解释、渲染，速度更快

3. 下分核心部件、支持空间、语言转译等功能模块

新项目目前没有独立发布TinEngine，但是TinText中的TinEngine模块不依赖项目包，可直接“取出”使用，只需要保证`/data/*`目录的存在和规范即可。

---

### QuickUp

QuickUp是一个应用组启动器，通过自定义的任务，一键启动工作、学习软件环境。

具体见[QuickUp](./project/QuickUp)

- - -

### 其它项目

一些我主导或参与策划与主导的项目，[项目列表](https://smart-space.com.cn/project)。

---

## 博客

### CSDN博客

[CSDN博客网址](https://blog.csdn.net/tinga_kilin/)

### 站内博客

暂不开通

~~[站内博客地址](https://smart-space.com.cn/personal/blogs.html)~~

### 联系

[作者邮箱](smart-space@qq.com)

- - -

#### 友情链接

[航天爱好者网](http://www.spaceflightfans.cn/)    |    [中国航天局](http://www.cnsa.gov.cn/)    |    [Python官网](https://www.python.org/)
