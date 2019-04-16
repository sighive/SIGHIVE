## VSG设计蓝图

### 1. 探索阶段, 2018.6-2018.9 (已完成)
**阶段目标 : 确定要使用的技术与工具**

学习并尝试使用Vulkan、C++新标准、 以及可能会用到的第三发库。尝试多种不同的方法来进行场景图的设计与实现。探索阶段整理的资料如下：

* [设计原则与哲学](docs/Design/DesignPrinciplesAndPhilosophy.md)
* [上层设计决策](docs/Design/HighLevelDesignDecisions.md)
* [探索阶段报告](docs/ExplorationPhase/VulkanSceneGraphExplorationPhaseReport.md)
* [感兴趣的领域](docs/ExplorationPhase/AreasOfInterest.md)
* [第三方库资源](docs/ExplorationPhase/3rdPartyResources.md)

### 2. 原型阶段, 2018.10-2018.12 (已完成)
**阶段目标 : 进行核心类、库、测试程序的快速原型开发，从而搭建VSG库的基本框架。**

原型阶段整理的资料如下:

* [原型阶段工作计划](docs/PrototypePhase/Workplan.md)
* [原型阶段报告](docs/PrototypePhase/PrototypePhaseReport.md)

### 3. 核心开发阶段, 2019.1-2019暑期
**阶段目标: VSG最终接口的创建与实现**

以原型阶段的工作成果为指南，完成VSG库的最终版，提供可靠的接口与实现。

* 最终版VSG库的开发
* 支持多线程数据库分页
* 支持多线程查看器、剔除和调度遍历
* 支持多管线渲染
* 支持大型全球数据库 (对场景图变换的双重支持)
* 开发插件库，提供以下功能:
    * 支持主流图像格式
    * 支持主流3D模型格式, 包括FBX, glTF.
    * 支持PBR着色器
    * 支持文本渲染
* 开发程序与数据的测试套件
* 支持RTX的网格着色器(Mesh Shaders)与光线追踪
* 移植到iOS平台

### 4. 发行阶段, 2019秋
**阶段目标: 针对实际应用进行VSG库的测试，完善与发行VSG的第一个稳定版本.**

* 完善VSG的接口与实现
* 与VSG应用开发者建立关系，并使他们参与到测试工作中
* 创建VSG的使用教程与示例
* 测试，调试，改善，并发行VSG 1.0.0 版本!
