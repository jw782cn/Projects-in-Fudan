# Projects in Fudan
 Projects conducted by Chenran Ning in Fudan University

My Chinese name is 宁晨然(Chenran Ning). My English name is Thomas.

This repository includes all the projects implemented by me from Sep 2017 to now.

I use ⭐ to comment on the quality of these projects(5 stars are the best).



## 大一

大一学习的基础课偏多，比如数学分析、线性代数、大学物理，做project较少。

#### 面向对象程序设计 ⭐⭐⭐

大一学习的跟专业知识挂钩的专业课，有程序设计(C语言/上半学期)和面向对象程序设计(C++语言/下半学期)。由于才大一，所以没有做很多有质量（但当时觉得有挑战性了）的project。

这个project我会要刘卉老师的推荐信，可能会在推荐信中提及。

C++的大project：

- 实现C++中的大整数的加减乘除
- 熟悉C++的数据结构，类的构造函数、成员函数、方法等
- 主要是熟悉了C++的面向对象特性



## 大二

大二期间的project质量一般般，不过也挺有含金量的哈。

### 大二上

#### 成功心理素质训练 ⭐⭐

技能书Exchange项目，这个不是计算机项目，是一个面向复旦大学生的服务型项目。我是组长，考验了很多组织力。

直接参考我的ppt和项目报告书吧，很详细。写的挺好的。

#### 数据结构 ⭐⭐⭐⭐⭐

数据结构是拔尖班的课程，我拿了A。这门课是**计算机最最最最重要的课**，因为之后面试基本就最重点考察数据结构。我们每周有5-7作业题，每周有机考，最后有一个大的project。project含金量挺高。我打算去找老师要推荐信。

project：

- 用数据结构知识解决地理围栏问题，解决判断地图上点在多边形内的基础问题，寻找最优数据结构使得运行速度最快。
- PointInPolygon in large Database problem
- 任务：
  - 寻找存储点和多边形的数据结构，寻找判断点在多边形内的高效算法
- 创新点：
  - 一开始从blender开源代码出发
  - 尝试了KD树和Range树
  - 尝试R树
  - 最终选择网格算法将索引和判断融合在一起，用空间换时间的思想，取得最终极快运行速度。
  - 具体看论文。。



#### 数字逻辑与硬件设计 ⭐⭐

是一门硬件语言课程，计算机非常底层甚至偏向于电工和微电子的课。做了七次实验。

- 环境：使用vivado软件，使用verilog语言

- 基本就是verilog语言我熟悉了，这些实验内容在报告里。



### 大二下

#### 计算机原理 ⭐⭐⭐⭐⭐

这门课是计算机超级重要的基础课，但我学的不是很好，拿了B-。（当时学的太痛苦了）而且这门课工作量很大，project极多。

做了两次作业homework，两次实验lab，三个大project（虽然叫做PA）



Homeworks:

- 环境：使用C语言，gcc编译器，linux系统

- 深入理解计算机计算机中整数、浮点数的机内表示和运算过程，通过观察与常 识不符合的程序结果来探索机器运算方式
- 理解程序编译链接 的过程，学会使用 进行基本的查看和调试

lab应该是CSAPP这本书配套的lab，好像是CMU配套的lab。

Labs:

https://blog.csdn.net/miracle_ma/article/details/79968992可以参考一下这个 lab1-2

- 位运算：熟悉数据位运算、熟悉计算机内部数据存放形式，运用C语言实现各种操作(Data lab)
- 二进制炸弹：认识汇编语言，通过汇编语言反演出程序，找出解题密码

