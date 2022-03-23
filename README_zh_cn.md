<p align="center">
    <img src="https://s4.ax1x.com/2022/01/16/7tP1V1.png" alt="logo" width="256" height="256">
</p>



<h3 align="center">JEngine</h3>

<p align="center">
  使Unity开发的游戏支持热更新的解决方案。
    <br>
  <a style="text-decoration:none">
    <img src="https://img.shields.io/github/license/JasonXuDeveloper/JEngine" alt="license" />
  </a>
  <a style="text-decoration:none">
    <img src="https://img.shields.io/github/last-commit/JasonXuDeveloper/JEngine" alt="last" />
  </a>
  <a style="text-decoration:none">
    <img src="https://img.shields.io/github/issues/JasonXuDeveloper/JEngine" alt="issue" />
  </a>
  <a style="text-decoration:none">
    <img src="https://img.shields.io/github/languages/top/JasonXuDeveloper/JEngine" alt="topLanguage" />
  </a>
  <a style="text-decoration:none">
    <img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FJasonXuDeveloper%2FJEngine.svg?type=shield" alt="status" />
  </a>
  <a style="text-decoration:none">
    <img src="https://www.codefactor.io/repository/github/jasonxudeveloper/jengine/badge" alt="badge" />
  </a>
  <br>
  <br>
  <a href="https://xgamedev.uoyou.com/"><strong>框架文档 »</strong></a>
  <br>
  ·
  <br>
  <a href="https://github.com/JasonXuDeveloper/JEngine/">框架首页 »</a>
</p>


# JENGINE v0.7.0

JEngine是针对Unity开发者设计的**开箱即用**的框架，封装了强大的功能，小白也能**快速上手**，**轻松制作**可以**热更新的游戏**

```master```分支为开发者认为的可以正常使用，不会有太大问题的最新版本，建议使用，功能最为强大（同时修复了0.6和0.5版本的bug）；

```0.6.x```分支目前大部分商业项目正在使用，<u>内容完善，文档视频充足，不会再进行任何更新或维护</u>；

```0.5.x```分支有部分商业项目正在使用，<u>不会再进行更新或维护</u>；

```development```分支为开发分支，欢迎fork后在该分支进行修改并PR，也欢迎提交issue！




