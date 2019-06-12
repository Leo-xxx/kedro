## Github项目推荐 | Kedro：生产级机器学习开源代码库

AI研习社 [AI研习社](javascript:void(0);) *今天*

![img](https://mmbiz.qpic.cn/mmbiz_jpg/bicdMLzImlibRiboYcgtAAFwZvvLPUlRkFmiaQ8aCfWBsYib2ic7uVBLAHBtL8m8gYWxDLRdVWaAoASYXjjYclph6NlQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

by **quantumblacklabs**

Kedro是一个Python库，可用于构建强大的生产就绪数据和分析管道

![1559720141457810.jpg](https://mmbiz.qpic.cn/mmbiz_jpg/bicdMLzImlibTxibPhVCYy69wUcoMougmMbAibdbjGrEbc1libllbw8XqKPS4tjhvplvdYDKI4ERLfM7hZI7MLatjnQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![1559720214968311.png](https://mmbiz.qpic.cn/mmbiz_png/bicdMLzImlibTxibPhVCYy69wUcoMougmMbgRQdwp7kIweGBm4MpwnjzkVzQxaeiapL8aKaSQhyxWqtX9vZ7RvGGRw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## Kedro是什么？

> “数据管道的中心。”

Kedro是一个工作流开发工具，可帮助你构建强大，可扩展，可部署，可重现和版本化的数据管道。 我们提供标准的方法，你可以：

- 花更多时间来构建数据管道
- 不用担心如何编写生产就绪代码
- 标准化团队在整个项目中的协作方式
- 工作效率更高

Kedro最初由 Aris Valtazanos 和 Nikolaos Tsaousis 设计，以解决他们在项目工作中遇到的挑战。

## 如何安装Kedro？

由于Kedro是一个Python包，因此只需运行以下命令即可安装：

- 

```
pip install kedro
```

有关更详细的安装说明，包括如何设置Python虚拟环境等，请查看安装指南。

## Kedro的主要特点是什么？

### 1.项目模板和编码标准

- 标准且易于使用的项目模板
- 配置证书，日志记录，数据加载和Jupyter笔记本/实验室的配置
- 使用pytest进行测试驱动的开发
- 集成Sphinx以生成记录良好的代码

## 2.数据抽象和版本控制

- 将计算层与数据处理层分离，包括支持不同的数据格式和存储选项
- 为你的数据集和机器学习模型进行版本控制

## 3.模块化和管道抽象

- 支持纯Python函数，节点，将大块代码分成小的独立部分
- 自动解析节点之间的依赖关系
- （即将推出）使用Kedro-Viz可视化数据管道，Kedro-Viz是一个显示Kedro项目管道结构的工具
- *注意：*阅读我们的常见问题解答，了解我们与Airflow和Luigi等工作流程管理器的区别。

### 4.功能可扩展性

- 将命令注入Kedro命令行界面（CLI）的插件系统

- （即将推出）官方支持的插件列表：

- - Kedro-Airflow，在部署到工作流调度程序Airflow之前，可以轻松地在Kedro中对数据管道进行原型设计
  - Kedro-Docker，用于在容器内包装和运输Kedro项目的工具

- Kedro可以部署在本地，内部部署和云（AWS，Azure和GCP）服务器或集群（EMR，Azure HDinsight，GCP和Databricks）

![1559721562907006.png](https://mmbiz.qpic.cn/mmbiz_png/bicdMLzImlibTxibPhVCYy69wUcoMougmMb1uJMYyhwCq31IVqaVNDoCeu5SIOI4LUicu4n8B11hTqbdFnZDXMAFmg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*使用Kedro-Viz进行随机管道可视化（即将推出）*

## 如何使用Kedro？

我们的文档说明提供了以下内容：

- 典型的Kedro工作流程
- 如何设置项目配置
- 构建第一个管道
- 如何使用kedro_cli.py提供的CLI（kedro new，kedro run，...）

> *注意：*CLI是一个方便的工具，可以运行kedro命令，但你也可以使用python -m kedro调用Kedro CLI作为Python模块

## 如何找到Kedro文档？

以下CLI命令将在浏览器中打开当前版本Kedro的文档：

- 

```
kedro docs
```

你可以点击此处查看最新稳定版本的文档。入门教程、常见问题解答等，请查看：

- Getting started
- Tutorial
- FAQ

## 如何更新Kedro？

我们使用语义版本控制。 安全升级的最佳方法是查看我们的发行说明，了解任何值得注意的重大更新。

安装Kedro后，你可以按如下方式检查你的版本：

- 

```
kedro --version
```

如果想将Kedro升级到其他版本，只需运行：

- 

```
pip install kedro -U
```

## License

Kedro根据Apache 2.0许可证获得许可。

**Github项目地址：**

[https://github.com/quantumblacklabs/kedro](https://mp.weixin.qq.com/s?__biz=MjM5ODU3OTIyOA==&mid=2650676995&idx=2&sn=750380f63cb13eafea2dfe0a0b5ca259&chksm=bec2227089b5ab66664a02ed0b4fd5896bc522925295b705d6820f62dc8b1c98f220c16fc721&mpshare=1&scene=1&srcid=&key=45382ee80ea50780f7d7f935b5cb1e39df92006dc004d31a4e48666870e33532cd2bb50164dc3fbb9841e94f33bad85f2df8621be6a701846f06402b80086600985a2e6e57f02427f3e7e00bb7164266&ascene=1&uin=MjMzNDA2ODYyNQ%3D%3D&devicetype=Windows+10&version=62060833&lang=zh_CN&pass_ticket=BUWUYnKfJ56vNqQot1aK1RyBMuUIKZVt8%2BLodOvPcOenM5CSUrKLMK7C%2FjdIemJw)

![img](https://mmbiz.qpic.cn/mmbiz_jpg/bicdMLzImlibTyAbZ2YnxvF3mswjVtnXAseVEfrE0D447QjEWham7tVf3iaibibwNrj2Wrbmat3ydmibcT0wkibvFI8Eg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![img](https://mmbiz.qpic.cn/mmbiz_gif/bicdMLzImlibRAS3Tao2nfeJk00qqxX3axIgPV3yia4NPESGdUJEM9vsfw1O4Dg1iat7lVNAmbCMY65ia2pzfBXm5kg/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1) 点击 **阅读原文** ，进入技术交流小组，查看更多Github项目推荐

[阅读原文](https://mp.weixin.qq.com/s?__biz=MjM5ODU3OTIyOA==&mid=2650676995&idx=2&sn=750380f63cb13eafea2dfe0a0b5ca259&chksm=bec2227089b5ab66664a02ed0b4fd5896bc522925295b705d6820f62dc8b1c98f220c16fc721&mpshare=1&scene=1&srcid=&key=45382ee80ea50780f7d7f935b5cb1e39df92006dc004d31a4e48666870e33532cd2bb50164dc3fbb9841e94f33bad85f2df8621be6a701846f06402b80086600985a2e6e57f02427f3e7e00bb7164266&ascene=1&uin=MjMzNDA2ODYyNQ%3D%3D&devicetype=Windows+10&version=62060833&lang=zh_CN&pass_ticket=BUWUYnKfJ56vNqQot1aK1RyBMuUIKZVt8%2BLodOvPcOenM5CSUrKLMK7C%2FjdIemJw##)







微信扫一扫
关注该公众号