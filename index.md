# Welcome to Smart-Space's Pages

Smart-Space 的个人网站使用[GitHub](https://github.com/)提供的*GitHub Page*功能构建，通过html和Markdown等文件文本组成。

该个人网站用以记录关于Smart-Space的项目和一些事件。

- - -

## 关于作者
作者目前是一名中学生，喜欢 天文（以及航天项目）、物理、编程等。

这里可以查看关于作者的[详细介绍](https://smart-space.github.io/personal/index.html)（待完善……）

- - -

## 项目

### Tin
<img src="http://smart-space.github.io/img/TinLogo.png" width="300" height="300" alt="Tin的logo">Tin's logo

Tin是一种**富文本标记语言**，像Markdown、html等语言，可以被指定的程序渲染成富文本。Tin的定位与Markdown一样，因为Tin基于tkinter（Python）开发， 无法实现像html那样的超文本类型渲染。

开发的起点虽然是tkinter，但是Tin同样提供了优秀的渲染效果和一定的交互能力。此外，相比于html和Markdown（主要是Markdown），Tin还有如下特点：  

1. 内置组件，可以使用文本框以外的组件进行渲染
2. 容器概念，实现加密、询问等交互功能
3. 即时性，通过<stop>、<jit>等标签，可以让读者跟随作者的思路阅读文本

> 相关链接：[Tin知识库](http://tinhome.baklib.com/)。如果因Baklib的原因无法访问，可以使用[临时知识库地址](http://tinhome.baklib-free.com/)。

关于 **Tin** 的[站内介绍](https://smart-space.github.io/project/Tin/index.html)


### TinEngine
> 隶属于Tin项目

TinEngine是实现对Tin标记进行渲染的重要组件，是最标准也是最基础的Tin标记实现。TinGroup的渲染功能均使用了TinEngine的渲染文本框（TinText），部分功能界面也是使用TinEngine加上Python实现。

TinEngine基于tkinter的Text开发，主体使用系统原生组件（ttk style）搭建，通过加入tkinter拓展以及自研内容丰富TinText的渲染效果和交互功能。此外，TinText还能够加入网页（HTML3、HTML5）的支持，拓宽TinEngine的使用范围。

TinEngine的技术功能和HTMLlayout一样，都可以实现现代的软件界面（UI）的快速搭建和显示，但TinEngine应用于能耗更少的tkinter（Python）程序中。TinEngine也可以作为文本文章阅读的渲染工具。

TinEngine在[Tin知识库](http://tinhome.baklib.com/)中通过使用接口的方式，以pyd文件的形式公开，因为不允许篡改Tin标签内容，所以使用pyd文件加载到Python（Cpython）程序中。TinEngine是半开源的，一些相关的框架可以在CSDN上找到[我的文章](https://blog.csdn.net/tinga_kilin/category_10332845.html)。

关于**TinEngine**的[站内介绍](https://smart-space.github.io/project/TinEngine/index.html)
- - -

## 博客

### CSDN博客
[CSDN博客网址](https://blog.csdn.net/tinga_kilin/)

### 站内博客
暂无（待完善）~~

- - -
#### 友情链接
[航天爱好者网](http://www.spaceflightfans.cn/)