> QQ群: [921271552](https://jq.qq.com/?_wv=1027&k=cF4hODjW)
>
> 已有项目使用JEngine热更新，并成功上架iOS



## 下载方式（非常重要）

> 因为JEngine使用了Git的Submodule模块来安装子模块，下载本框架源码不推荐直接从网站下载zip，目前有3种下载方式：

1. 方法一，直接下载zip，然后进入UnityProject/Assets/Dependencies，解压里面的zip（zip下载必看）

2. 方法二，先git clone再安装子模块

   ```bash
   git clone git@github.com:JasonXuDeveloper/JEngine.git
   cd JEngine
   git submodule init
   git submodule update
   ```

3. 方法三，git clone的时候顺带安装子模块（推荐）

   ```bash
   git clone git@github.com:JasonXuDeveloper/JEngine.git --recursive
   ```

> 注，这里的github地址可以换为gitee地址
>
> 如果安装submodule的时候报错了，则需要配置Github（或Gitee）的ssh key



## 框架相关

| 主题                                 | 地址                                                         |
| ------------------------------------ | ------------------------------------------------------------ |
| 框架文档：短时间快速精通框架必看     | [点击跳转](https://xgamedev.uoyou.com/)                      |
| 知乎文章：JEngine介绍                | [点击跳转](https://zhuanlan.zhihu.com/p/218105381)           |
| 知乎文章：JEngine热更DLL内存加密方案 | [点击跳转](https://zhuanlan.zhihu.com/p/356693738)           |
| 项目原地址                           | [GitHub地址](https://github.com/JasonXuDeveloper/JEngine)    |
| 国内快速下载地址                     | [Gitee跳转](https://gitee.com/JasonXuDeveloper/JEngine)      |
| QQ群                                 | [点击加入](https://jq.qq.com/?_wv=1027&k=cF4hODjW)           |
| 作者Unity社区主页                    | [点击跳转](https://developer.unity.cn/u/jie-1ees3?tab=article) |
| 作者Unity微社区频道                  | [点击加入](https://fanbook.mobi/IBVIPF3D)                    |

  ## 框架上线项目

  > 若您的项目使用了JEngine，欢迎联系作者，作者很乐意把您的作品展示出来~

| <img src="https://img.tapimg.com/market/lcs/b2d125432dffa4741c929ddceb3bf95f_360.png?imageMogr2/auto-orient/strip" alt="g1" width="128" height="128" /> | <img src="https://img.tapimg.com/market/lcs/378c87731ce06ab8338977c90761a187_360.png?imageMogr2/auto-orient/strip" alt="g2" width="128" height="128" /> |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| <p align="center">[爱丽丝造梦空间](https://www.taptap.com/app/224117)</p> | <p align="center">[肝到发慌](https://www.taptap.com/app/225175)</p> |



## 近期star趋势

[![Stargazers over time](https://starchart.cc/JasonXuDeveloper/JEngine.svg)](https://starchart.cc/JasonXuDeveloper/JEngine)

## JEngine优势

JEngine的目的是针对游戏开发者提供**精简、美观且高效**的**代码**功能，并且使游戏开发者**更加轻松的制作游戏**

市面上的**Unity热更新框架**，**没有**一个**比JEngine**的**学习成本低**，使用**难度较大**，需要耗费**大量时间去入门、跑通框架**；

而**JEngine入门快的话可能几分钟即可，最多几小时即可跑通框架**，**简单易用**、**傻瓜式操作**，**不需要去关注管理热更资源**，**不需要关注任何热更新的底层**，**只管写游戏代码，做游戏场景即可**！

### 老项目

对于需要将不包含热更新的老项目改造为可热更的项目，JEngine是不二之选。

熟悉框架流程通常只需要数日，接着仅需对需要热更的资源分类整理进入对应文件夹，其次将需要热更的代码复制进入热更工程，最后再把全部用MonoBehaviour挂在Inspector上的脚本通过ClassBind重新拖拽（可以自己实现个工具简化该流程）即可。

通常情况下接入只需1个月左右，且80%的业务代码无需修改，15%的业务代码只需优化，最后5%的业务代码是意外情况才需要进行修改的。同时，如果项目有拖拽MonoBehaviour到GameObject的习惯，JEngine现成的解决方案会让你事半功倍，让你的项目轻松支持热更新！

### 新项目

JEngine非常适合中小型项目，尤其是对于独立游戏开发者而言，该框架方便快捷，且功能强大，开发者可以在短时间驾驭，以极其小的代价掌握热更新，基本无需学习热更新原理。

对于新项目而言，只需要拉取一份JEngine源码，然后再往里面导入各种插件和SDK，最后制定自己的项目规范就可以开始愉快的制作游戏了，且不同于其他热更新框架，JEngine更加注重开发效率，完善了在编辑器对热更工程进行操作的体验，因此在编辑器下进行开发的效率远胜于其他热更新框架。

### 总结

**JEngine**文档齐全，维护频繁，只要有issue，通常3日内必定解决，同时底层的热更源码经过大量上线项目验证，无需担心质量、性能、效率等问题！

**如果你觉得JEngine对你有帮助，请给该框架一个Star！**

​    

  ## v0.7.0 最新功能

  - 依赖代码**模块化**（更规范）
  - 支持**离线模式**（无需架设服务器即可打游戏包测试）
  - 改善**开发流程**（一系列的开发时的体验优化）
  - 框架**代码解耦**（更轻量，开箱即用）
  - 框架**底层优化**（更卓越的性能）
  - LitJson及Protobuf**优化及维护**（更稳定的序列化插件）
  - 修复0.6.3出现的**全部Issue**（更少bug，更强大）
  - 更多**Demo**（更完善，使用起来更容易驾驭）
  - 新增**可扩展验证器**（新功能）
  - 便捷**UI扩展工具**（新功能）
  - **ILRuntime2.0**（更强大的性能，同时解决很多曾经的bug）
  - **JPrefab升级**（支持同步/异步创建，支持批量销毁）
  - **JBehaviour新周期**（类似MonoBehaviour的OnEnable和OnDisable）

  [点击此处查看历史版本功能（英文）](CHANGE.md)

  

  ## JEngine专业版

  JEngine专业版现已推出，大幅度提高开发效率和底层性能，可以根据需求进群联系作者进行购买，可以补差价升级

  （满1K star之后会进行直播讲解专业版，同时会降价到39/299/799，维持一个月，之后变为99/599/999）

  （开源版功能对于小项目开发和正常使用足矣，可以自行魔改来实现更完善的功能，或购买体验版进行尝试，好用再升级一年或永久版！提倡先用开源版开发，觉得好用再升级专业版，请理性消费！）

|                                           | 99元（体验版） | 399元（一年版） | 899元（永久版） |
| ----------------------------------------- | -------------- | --------------- | --------------- |
| 有效时长                                  | 永久           | 一年            | 永久            |
| 是否包含后续更新                          | 否             | 是              | 是              |
| 是否包含Bug修复                           | 否             | 是              | 是              |
| 是否包含专业版框架问题咨询                | 否             | 是              | 是              |
| 免费远程框架问题解决次数                  | 0次            | 1次             | 3次             |
| 热重载                                    | 支持           | 支持            | 支持            |
| ClassBind智能提示                         | 不支持         | 支持            | 支持            |
| ClassBind对数组赋值                       | 支持           | 支持            | 支持            |
| ClassBind可视化管理面板                   | 不支持         | 支持            | 支持            |
| 自定义ClassBind自动匹配正则               | 不支持         | 支持            | 支持            |
| ClassBind支持根据字段名自动匹配gameObject | 不支持         | 支持            | 支持            |
| 运行时Inspector支持显示数组               | 支持           | 支持            | 支持            |
| 自行扩展Inspector运行时序列化             | 不支持         | 支持            | 支持            |
| Inspector下对Button添加热更事件           | 不支持         | 支持            | 支持            |
| 底层优化                                  | 部分           | 全面            | 全面            |

​    

  ## 推荐项目

  - [IFramework](https://github.com/OnClick9927/IFramework) - Simple Unity Tools
  - [QFramework](https://github.com/liangxiegame/QFramework) - Your first K.I.S.S Unity 3D Framework.

