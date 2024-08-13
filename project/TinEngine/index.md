# TinEngine介绍

<img src="http://smart-space.com.cn/img/TinLogo.png" style="zoom:35%;" />

​	TinEngine是一个基于tkinter的渲染环境，提供主要组件：TinText。

​	TinText能够实现对Tin标记文本的渲染，是原生的Tin实现，也是目前最强的Tin实现。

---

## 发布形式

### 下载

TinEngine以pyd编译形式发布。[下载地址](https://tinhome.baklib-free.com/9160/286d)

在你的代码中这样引用：

```python
from tkinter import Tk
import TinEngine

root=Tk()
#...
text=TinEngine.TinText(root)
text.pack()

root.mainloop()
```



### 拓展

从TinEngine-2.3.0-开始，发布到了pypi上。

在命令行运行如下代码：

```shell
pip install tinengine
```

在你的代码中这样引用：

```python
from tkinter import Tk
from tinengine import TinEngine

root=Tk()
#...
text=TinEngine.TinText(root)
text.pack()

root.mainloop()
```



### 必要说明	

至于为什么不开放源代码，而只开发接口。原因如下：

1. Tin还没有足够广泛，无法保证基础语法不被篡改（重点）
2. 防止黑心的人乱用（与[miniblink](https://miniblink.net/)半开源思路相似，重点）
3. 防止虚荣心强的人说是自己开发的（与[miniblink](https://miniblink.net/)半开源思路相似）
4. 提高速度渲染速度

## 开发初衷

1. 体现tkinter的价值
2. 为tkinter窗口布局提供类似HTMLlayout的布局方式
3. 提高tkinter窗口的开发效率
4. 是读者能够跟随编写者的思路阅读文章
5. 给富文本标记提供交互能力
6. 轻量化的富文本渲染组件（500k）
7. ……

## 应用范围

TinEngine可以应用在很多地方，以下是比较常用的方面。

#### 富文本阅读

TinEngine中的TinText，是一个富文本渲染框，可以将Tin标记文本渲染为人类易读的富文本。

#### 窗口布局

Tin标记中，不仅有渲染类标记，还有交互、导入（操作）类标签。基于此，可以将Tin标记语言理解为简化的HTML布局。

使用TinEngine中的TinText作为窗口主体，可以基于tkinter实现类似于HTMLlayout的Tinlayout。

#### 数据多样化

适用于数据集散型程序的文本数据呈现。例如爬虫、格式报告、格式化等。

## 运行速度

​	使用自动解析和底层编译加持，速度完胜原生tkinter。

​	根据目前测试，TinEngine-V3比TinEngine-V2快两倍。

## 版本迭代

目前，TinEngine经历了V1~V2两个版本。现在公开的最新TinEngine为**TinEngine-V3**

### V1(已结束)

由point_file函数直接控制文本框，根据输入的Tin标记行列表进行渲染。

### V2（已结束）

提供Tin标记渲染组件——TinText，根据输入的Tin标记行列表进行渲染。

### V3（当前使用）

直接解析Tin标记文本段，增加脚本支持，提升渲染速度（至少1.6倍）。

### V4（设想）

采用字典匹配……

---

## 相关链接

[Tin知识库](http://tinhome.baklib.com/)	|	[临时知识库](http://tinhome.baklib-free.com/)	|	[CSDN个人博客](https://blog.csdn.net/tinga_kilin)	|	[TIP-Tin改进计划](http://smart-space.com.cn/project/Tin/tip.html)