PA应该是用的南京大学的[作业](https://github.com/likmin/ics2019)

PA0：

- 开发环境配置：安装 、配置环境、熟悉linux操作

PA1：

- 简易调试器：梳理NEMU框架，组织寄存器结构体，完成简易调试器中的几个功 能。初步认识 框架，活用 进行编辑，以完成模拟调试的功能。
- 在于表达式求值、监视点和i386手册的功能实现

PA2：

- 完成i386指令系统部分的阅读、框架代码的阅读、基本指令的实现三个板块。
- 重点在于理解i386系统取指、译码、执行的过程，并且根据流程实现基本指 令，其中还涉及到了EFLAGS寄存器的结构、初始化和更新。还需要完成打印变量、打印栈 帧。



#### 数据库 ⭐⭐⭐⭐⭐

数据库的内容其实挺简单，但有一个两人合作项目，做了一个大project。因为有视频，比较好展示。

project1：

- [演示视频](https://youtu.be/CEXan4tCjo0)
- 环境：使用python语言后端，django框架；使用html+js+css前端基本框架；mysql数据库
- 任务：
  - 实现了基于数据库的音乐网站（本地）music power
  - 我们最终实现的⾳乐⽹站，⽀持⽤户以及管理员两种不同的服务模式：基于⽤户的服务模式： 
    提供注册、修改个⼈信息、修改密码、检索歌曲、添加喜欢的歌曲、发布评论等功能操作；基于管 
    理员的服务模式，提供删除添加歌曲、专辑、⾳乐⼈以及删除⽤户的功能操作
  - 我的分工是前端+后端都有，前端几个页面的设计；后端框架部分的撰写、部分数据库操作函数
- 创新点：
  - 花了数据库的ER图，深入研究了数据库中表的结构
  - 花了用户操作的流程图，过程清晰
  - 前端美观好看，设计了完整的logo/产品理念，并且做了展示视频

Project2:

- PostgreSQL上实现similarity join
- 这个不太好写，因为任务也就很简单



## 大三

大三的project应该含金量最高。

### 大三上

#### 操作系统 ⭐⭐⭐⭐⭐

操作系统做的6个实验，lab1-lab6，实际上是MIT 6.828 OS课程的lab1-lab6的**简单版本**（删减某些作业），可能确实会简单很多，但是作业花费了很多时间感觉还是挺难的。

（这里有一个知乎的介绍，https://zhuanlan.zhihu.com/p/74028717）

- 环境：使用**c语言**，使用**vmware虚拟机**，在**linux系统**上做的实验
- 任务：
  - 了解x86汇编语言，掌握基础调试功能
  - 实现xv-6的进程管理、同步与互斥、调度管理机制、内存管理、文件系统等功能
- 最终完成了xv-6六个主题的实验，撰写了实验报告



#### 计算机网络 ⭐⭐⭐⭐

计算机网络课程主要有四个实验，lab1-lab4和一个大project。project是双人合作完成。project含金量还行。lab实验比较简单。

实验部分：

- 环境：使用**wireshark软件**
- 任务：
  - 实现网络抓包
  - 根据抓包内容分析DNS、HTTP协议、TCP协议、NAT

Project部分：

- 环境：使用**Python语言**做后端，**QT语言**做前端
- 任务：
  - 两人合作完成了一个网络聊天室
  - 实现了集登陆注册、群聊私聊、加群加好友等功能，QT窗口做前端做交互页面的网络聊天室
  - 实现了window/client/server三个模块，使用了自定义的网络传输协议实现前后端交互
- 分工：
  - 我负责了后端python撰写
  - 使用python实现server和client之间消息传递
    - 自定义message通信协议
    - 实现server和client分别的模块
    - 实现server和client之间通信，采用encode和decode方式



#### 人工智能 ⭐⭐⭐

人工智能主要学习了神经网络和专家系统，老师讲课内容偏传统的专家系统，做了一个专家系统project（专家系统是十年前比较流行的人工智能，不同于现阶段流行的深度学习和机器学习），个人觉得这个project比较水，拿了A-。但这个project有完整的中文论文（课程最后提交论文）。

但因为有完整的成文思路和解决问题过程，所以可能国外比较青睐？

项目（有点类似app“烧杯”）：

- 简述：实现化学反应方程式自动生成的专家系统，力图使用专家系统解决中小学生初中无机化学不熟悉化学反应过程的问题。
- 环境：使用python语言，maniam的动画生成库。
- 这一个项目有完整的论文，直接参考我的论文摘要和简述吧！（解决了三个问题）



#### 自然语言处理 ⭐⭐⭐⭐⭐

自然语言处理(NLP)应该是比较重要的project了，因为本身这门课就是机器学习领域中的很重要的前沿方向。

做了三次课程作业，和一次大project。但课程拿了B+。

课程作业：

- 环境：使用**python语言**，使用**nltk**分析工具
- 任务：
  - 使用nltk分析语料库中词频
  - 学会使用正则匹配
  - 实现语料库词性标记，使用朴素贝叶斯方法实现简单名字性别分类器

Project：

- 这个含金量应该还可以，虽然最后没有拿到课程A
- 环境：使用python语言，seq2seq神经网络模型
- 任务：
  - 使用seq2seq模型结合attention的机制，使用康奈尔大学电影学院对白语料库作为数据集，训练一个对话机器人。
  - 有论文，可以看一下论文。



### 大三下

#### 计算机体系结构 ⭐⭐⭐

这个实验是硬件语言，我感觉可以增加多样性，也是计算机专业课，工作量也挺大的。有三次大的project。

Projects：

- 环境：使用**verilog硬件语言**，使用**vivado**软件。

- 任务：
  - 实现32位ALU设计，并且使用仿真模拟测试所有功能。
  - 实现单周期处理器MIPS设计，实现24条指令，实现模块化测试和整合仿真模拟测试
  - 实现多周期处理器MIPS设计，实现多条指令，实现模块化测试和整合仿真模拟测试



#### 模式识别与机器学习 ⭐⭐⭐⭐

这个课程很关键，应该是人工智能的先导课。这门课主要讲机器学习的各种数学理论知识。但我拿了B+。。最后的project没有太认真做，不过也是很好的选题，如果不细看的话还行。

Project老师是让我们去参加[AIcure比赛](https://www.aicures.mit.edu/)，我们不需要报名，直接进行课程作业报告。

Project：

- 环境：使用python语言
- 任务：
  - 给出若干种化合物的SMILES表示，要求判断其是否对Covid-19具有抗性，输出为0或者1，是一个2分类 问题。
  - 这是有一点（也可以说没有用）的实际问题解决的，所以可能国外会比较青睐。是想要从已有的药学库中选择对covid19有抗性的药物。
  - 我们使用GCN和MPNN两种图模型，根据比赛给的数据集训练，进行了10折交叉验证，获得较好结果。



#### 软件工程 ⭐⭐⭐⭐⭐

小组合作项目，开发了一个网页（没有上线部署，本地运行），六人小组项目。这个**含金量比较高**，因为是小组合作，而且开发迭代了三个sprint周期，最终成品是有优美前端页面和完整框架代码的。具体项目地址在[这里](https://github.com/EZ-hwh/Software-Engineering)。

Project：

- 环境：前端Vue.js + 后端 Django 框架开发，使用vue.js和python语言
- 任务：
  - 完成一个宗旨为时间管理的线上学习平台 LIFELINE。
  - 分了3个sprint开发周期，每个周期为一个月。
  - 我担任组长，负责了前端主页开发、前后端链接、人员分工、前后端代码汇总、前端风格汇总和修改、最终sprint文档撰写和上台展示等工作。



#### 数字信号处理 ⭐⭐⭐⭐⭐

薛向阳老师的课程，这门课更像工科课程，偏向于微电子和电工专业的课程，是我们的选修课。但我这节课表现比较出色。有一个project，也可以作为人工智能方向的project。

Project：

- 环境：python语言，pytorch深度学习框架
- 任务：
  - 实现20个孤立词语语音的识别，里面10个中文，10个英文
  - 数据集来源于班级上所有人每人录音20个词语，每个词语20次。
  - 训练集达到100%准确率，测试集达到96.5%准确率。
- 创新点：
  - 参照DFCNN结构，先将语音预处理后生成语谱图，对语谱图进行三维图像分类。将语音分类问题转换为图像分类问题。
  - 使用VGG16网络结构。













