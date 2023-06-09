# UMl-Software-Modeling
UML软件建模基础
# UML软件建模

[TOC]



## 一、认识软件工程

### 1.1.认识软件与软件工程

------

- **任务目录**：

  - **软件的概念**

  - **软件的分类**

  - **软件危机**

  - **软件工程的概念**

  - **软件工程的方法**


------



#### **软件的概念**

- **软件的阶段：**

  - 第一阶段：软件=程序（20世纪50年代-60年代）

  - 第二阶段：软件=程序+文档（20世纪60年代-70年代）

  - 第三阶段：软件=程序+文档+数据（20世纪50年代-20世纪末）

  - 第四阶段：软件=程序+文档+数据+服务（当今21世纪）


**软件与硬件是计算机系统中相互依存的两个重要组成部分。**

- **软件的特点：**

  - **软件不具备明显的物理特性**

  - **软件对计算机系统有一定的依赖性**

  - **软件是被开发或设计出来的**

  - **软件在使用过程中，没有磨损和老化问题**

  - **软件开发过程中，具有复杂性和不确定性****


#### 软件的分类

- **按功能分类：**
  - 系统软件
    - 计算机系统不可缺少的组成部分，能使用计算机各个部件、其他软件协调工作，如操作系统（Windows、Linux）、驱动程序、通讯处理程序等
  - 支撑软件
    - 用于开发软件的工具性软件，如各种开发软件包（JDK）和专有工具软件等。
  - 应用软件
    - 在某个领域中，为解决某特定目的服务而开发的一类软件，如电子商务系统、电子政务系统、企业管理系统等。
- **按版权分类：**
  - 商业软件
    - 版权受法律保护，经授权才能使用，并且需付费购买的软件。
  - 共享软件
    - 与商业软件类似，但可以“先适用再付费”，
  - 自由软件
- **按服务对象分类：**
  - 通用软件
  - 定制软件

#### 软件危机

- **概念：**
  - **软件危机是指在计算机软件的开发与维护过程中所遇到的一系列严重问题。**

- **软件危机主要体现在两个方面：**
  - **一是如何开发软件，以满足对软件日益增长的需求**
  - **二是如何维护软件，以使软件能提供高质量的服务**


#### **软件工程的概念**

- **定义：**
  - 1983年，IEEE给软件工程的定义是：**软件工程是开发、运行、维护和修复软件的系统方法**

- **涉及的两个方面：**
  - **软件开发技术**和**软件工程管理**两个方面


#### 软件工程的方法学

- **组成三要素：**由**方法**、**工具**、**过程**构成
- **主要的两种软件工程方法学**
  - **传统方法学**：
    - 传统方法学也称为生命周期方法学或结构化法
    - 特点：
      - 自顶向下，逐步求精（不适用于前期需求不明确，需求变化频繁的软件项目）
    - 缺点：在开发前期，就需要了解详细的、明确的用户需求，这往往是不现实的，也难于适应需求变化频繁的系统。
  - **面向对象方法学**：利用抽象、分类、继承、聚合、封装等人类常用思维习惯分析和设计系统，多次反复迭代的演化过程。（适用于软件规模庞大、需求复杂且变化频繁）

### 1.2.认识软件的生命周期

**任务目录**：

1. **软件定义时期**
2. **软件开发时期**
3. **软件运行维护时期**

#### 软件定义时期

- **主要任务**：
  - 确定软件系统“要解决什么”，确定软件工程必须达到的总目标

- **划分**：
  - **问题定义**
    - 通过用户的前期调研，确定系统要解决的问题、目标和规模，形成用户初步需求报告。该阶段主要解决软件系统“是什么”或“要解决什么”的问题

  - **可行性研究**
    - 根据用户确定的初步需求报告，结合现实项目条件，从技术、财务、组织、经济、社会、风险等方面进行可行性以及投资必要性等方面的分析，形成可行性分析报告。该阶段主要解决软件系统“可行吗？”的问题

  - **需求分析**
    - 软件需求是用户对软件系统在功能、性能、约束等方面的期待。需求分析阶段主要完成软件系统的功能需求分析、非功能性需求分析（如可用性、性能、可靠性等）、设计约束条件分析（如操作系统的要求、数据库平台的要求等），最后形成软件需求规划书说明书。该阶段主要解决软件系统的“做什么” “ 做得怎么样”的问题。


#### 软件开发时期

- **主要任务**：
  - 完成**软件设计**，**软件实现**（编程）和**软件测试**的工作。

- **划分**：

  - **概要设计**：总体设计、架构设计。
    - **该阶段的成果：定义各功能模块的接口，实现数据库的概念结构设计和逻辑结构设计，定义软件系统的边界，描述系统设计的约束**

  - **详细设计**：解决具体如何做。
    - **该阶段成果：各模块的详细设计规格说明书**

  - **编码和单元测试**：编码将设计转化为程序代码，同时对已经编码的模块或单元进行测试，以验证**模块功能及接口**与**详细规格说明书**的一致性。
    - **该阶段的成果包括：程序代码和单元测试文档**

  - **综合测试**：检查是否符合用户需求和设计需求。综合测试主要包括：**集成测试**和**验收测试**。
    - 该阶段的成功包括：**测试文档**和**修改文档**


  #### 软件运行维护时期

- **进行4类维护**：
  - **改正性维护**
  - **适应性维护**
  - **完善性维护**
  - **预防性维护**

- **主要成果**：**软件运行记录和软件维护记录等文档资料**

### 1.3.认识软件过程模型

#### 六种常用模型

##### **瀑布模型：**

- **概述：**
  - 瀑布模型也称生命周期模型，是使用范围最广泛、最经典的一种软件工程模型

- **特点**：
  - 严格的顺序性和依赖性
  - 规范的文档化
- **优点**：
  - 利于软件过程的管理和控制

- **缺点**：
  - 只适用于需求明确和变更较少的项目


![](img\第一章\瀑布模型.png)

##### **v模型：**

- **概述：**

  - RAD (Rap Application Development,快速应用开发) 模型是软件开发过程中的一个重要模型，由于其模型构图形似字母V，所以又称软件开发的V模型。它通过开发和测试同时进行的方式来缩短开发周期，提高开发效率。

- **特点：**

  - 简单易用，开发步骤和测试步骤明确。
  - 明确了测试过程与开发过程的对应关系
  - 强调了测试的重要性，增强了软件全过程的质量意识。
  - 对开发过程和测试过程中的送代和重做活动并没有真实反馈。

  

- **优点：**

  - 相对于瀑布模型，V模型测试能够尽早的进入到开发阶段。

- **缺点：**

  - 虽然测试尽早的进入到开发阶段，但是真正进行软件测试是在编码之后，这样忽视了测试对需求分析，系统设计的验证，时间效率上也大打折扣。


![](img\第一章\V模型.png)

- ​	**V模型大体可以划分为不同的阶段步骤：**既**需求分析、概要设计、祥细设计、编码、单元测试、集成测试、系统测试、验收测试**。

  -   **需求分析：**
      - 既你首先要明确客户需要的是什么，需要软件作成什么样子，需要有那几项功能，这一点上比较关键的是分析师和客户沟通时的理解能力与交互性。要求分析师能准确的把客户所需要达到的功能，实现方式，等表述出来，给出分析结果，写出规格文档说明书。

  -   **概要设计：**
      - 主要是架构的实现，指搭建架构、表述各模块功能、模块接口连接和数据传递的实现等项事务。
  -   **祥细设计：**
      - 对概要设计中表述的各模块进行深入分析，对各模块组合进行分析等，这一阶段要求达到伪代码级别，已经把程序的具体实现的功能，现象等描述出来。
  -   **编码：**
      - 按照祥细设计好的模块功能表，编程人员编写出实际的代码。
  -   **单元测试：**
      - 按照设定好的最小测试单元进行按单元测试，主要是测试程序代码，为的是确保各单元模块被正确的编译，单元的具体划分按不同的单位与不同的软件有不同，比如有具体到模块的测试，也有具体到类，函数的测试等。
  -   **集成测试：**
      - 经过了单元测试后，将各单元组合成完整的体系，主要测试各模块间组合后的功能实现情况，以及模块接口连接的成功与否，数据传递的正确性等。是软件系统集成过程中所进行的测试，其主要目的是检查软件单位之间的接口是否正确。它根据集成测试计划，一边将模块或其他软件单位组合成越来越大的系统，一边运行该系统，以分析所组成的系统是否正确，各组成部分是否合拍。
  -   **系统测试：**
      - 经过了单元测试和集成测试以后，我们要把软件系统搭建起来，按照软件规格说明书中所要求，测试软件其性能功能等是否和用户需求相符合，在系统中运行是否存在漏洞，等
  -   **验收测试：**
      - 主要就是用户在拿到软件的时候，会根据前边所提到的需求，以及规格说明书来做相应测试，以确定软件达到符合效果的。


##### **快速原型模型：**

- **概述：**
  - 快速原型模型允许在需求分析阶段对软件的需求进行初步而非完全的分析和定义，快速设计开发出软件系统的原型，该原型向用户展示待开发软件的全部或部分功能和性能；用户对该原型进行测试评定，给出具体改进意见以丰富细化软件需求；开发人员据此对软件进行修改完善，直至用户满意认可之后，进行软件的完整实现及测试、维护。
- **特点：**
  - 软件开发过程基本上是线性的顺序开发。
  - 原型建立以后的阶段之间不带反馈坏。
  - 通过送代的过程快速建立与用户需求一致的原型。
  - 减少开发活动的盲目性和需求不确定性。
  - 开发的系统能较好地满足用户需求，修改较小。

- **优点：**
  - 克服瀑布模型的缺点，减少由于软件需求不明确带来的开发风险。
  - 这种模型适合预先不能确切定义需求的软件系统的开发。
- **缺点：**
  - 所选用的开发技术和工具不一定符合主流的发展；
  - 快速建立起来的系统结构加上连续的修改可能会导致产品质量低下。
  - 使用这个模型的前提是要有一个展示性的产品原型，因此在一定程度上可能会限制开发人员的创新。

##### **增加模型：**

- **概述：**
  - **增量模型也称渐增模型。**使用增量模型开发软件时，把软件产品作为一系列的增量构件来设计、编码、集成和测试。每个构件由多个相互作用的模块构成，并且能够完成特定的功能使用增量模型时，第一个增量构件往往实现软件的基本需求，提供最核心的功能**把软件产品分解成增量构件时，唯一必须遵守的约束条件是，当把新构件集成到现有构件中时，所形成的产品必须是可测试的**
- **特点：**
  - 把瀑布模型的顺序特征与快速原型法的迭代特征相结合
  - 将软件看作一系列相互联系的增量，在开发过程的各次迭代中，每次完成其中的一个增量

- **优点：**
  - 能在较短的时间内向用户提交可完成部分工作的产品
  - 将待开发的软件系统模块化，可以分批次地提交软件产品，使用户可以及时了解软件项目的进展
  - 以组件为单位进行开发降低了软件开发的风险。一个开发周期内的错误不会影响到整个软件系统
  - 开发顺序灵活。开发人员可以对组件的实现顺序进行优先级排序，先完成需求稳定的核心组件。当组件的优先级发生变化时，还能及时地对实现顺序进行调整
- **缺点：**
  - 由于各个构件是逐渐并入已有的软件体系结构中的，所以加入构件必须不破坏已构造好的系统部分，这需要软件具备开放式的体系结构
  - 在开发过程中，需求的变化是不可避免的。增量模型的灵活性可以使其适应这种变化的能力大大优于瀑布模型和快速原型模型，但也很容易退化为边做边改模型，从而是软件过程的控制失去整体性
  - 如果增量包之间存在相交的情况且未很好处理，则必须做全盘系统分析，这种模型将功能细化后分别开发的方法较适应于需求经常改变的软件开发过程

##### **螺漩模型：**

- **定义：**
  - [螺旋模型](https://baike.baidu.com/item/螺旋模型/9817820)是一种演化[软件开发过程](https://baike.baidu.com/item/软件开发过程/3758917)模型，它兼顾了[快速原型](https://baike.baidu.com/item/快速原型/7432267)的[迭代](https://baike.baidu.com/item/迭代/8415523)特征以及[瀑布模型](https://baike.baidu.com/item/瀑布模型/9817778)的系统化与严格监控。螺旋模型最大的特点在于引入了其他模型不具备的风险分析，使软件在无法排除重大风险时有机会停止，以减小损失。同时，在每个迭代阶段构建原型是螺旋模型用以减小风险的途径
  - 螺旋模型是快速原型模型以进化的开发方式为中心，在每个项目阶段使用[瀑布模型法](https://wiki.mbalib.com/wiki/瀑布模型法)。该模型的每一个周期都包括需求定义、风险分析、工程实现和评审4个阶段，由这4个阶段进行迭代。软件开发过程每迭代一次，软件开发又前进一个层次。


- **螺漩模型四个阶段：**
  - 制定计划：确定软件目标，选定实施方案，弄清项目开发的限制条件
  - 风险分析：分析评估所选方案，考虑如何识别和消除风险
  - 实施工程：实施软件开发和验证
  - 客户评估：评价开发工作，提出修正建议，制定下一步计划
- **特点：**
  - 螺旋模型在“瀑布模型”的每一个开发阶段前引入一个非常严格的风险识别、风险分析和风险控制，它把软件项目分解成一个个小项目。每个小项目都标识一个或多个主要风险，直到所有的主要风险因素都被确定
  - 螺旋模型强调风险分析，使得开发人员和用户对每个演化层出现的风险有所了解，继而做出应有的反应，因此特别适用于庞大、复杂并具有高风险的系统
- **优点：**
  - 对可选方案和约束条件的强调有利于已有软件的重用，也有助于把软件质量作为软件开发的一个重要目标
  - 减少了过多测试（浪费资金）或测试不足（产品故障多）所带来的风险
  - 在螺旋模型中维护只是模型的另一个周期，在维护和开发之间并没有本质区别
- **缺点：**
  - 采用螺旋模型需要具有相当丰富的风险评估经验和专门知识，在风险较大的项目开发中，如果未能够及时标识风险，势必造成重大损失
  - 过多的迭代次数会增加开发成本，延迟提交时间

##### **喷泉模型：**

- **定义：**
  - 喷泉模型是一种以用户需求为动力，以对象为驱动的模型，主要用于描述面向对象的软件开发过程。该模型认为软件开发过程自下而上周期的各阶段是相互重叠和多次反复的，就像水喷上去又可以落下来，类似一个喷泉。各个开发阶段没有特定的次序要求，并且可以交互进行，可以在某个开发阶段中随时补充其他任何开发阶段中的遗漏。

- **特点：**
  - 　喷泉模型不像瀑布模型那样，需要分析活动结束后才开始设计活动，设计活动结束后才开始编码活动。该模型的各个阶段没有明显的界限，开发人员可以同步进行开发。其优点是可以提高软件项目开发效率，节省开发时间，适应于面向对象的软件开发过程。

- **优点：**
  - 喷泉模型不像瀑布模型那样，需要分析活动结束后才开始设计活动，设计活动结束后才开始编码活动。该模型的各个阶段没有明显的界限，开发人员可以同步进行开发。其优点是可以提高软件项目开发效率，节省开发时间，适应于面向对象的软件开发过程。

- **缺点：**
  - 　由于喷泉模型在各个开发阶段是重叠的，因此在开发过程中需要大量的开发人员，因此不利于项目的管理。此外这种模型要求严格管理文档，使得审核的难度加大，尤其是面对可能随时加入各种信息、需求与资料的情况。


------

### 项目回顾

本项目介绍了**软件**、**软件工程**、软件生命周期、**软件过程模型**等软件工程领域中的**基本概念**和**基础知识**。涉及的关键知识和关键技能如下：

- **关键知识：**
  - **软件：**软件的概念、软件的特点及软件的分类。
  - **软件工程：**软件危机的产生和表现，软件工程的概念，传统方法学和面向对象方法学。
  - **软件生命周期：**软件生命周期的划分，以及各个阶段的主要工作任务。
  - **软件过程模型：**瀑布模型、V模型、快速原型模型、增量模型、螺漩模型、喷泉模型的基本思想、特点和优点。
- **关键技能：**
  - 区别**软件**和**硬件**，以及二者的**关联**和特点，列举当今市场主流的**软件产品**和**硬件产品**，并且分别对这些软硬产品进行分类。
  - 针对某具体软件开发项目，**描述其生命周期及各个阶段的主要工作和成果**。
  - 针对某具体软件开发项目，**分析其开发过程中所采用的过程模型**。

------



## 二、面向对象方法与软件建模

------

- **任务目录**：

  - **2.1：认识面向对象**


  - **2.2：了解面向对象的基本概念**


  - **2.3：软件建模**

------



### 2.1、认识面向对象方法

#### 面向对象过程方法

- **定义：**
  - 强调流程，线性化、步骤化。
- **缺点：**
  - 代码复用性低
  - 扩展能力差
  - 各个模块之间的耦合度非常高，维护难。

#### 面向对象方法

- **概述：**
  - 面向对象是一种思想，也是一种开发方法，但不是一种开发技术。**它使用类、对象、消息等基本概念和继承、封装、多态等主要特征**来进行软件开发。
  - 面向对象可以是任何事物

#### 面向对象分析（OOA）

- **主要任务（概述）**：
  - 面向对象分析，其主要任务是识别问题域所涉及的类与对象，并分析它们之间的关系，任何建立问题域的梦想，该模型力争能真实地反映所要解决'实质性问题'，且简洁的，可理解的正确模型。
  - **其实质就是获取和整理用户需求并建立精确的模型过程。**
- **三个子模型：**
  - **对象模型：**
    - 描述了系统的**对象、类、以及对象之间、类之间**关系的静态结构。
    - **对象模型是最重要的、最核心的模型，主要考虑的是系统中对象的结构、属性和操作。是其他两个模型的基础**
  - **动态模型：**
    - 描述了系统中与时间有关的方面以及操作执行顺序的动态行为。
    - **动态模型通过时序图、通信图描述对象之间的交互，以揭示对象如何协作完成每个具体的用例功能**
  - **功能模型：**
    - 描述了系统的所有计算，输入值对应输出值关系，不考虑时间的计算次序，由动态模型的动作引起。
    - **功能模型通常由多张数据流图组成**
- **五个层次：**
  - **主层次**
  - **对象与类层次**
  - **结构层次**
  - **属性层**
  - **服务层**
- **五个活动**
  - **标识对象类**
  - **标识结构**
  - **定义主体**
  - **定义属性**
  - **定义服务**
- **五个基本步骤：**
  - **确定对象类**
    - 先找出系统中候选的类和对象，然后筛选出正确的类和对象，最后确定对象属性，定义对象操作
  - **确定结构**
    - 结构是指问题域的复杂性和连接关系。两个或者多个对象之间相互依赖、相互作用的关系就是关联。由关联可构成OOA的两种基本结构：分类结构（**泛化特殊关系**）和组装结构（**整体与局部关系**）先初步确定类之间的关系，然后在进行筛选和完善
  - **确定主题**
    - 通过将类和对象划分成更大的单元完成
  - **确定属性**
    - 避免冗余和不确定的属性
  - **确定方法**
    - 收到消息后必须处理的一些处理方法

#### 面向对象设计

- ​	**主要任务：**
  - 在OOA的基础上进行扩展，对OOA的结果作进一步的规范化整理。OOD的目标是跨越业务领域模型与可运行的软件系统之间的鸿沟，建立可靠的、可实现的系统模型，是对OOA的成果完善和细化分析。
- **OOD主要包括两个方面的工作内容：**
  - 一是根据现实条件对OOA模型做必要的修改和调整。
  - 二是针对具体的实现条件，建立人机界面、数据存储、和控制驱动等模型。
- **需要遵守以下准则：**
  - **模块化、抽象、信息隐藏、高内聚、低耦合、可重用**

#### 面向对象编程

- **主要任务：**
  - 使用面向对象编程语言，实现OOA和OOD模型，开发能正常运行的、实际的软件系统。
  - 在OOP过程中，通过对象、类、消息等基本概念和封装、继承、多态等主要特征的代码实现。

### 2.2：了解面向对象的基本概念

#### 基本概念

##### 对象

- **概述：**
  - 对象就是客观存在的事物（实体）
  - 是面向对象开发模式的基本成份。对象由属性和方法组成，每个对象都存在一定的状态和内部标识，对象将它自身的属性集操作“包装”起来，成为封装。
  - 对象=属性+操作
- **组成三要素：**
  - 对象标识（对象名称）
  - 属性
  - 操作

##### 类

- **概述：**
  - 一组具有相同数据结构和相同操作的对象的集合。比如车可以分为汽车，轿车，火车，都是车这就是类
  - 多个对象的抽象集合

##### 消息

- **概述：**
  - 对象之间的**通信**

- **消息主要包含的5个部分：**
  - 发送消息的对象
  - 接收消息的对象
  - 传递消息的方法（操作）
  - 消息的内容（参数）
  - 反馈消息（发送或失败等）

#### 特征

##### 封装

- **概述：**
  - 将属性和方法绑定在一起。

- **两方面特征：**
  - 一是对象内部的属性和方法封装在一起，形成一个不可分割的独立的整体，对象内部的私有属性只能由这个对象自身的方法来访问。
  - 二是尽可能隐藏了对象的内部细节，受到封装的保护，对外形成了一道屏障，外界不能直接调用对象内部的属性和方法，对象内部与外界的联系只能通过外部接口来实现。

##### 继承

- **概述：**
  - 子类可以继承父类的全部属性和方法。Java语言只允许单继承。
  - 是使用已存在的定义做为基础建立新定义的技术。比如你爸是皇帝，你也是，子承父业。

- **方法：**
  - 单继承：
    - 单继承是指一个子类只能从一个父类继承。
  - 多继承：
    - 多继承是指一个子类可以从多个父类继承在**Java语言只允许单继承**。



##### 多态

- **概述：**
  - 提高程序的重用性和可扩展性
  - 是指相同的操作、函数、过程作用于不同的对象上并获得不同的结果，即相同操作的消息发送给不同的对象时，每个对象将根据自己所属类中所定义的操作去执行，从而产生不同的结果。比如水果类的颜色，每个水果的颜色不同，这就是多态。颜色就是接口。

### 2.3：软件建模

#### 软件建模概述

- **概述：**
  - 软件建模中的一个视图代表不同的人员（**用户、系统分析员、编码人员、测试人员、集成人员、项目经理**）
  - 捕捉软件系统本质，将**问题领域**转移到**解决领域**
- **模型：**
  - 模型是用某媒介对相同媒介或其他媒介里的一些事物的表现形式，是对现实世界客观存在的现实的抽象和简化，提供了系统蓝图。
- **建模：**
  - 建模就是捕捉系统本质的过程，对现实实体抽象和简化的过程，构建系统蓝图的过程。
  - 在建模的时候，设计者从某个角度的观点出发，过滤事物的非本质细节，抓住事物最重要的方面并进行简化，抽象出问题的本质，使问题更容易理解，使现实更简化。
- **软件建模的好处：**
  - 通过软件建模，有利于对软件系统的理解
  - 复杂软件系统在开发过程中往往难以把控，分层方法有利于解决封装问题，使复杂的问题得到有效的简化。
  - 通过软件建模，有利于构建真正满足用户需求的实际产品。
  - 软件建模使软件开发过程更可控。
- **软件建模的目的（通过建模，要达到四个目的）**：
  - 模型帮助我们按照实际情况或按照我们所需要的样式对系统进行可视化。
  - 模型允许我们详细说明系统的结构或行为。
  - 模型给出了一个指导我们构造系统的模板。
  - 模型对我们作出的决策进行文档化。
- **各阶段工作人员的关注重点（初略了解）**
  - 用户：软件系统的功能
  - 系统分析员：将问题转化为解决方案
  - 编码人员：系统的类，接口，算法，对象之间的通信。
  - 集成人员：将开发的子单元、子系统或者构件集成软件产品，并在网络和主机系统平台 上部署开发出来软件系统

#### 面向对象建模

##### 概念：

面向对象的系统开发过程以体系结构为中心，以用例为驱动，是一个反复渐增的过程

##### 建模方法：

###### Booch方法

- **Booch方法（主要步骤）**：
  - 在给定的抽象层次上识别类和对象
  - 识别这些对象和类的语义
  - 识别这些类和对象之间的关系
  - 实现类和对象
- **Booch方法特点：**
  - 不断细化的送代和渐增的开发过程

###### OMT方法

- ​	**OMT方法（对象建模技术）主要步骤：**

  - 分析阶段：基于问题和用户需求的描述，建立现实世界模型

  - 设计阶段：结合问题域的知识和目标系统的结构，将系统拆分为子系统

  - 实现阶段：将设计转化为特定编程语言或硬件，同时保持可追踪性、灵活性和可扩展性

- **OMT方法（对象建模技术）特点：**

  - 覆盖了软件分析、设计和实现
  - 从对象模型、动态模型和功能模型三个不同但相关的角度进行系统建模。
  - 在软件开发的周期中的每个阶段，三种模型不断地精化、优化和扩

###### OOSE方法

- **OOSE方法（主要步骤）：**
  - 需求模型
  - 分析模型
  - 设计模型
  - 实现模型
  - 测试模型
- **OOSE特点：**
  - 较好的描述系统与用户的信息交换机制，即向软件系统提出需求，系统完成需求。

###### UML方法

- **UML方法（统一建模语言）**
  - **特点：**
    - 综合了前三个建模方法的精华集合
      - 同统一了Booch、OMT、OOSE等方法中的基本概念和符号，**并最终统一为大众所接受的标准语言**
      - 定义良好、易于表达、功能强大、先进实
  - **UML新增：**
    - 模块（Stereotypes）职责（Responsibilities）线程（Thread）
    - 过程（Process）扩展机制（Extensibility Mechanism）
    - 分布式（Distribution）并发（Concurrency）模式（Patterns）
    - 合作（Collaboration）活动图（Activity Diagram）等新概念
  - **并清晰地区分：**
    - 类型（Type）类（Class）实例（Instance）
    - 细化（Refinement）接口（Interfaces）组件（Conponents）等概念

### 项目回顾

------

本项目首先阐述了面向对象方法的分析、设计和编程等过程，接着介绍了面向对象方法的基本概念和主要特征，最后介绍了软件建模的概念，好处和经典方法。涉及的关键知识和关键技能如下。

- **关键知识：**
  - 面向对象分析：主要任务、三个子模型、五个层次、五个活动。
  - 面向对象设计：主要任务、准则。
  - 面向对象编程：主要任务
  - 面向对象基本概念：对象、类、消息等基本概念。
  - 面向对象主要特征：封装、继承、多态等主要特征。
  - 软件建模：模型、软件建模的概念，软件建模的好处。
  - 面向对象建模：Booch、OTM、OOSE和UML等建模方法。
- **关键技能：**
  - 描述面向对象分析、面向对象设计和面向对象编程的主要任务。
  - 对象和类等概念的代码实现。
  - 封装、继承和多态等特征的代码实现。
  - 针对具体的软件系统项目，阐述软件建模的含义和好处。
  - 描述Booch、OTM、OOSE和UMl等各经典的面向对象建模方法的特点。

------

## 三、认识UML

------

- **任务目录：**

  - 3.1：认识UML结构


    - 3.2：掌握UML视图和图

  

    - 3.3：掌握UML建模工具

------

### 3.1、了解UML结构

**概述：**UMl的组成主要有**事物、关系和图**。事物把关系事物联系在一起，组成有意义的结构模型。图聚集了相关的事物。

#### UML中的事物

- **概述：**
  - 事物是构成模型图的一些基本图示符号，表示一些面向对象的基本概念。
  - 它是对模型中最具有代表性成分的抽象。

##### UML中的事物组成四大类：

###### 结构事物

- **概述：**
  - 结构事物是UML模型的静态部分，描述概念或物理元素，主要包括类、接口、协作、用例、活动类、构件和节点等七种。

- **七种组成部分：**
  - 类
    - 类是对一组具有 相同属性，方法，关系和语义的对象的描述。一个类实现一个或多个接口。
  - 接口
    - 接口是指类或组件所提的、可以完成特定功能的一组操作的集合。
    - 因此，一个接口描述了类或组件的对外的、可见的动作。
  - 协作
    - 协作定义了一组事物间的相互作用，表示一些角色和其他元素一起工作，提供一些合作的动作。
    - 在UMl图中，协作用一个虚线椭圆来表示。
  - 用例
    - 用例描述系统对一个特定角色执行的一系列动作。
    - 在模型中用例通常用来组织动作事物，用例是通过协作来实现的。
  - 活动类
    - 活动类是类对象有一个或多个进程或线程的类。
    - 在UML中，活动类的表示方法和类相同，也是用一个矩形表示，只是外框用粗线条。
  - 构件
    - 构件又称为组件，是定义了良好接口的物理实现单元，是系统中物理的、可替换的部件。
    - 组件提供一组实现接口，每个组件体现了系统设计中特定类的实现。
  - 结点
    - 结点是系统在运行时真实存在的物理对象，表示某种可计算资源，这些资源通常具有一定的存储能力和处理能力（如一台计算机）。
    - 设备是指那些本身不具备处理能力的结点。

###### 行为事物

- **概述：**
  - 行为事物也称为动作事物，是UMl模型中的动态部分，代表时间和空间上的动作。
  - 行为事物主要有两种交护和状态机。

- **行为事物主要的两种元素：**
  - 交互
    - 交互是特定上下文中的一组对象，为共同完成一定的任务而进行的一系列消息交换所组成的动作。
    - 交互这样一种行为，它由在特定语境中共同完成一定特定任务的一组对象之间交换的消息组成。一个对象群体的行为或单个操作的行为可用一个交互来描述。
  - 状态机
    - 状态机用于表示一个类的东西所有可能的生命历程的模型，因此状态机可用于描述一个对象或者一个交互在生命期内响应事件所经历的状态序列。
    - 状态机是这样一种行为，描述了一个对象或者一个交互在生命期内响应事件所经历的状态序列。单个类或者一组类之间协作的行为可以用状态机来描述。一个状态涉及到一些其他元素，包括状态转换（从一个状态到另一个状态的流）事件（发转换的事物）和活动（对一个转换的响应）。分组事物

###### 分组事物

- **概述:**
  - 分组事物也称为组织事物，是UMl模型中组织的部分，可以把它看作一个个盒子，每个盒子里面的对象关系相对复杂，而盒子与盒子之间的关系相对简单。目前分组事物只有一种既**包（Package）**。

- **分组事物主要的一种元素：**
  - **包（Package）**
    - 把元素组织成组的机制。是UML中唯一的组织机制。包可以拥有其他元素。

###### 注释事物

- **概述：**
  - 注释事物是UMl模型的解释部分用来描述、说明和标注模型的任何元素。
  - 是一个依附于一个元素或一组元素之上，对它进行约束或解释的简单符号。

#### UML的关系

- **概述：**
  - UMl模型是由各种事物以及这些事物之间的各种关系构成的。
  - 关系是指支配、协调各种模型元素存在并相互使用的规则。
  - UMl中主要包含**四种关系**，分别是**关联、依赖、泛化和实现**。

##### UMl的四大关系：

###### 关联关系

- **概述：**
  - 关联表示两个类之间存在的某种语义上的联系，其描述的是两个或多个类之间的结构关系。
  - 关联关系式一种结构化的关系，是指一种对象和另一种对象有联系。给定关联的两个类，可以从其中的一个类的对象访问到另一个类的相关对象。关联关系用一条实线表示。

- **三个主要的关联关系：**
  - 普通关联
    - 普通关联关系是类与类之间最常用的一种关系，它是结构化关系，用于表示一个类对象与另一个类对象之间的有联系。
  - 聚合关联
    - 聚合是关联的特例。聚合是表示整体与部分的关系，即has a 关系。聚合关系中的整体和部分是可以分离的，他们可以具有各自的生命周期，部分可以数据多个整体对象。
  - 组合关联
    - 组合关系式关联关系的一种特例，他体现的是一种contains a的关系，这种关系比聚合更强。它同样也体现了整体与部分的关系。此时整体与部分是不可分的，整体的生命周期结束也就意味着部分的生命周期结束。

###### 依赖关系

- **概述：**
  - 依赖关系式类与类之间的连接，表示一个类依赖于另一个类的定义。其中一个类元素是独立的，另一个类元素不是独立的，它依赖与独立的那个类。如果独立的类改变，将影响依赖与它的那个类。

###### 泛化关系

- **概述：**
  - 泛化关系式一个类（子类、子接口）继承另外一个类（父类、父接口）的功能。子类还可以增加自己的新功能。继承是类与类或者接口与几口之间最常见的关系之一。

###### 实现关系

- **概述：**
  - 实现关系指的是一个class类实现interface接口（可以是多个）的功能；实现是类与接口之间最常见的关系。

### 3.2、掌握UML视图和图

#### UML的视图

- **概述：**
  - Kruchten提出的“4+1”视图模型，是从五个不同的视角，既用例视图、逻辑视图、并发视图、组件视图、部署视图来描述软件体系结构。每个视图只关心系统的一个侧面，五个视图结合在一起才能反映系统的软件体系结构的全部内容。

##### UMl4+1视图模型

###### 用例视图

- **概述：**
  - 用例视图又称为外部视图、用户视图功能视图。用例视图描述系统应具备的功能，强调从系统的外部参与者（主要是用户）的角度看到的或需要的系统功能。

- **作用：**
  - 描述系统应该具备的功能，关注系统外部，从系统的外部看到的系统功能。

- **用途：**
  - 列出参与者和系统用例，以及参与者和用例之间的关系

- **组成：**
  - 用例图

- **使用者：**
  - 用户

###### 逻辑视图

- **概述：**
  - 逻辑视图又称为动态视图、进程视图，主要用于描述在用例中提出的系统功能的实现。与用例视图相比，逻辑视图主要关注系统内部，天既描述系统的静态结构（系统中的类、对象以及它们之间的关系），也描述系统内部的动态行为关系。
- **作用：**
  - 主要用于描述在用例中提出的系统功能的实现。与用例视图相比，逻辑视图主要关注系统内部，天既描述系统的静态结构（系统中的类、对象以及它们之间的关系），也描述系统内部的动态行为关系。
- **组成：**
  - 静态（类图和对象图）动态（状态图，序图，协作图以及活动图）

- **使用者：**
  - 设计人员和开发人员

###### 并发视图

- **概述：**
  - 并发视图又称为动态视图、进程视图，主要是从资源的有效利用、代码的并行执行以及系统环境中异步事件的处理等角度来考虑。
- **作用：**
  - 主要是从资源的有效利用、代码的并行执行以及系统环境中异步事件的处理等角度来考虑。
- **组成：**
  - 状态图、协作图、以及活动图。
- **使用者：**
  - 开发人员和系统集成人员。

###### 组件视图

- **概述：**
  - 组件视图又称为实现视图、物理视图，用于描述系统的实现模块以及它们之间的依赖关系。
  - 其中的组件是指不同类型的代码模块，是构造应用的软件单元。
- **作用：**
  - 描述系统的实现模块以及它们之间的依赖关系。
- **组成：**
  - 组件图
- **使用者：**
  - 开发人员

###### 部署视图

- **概述：**
  - 部署视图又称为配置视图，用于显示系统的物理部署，描述位于结点上的运行实例的部署情况。
  - 部署是指将系统配置到由计算机和设备的物理结构上。
- **作用：**
  - 用于显示系统的物理部署，描述位于结点上的运行实例的部署情况。
- **组成:**
  - 配置图
- **使用者：**
  - 开发人员、系统集成人员和测试人员。

#### UML的图

- **概述：**
  - UMl语言的各种图是UMl模型的重要部分。UMl中常用的图有九种：**用例图、类图、对象图、活动图、状态图、序列图（顺序图）、协作图、构件图、部署图（配置图）**，通过他们的相互组合提供被建模系统的所有视图。

##### 	UML常用的九种图	

- **1、用例图**
  - 描述角色以及角色与用例之间的连接关系。说明的是谁要使用系统，以及他们使用该系统可以做些什么。一个用例图包含了多个模型元素，如系统、参与者和用例，并且显示了这些元素之间的各种关系，如泛化、关联和依赖

- **2、类图**
  -   类图是描述系统中的类，以及各个类之间的关系的静态视图。能够让我们在正确编写代码以前对系统有一个全面的认识。类图是一种模型类型，确切的说，是一种静态模型类型。

- **3、对象图**
  -   与类图极为相似，它是类图的实例，对象图显示类的多个对象实例，而不是实际的类。它描述的不是类之间的关系，而是对象之间的关系。

- **4、活动图**
  -   描述用例要求所要进行的活动，以及活动间的约束关系，有利于识别并行活动。能够演示出系统中哪些地方存在功能，以及这些功能和系统中其他组件的功能如何共同满足前面使用用例图建模的商务需求。

- **5、状态图**
  -   描述类的对象所有可能的状态，以及事件发生时状态的转移条件。可以捕获对象、子系统和系统的生命周期。他们可以告知一个对象可以拥有的状态，并且事件(如消息的接收、时间的流逝、错误、条件变为真等)会怎么随着时间的推移来影响这些状态。一个状态图应该连接到所有具有清晰的可标识状态和复杂行为的类；该图可以确定类的行为，以及该行为如何根据当前的状态变化，也可以展示哪些事件将会改变类的对象的状态。状态图是对类图的补充。

- **6、序列图**（顺序图）
  -   序列图是用来显示你的参与者如何以一系列顺序的步骤与系统的对象交互的模型。顺序图可以用来展示对象之间是如何进行交互的。顺序图将显示的重点放在消息序列上，即强调消息是如何在对象之间被发送和接收的。

- **7、协作图（通信）**
  -   和序列图相似，显示对象间的动态合作关系。可以看成是类图和顺序图的交集，协作图建模对象或者角色，以及它们彼此之间是如何通信的。如果强调时间和顺序，则使用序列图；如果强调上下级关系，则选择协作图；这两种图合称为交互图。

- **8、构件图** （组件图）
  -   描述代码构件的物理结构以及各种构建之间的依赖关系。用来建模软件的组件及其相互之间的关系，这些图由构件标记符和构件之间的关系构成。在组件图中，构件时软件单个组成部分，它可以是一个文件，产品、可执行文件和脚本等。

- **9、部署图** （配置图）
  -   是用来建模系统的物理部署。例如计算机和设备，以及它们之间是如何连接的。部署图的使用者是开发人员、系统集成人员和测试人员。

在有的文献书籍中，将这九种模型图分为三大类：

结构分类、动态行为和模型管理：

**1：结构分类包括用例图、类图、对象图、构件图和部署图，**

**2：动态行为包括状态图、活动图、顺序图和协作图，**

**3：模型管理则包含类图。**

### 3.3、掌握UML建模工具

常用UML建模工具介绍



#### ENterprise   Architect   的安装和配置







### 项目回顾

------

本项目首先阐述了UML结构中的事物和关系，接着介绍了UML‘’4+1‘’视图模型和九总经典图形，最后介绍了常用的UML建模工具软件。涉及的关键知识和关键技能如下。

- **关键知识**
  - UMl中的事物：结构事物、行为事物、分组事物和注释事物。
  - UML中的主要关系：依赖、关联、泛化和实现。
  - UMl ”4+1“ 视图模型：用例视图、逻辑视图、并发视图、组件视图、部署视图。
  - UML中常用的图有九种：用例图、类图、对象图、状态图、活动图、顺序图、通信图、组件图和部署图。
  - 常用的UMl建模工具，例如：Enterprise  Architect   和   Rational  Software  Architect。

- **关键技能**
  - Enterprise  Architect  的安装。
  - Enterprise  Architect  的基本设置和使用。

------

## 四、用例建模

### 用例概述

#### 概念

- 用例图是从使用者的角度来描述软件系统的功能以及系统与使用者之间的交互。
- 一幅用例图由参与者、用例、系统（系统边界）以及它们之间的不同关系（如泛化、包含、扩展等）等4个组成要素构成。

#### 作用

- 用于进行系统功能方面的分析准确的描述用户对系统功能方面的期望。
- 用例图在系统需求的跟踪、验证和确定的过程中起着重要作用。

### 用例组成要素

#### 参与者

##### 概念

- 表示系统中的用户，即与系统交互的对象

##### 作用

- 与系统交互的人
- 与系统交互的硬件组件
- 或者其他的外部系统
- 关注的重点是所承担的***\*角色\****
- 参与者的名要明确定义其角色

#### 用例

##### 特征

- 定义一个参与者要用到的**系统功能**
- 描述系统为实现参与者价值所开展的**行为序列**
- 对参与者与系统之间的**交互活动**进行建模
- 从特定的用户角度出发，是完整的、实现特定用户价值的事件流

- 是系统所提供的一个功能（或某一特定用法）的描述，是**执行者和系统交互的一个完整过程**。用例具有**响应性、回执性、完整性**，分为**业务用例**和**系统用例**

#### 系统边界

- 概念：
  - 系统是具有特定功能的有机整体，系统的范围大小是相对的，一个系统也可以包含用户需要的所有功能，也可能是一部分功能。
  - 系统边界代表了系统的范围，通过系统边界把系统内部和外部可视化区别出来。
  - 系统边界决定了参与者，如果系统边界不一样，它的参与者就会发生很大的变化。
  - **系统边界，即系统包含的功能与系统不包含的功能之间的界限。一般在系统分析阶段定义，只有明确了系统边界，才能继续进行下面的分析、设计等工作。**
- 作用：
  - 在UML中系统边界通常用矩形来表示，矩形之内表示系统内部，矩形之外表示系统外部，系统名称写在矩形内部的上方，系统的用例画在矩形里面，参与者则在矩形的外面。

#### 关系

- 概念：
  - 参与者与用例之间的交互通道
  - 用一条直线表示交互：有箭头的关联指出是谁发起的交互、没有箭头则表明双方都可以发起交互
  - 每一个交互代表一个完整的对话

##### 关联关系

- 概念：
  - 表示参与者与用例之间的通信。

- **参与者与用例之间的关系**
  - 非定向关联

  - 一定的


##### 泛化关系

- 概念：
  - 参与者与参与者之间的关系、用例与用例之间的关系。
  - 参与者之间可以有共同的属性和行为，因此可使用泛化关系来描述多个参与者之间的公共行为。它们之间有特殊和一般的关系。
  - 当多个用例**共同拥有一种类似的结构和行为**的时候，我们可以将它们的共性抽象成为父用例，其他的用例作为泛化关系中的子用例。
  - 泛化关系是对父用例具有一定的**强依赖关系**，子用例表示父用例的特殊形式，可以继承父用例的行为和属性，还可以添加自己的行为和属性。

##### 包含关系

- 概念：
  - 用例与用例之间的关系
  - 指一个用例可以包含其他用例具有的行为，并把它所包含的用例行为作为自身用例的一部分。其实就是基础用例中一个不得不执行的用例部分。
- 重要内容：
  - 包含关系中的基本用例(base use case) 的执行依赖于包含用例的执行，如果没有包含用例，则基本用例的执行是不完整的。
  - 包含用例是可重用的用例──多个用例的公共用例（公共行为）。
  - 该用例本身具有独立的业务逻辑，同时也可能被其它用例所引用，或者这个用例需要独立封装。
  - 要使用包含关系，必须在子用例中说明基础用例行为包含的详细位置，类似于功能调用。

##### 扩展关系

- 概念：
  - 用例与用例之间的关系。
  - 一个用例也可以被定义为基础用例的增量扩展，这称作扩展关系，扩展关系是把新行为插入到已有用例的方法。
- 重要内容：
  - 扩展关系表示一个业务用例的执行有时需要对用例的功能进行扩展。将扩展用例的事件流在一定的条件下按照相应的扩展点插入到基础用例中。
  - 基础用例不必知道扩展用例的任何细节，它仅为其提供扩展点。基础用例没有扩展用例也是完整的。
  - 扩展用例的行为是否被执行要取决于主事件流中的判定点。如果特定条件发生，扩展用例的行为才被执行。
  - 值得注意的是扩展用例的事件流往往也可以抽象为基础用例的备选流。

------



## 五、静态建模

### 类图

#### 概念

- 类图是UML图形中最基本的图形之一，是描述系统中一组类、接口、协作，以及它们的结构和相互之间的关系的静态模型。

#### 组成要素

##### 类

- **概念**：
  - 类是面向对象开发思想的基本概念，是面向对象系统组织结构的核心。
- **类的名称**
- **类的属性**
  - 可见性
    - 可见性用于描述该属性对于其他类是否可以访问引用的特性，实际上就是属性的作用域。
  - 属性名
    - 类的属性描述类的静态特征，一个类可能有多个属性，每个属性都必须有一个名称以区别类中的其他属性。
  - 属性类型
    - 属性类型表示该属性是什么数据类型。
  - 初始值
    - 初始值是指属性最初获得的默认赋值。
  - 属性字符串
    - 属性字符串用来指定关于属性的其他信息。
- **类的操作**
  - 可见性
    - 可见性用于描述该操作对于其他类是否可以访问引用的特征，实际上就是操作的作用域。
  - 操作名
    - 类的操作描述类的动态特征，一个类可能有多个垂直，每个操作都必须有一个名称以区别类中的其他操作。
  - 参数列表
    - 参数列表是由参数名和类行组成的序列。
  - 返回类型
    - 返回类型指定操作执行之后返回值的数据类型，可以是任意有效的数据类型，如字符型、字符串型、整型
  - 属性字符串
    - 属性字符串用来附加一些关于垂直的除了预定义的元素之外的信息，方便对操作的一些内容进行说明。
- **类的构造类型**
  - 实体类
    - 实体类表示在软件系统中需永久性存储信息的实体。
  - 边界类
    - 边界类用于对外部用户与系统之间的交互对象继续抽象，位于系统与外部的交界处。
  - 控制类
    - 控制类用于负责协调其他类的工作，体现了应用程序的执行逻辑，提供相应的业务操作，将控制类抽象出来可以降低界面和数据库之间的耦合度。

##### 接口

- ##### 概念

  - 通常在面向对象开发方法中类的继承是单继承，即一个类（子类）只能继承另一个类（父类），但是使用接口可以继承或实现多个类。

##### 类之间的关系

- 关联关系
  - 概念：
    - 关联关系，关联(Association)表示两个类之间存在某种语义上的联系。

  - 名称
    - 名称用来描述关联的性质，通常使用一个动词或动词短语来命名关联，以表明源对目标执行的动作。
  - 角色
    - 角色是关联关联中一个类对另一个类所表现出来的职责。
  - 多重性
    - 多重性描述了关联关系中的类中对象的数量关系，是指类中有多少个对象可以参与该关联。
  - 导航性
    - 导航性代表关联关系的方向性，描述关联关系中一端的类中对象通过导航访问另一端类中对象。

- 聚合关系
  - 概念：
    -  聚集(Aggregation)是一种特殊形式的关联。聚集表示类之间的关系是整体与部分的关系。
    -  在需求分析中,"包含"、"组成"、"分为……部分"等经常设计成聚集关系。
    -  聚集可以进一步划分成共享聚集(Shared Aggregation)和组成。

- 组合关系
  - 概念：
    - 组合关系也是一种特殊的关联关系，描述了整体和部分之间存在的一种完全隶属于的关系，既“ contains a ”  或  “ is part of ” 的关系，体现整体和部分之间非常强的关联性。
    - 在组合关系中一个部分类的对象仅属于一个整体的对象，二者是共存亡的。

- 泛化关系
  - 概念：
    - 泛化关系。类的泛化关系描述是一般类与特殊类之间的关系，表示了类与类之间的继承关系，既特殊类继承一般类的属性和行为特征，是一种 “ is a ” 的关系。
    - 在类的泛化关系中，表示一般特征的、被继承的类称为父类或超类，表示特殊特征的、继承的类称为子类。

- 依赖关系
  - 概念：
    - 依赖关系。依赖关系描述两个模型元素之间的语义关系，表示一个元素对另一个元素的依赖性，也就是一个元素的变化会影响另一个元素。
    - 有两个元素X、Y,如果修改元素X的定义可能会引起对另一个元素Y的定义的修改,则称元素Y依赖(Dependency)于元素X。
    - 在类中,依赖由各种原因引起,如:
      一个类向另一个类发消息;
      一个类是另一个类的数据成员;
      一个类是另一个类的某个操作参数。
    - 如果一个类的界面改变,它发出的任何消息可能不再合法。

- 实现关系
  - 概念：
    - 实现关系。实现关系描述两个模型元素之间的规格说明与其实现的关系，也就是说一个元素只定义了规格说明或约定，但并没有实现，而是通过一个元素来实现的。


### 对象图

#### 概念

#### 对象图的组成要素

##### 对象

- 概念：
  - 对象是类的实例，是一个独立的、可确定的物体、单元或实体。
  - 可以是一个具体的实物，如某一本书、某位老师等，也可以是一个抽象的事物，如某一份计划。
- 三个基本组成部分：
  - 标识
    - 标识。标识就是为了将一个对象区别于其他对象的名称。
    - 一个对象就是具体的事物，也就应该为该对象明确一个确定的”对象名“。
  - 属性
    - 属性。属性也称为对象的状态，表示对象的结构特征，描述了对象的结构状态，是表示对象静态特征的一个数据项。
  - 行为
    - 行为。行为也称为方法或操作，在一个系统中，对象往往不是孤立的，它是可以操作的对象，也可以是被操作的对象。

##### 关系

- 概念：
  - 在对象图中，对象与对象之间的关系称为链。
  - 因为对象是类的实例，所以对象可以用有或参与的链是由类图的关联定义。

------



## 六、数据库建模

### 数据库需求分析

#### 业务流程

- 

#### 系统功能结构

##### 各模块业务功能

- 商品模块
  - 商品管理模块主要实现的功能操作包括：商品的添加、修改、查询和删除；商品类别的添加、修	改、查询、和删除；供应商的添加、修改、查询和删除。
- 订单管理模块
  - 订单管理模块主要实现的功能操作包括：订单的查询、修改、确认、取消、发货处理等。
- 用户管理模块
  - 用户管理模块主要实现的功能操作包括：会员的添加、修改、查询和删除，以及会员基本信息、积分、等级等资料的维护。客服人员的添加、修改、查询和删除。客服人员的基本信息、权限等资料的维护；管理人员添加、修改、查询和删除，管理人员的基本信息、权限等资料的维护。
- 统计分析模块
  - 统计分析模块主要实现的功能操作包括：网站访问流量的统计分析、商品销售情况的统计分析，如根据商品、商品类别或供应商的不同，进行显示金额、数量的分析统计分析。


#### 数据流

##### 概念

- 数据流分析是对事务处理所需的原始数据进行收集，经过处理后所得到的数据及其流向，一般用数据流图来表示。

##### 数据流基本图形元素

- 数据流
  - 数据在系统内传输的一项或一组数据，既流动中的数据。在绘制数据流图时，数据流用带箭头的线来表示 （如：→）。

- 数据加工
  - 或称数据处理，是对数据进行处理加工的单元，接收输入的数据，然后进行加工处理，并且产出新的数据输出。在绘制数据流图时，数据加工用圆圈表示，在圆圈内写上加工名（如：○）。

- 数据存储
  - 用于存储数据信息，表示数据信息，表示数据信息的静态存储，如文件、数据库表、账本等。在绘制数据流图时，用双杠表示（如：＝）。

- 数据源（终点）
  - 指数据的源点或终点，表示系统之外的实体，它们与本系统有信息传递关系，如人、物或其他软件系统。在绘制数据流图时，用方框表示（如：□）。


#### 绘制数据流

- 创建数据流图
- 创建数据流模型
- 绘制数据流图

### 构建概念数据模型

#### 概念

- 概念结构设计是数据库设计的一个重要阶段，就是将需求分析阶段得到的用户需求抽象为信息结构，既概念模型。

------



## 七、动态建模

### 状态图

#### 概述

- 状态图（State Diagram）也称状态机图，或者说一个状态图显示了一个状态机。
- 就是描述系统状态状态转换的一种UML图形。

#### 作用

- 状态图清晰地描述了状态之间的转换顺序，通过状态的转换顺序可以清晰看出事件的执行顺序。
- 状态图清晰地描述了状态转换时所必须触发的事件、监护条件和动作等影响转换的因素，有利于程序员避免程序中非法事件的进入。
- 清晰的事件顺序有利于程序员在开发程序时避免出现事件错序的情况。
- 状态图通过判定可以更好地描述工作流因为不同的条件发生的分支。

#### 组成要素

##### 状态

- 初始状态
  - 使用一个实心圆表示，表示状态图的起始点。
  - 一个状态图只允许有一个初始状态。

- 一般状态
- 终止状态
- 如何描述一个状态包含：
  - 名称
  - 入口/出口动作
  - 内部活动和转换
  - 子状态
  - 延迟事件
- 三种状态
  - 简单状态
  - 复合（或组合）状态
  - 历史状态

##### 转换

###### 转换的组成要素

- 源状态
- 触发事件
- 监护条件
- 动作
- 目标状态

##### 事件

###### 事件组成要素

- 信号事件
- 调用事件
- 时间事件
- 修改事件

##### 动作和活动

##### 判定和同步

### 活动图

#### 概述

#### 组成要素

##### 动作

- 动作三个突出特征
  - 原子性
  - 不可中断性
  - 瞬时性

##### 活动

##### 开始结点

##### 动作流

##### 对象流

##### 分支与合并

##### 分叉与汇合

##### 泳道

### 顺序图

#### 概述

#### 组成要素

##### 对象

##### 生命线

##### 激活期

##### 消息



### 通信图

#### 概述

#### 组成要素

##### 对象

##### 链

##### 消息

------

## 八、物流建模

### 组件图

#### 概述

- 组件图（Component Diagram）是用来表示系统中组件与组件之间，以及定义的类/接口与组件之间的结构关系的图。
- 组件图通过显示系统的构件以及接口等之间的接口关系，形成系统的更大的一个设计单元。

#### **作用**

- 使系统测试人员和开发人员能够从整体上了解系统的所有物理部件；
- 从**软件架构**的角度来描述一个系统的主要功能；
- 方便项目组的成员了解系统的结构和功能；
- **有利于软件复用**。

#### 组件

##### 概念

- 组件又称为“ 构件 ”，是指系统中的可替代性物理单元，是系统高层的可重用部件。

##### 特征

- 代码特征
  - 指组件包含和封装了实现系统功能的类或者其他元素的实现代码，以及某些构成系统的实例对象。

- 身份特征
  - 指组件拥有身份和状态，用于定位在其上的物理对象。
  - 由于组件的实例包含身份和状态，称为有身份的组件。一个有身份的组件是物理实体的物理包容器。


##### 组件类型

- 实施组件
- 配置组件
- 工作产品组件

##### 组件和接口

- 组件（Component）是系统中可替换的部分，遵循并提供了一组接口的实现，而接口是一组操作的集合，用于指明类或组件的一个服务。
- 组件和接口之间的关系是很重要的，几乎所有流行的基于组件的操作工具（如 COM+）都以接口作为把组件绑定在一起的粘合剂。

#### 端口

##### 概述

- 端口是一个被封装的组件的对外窗口，在封装的组件中，所有出入组件的交互都要通过端口，组件对外可见行为恰好是它端口的总和。
- 端口是组件的一部分，端口的实例随着它们所属组件的实例被创建和撤销。

#### 内部结构

- 组件可以被作为一段单独的代码来实现，但在很多大型应用系统中，为了达到“ 高内聚 、低耦合” 的松散型设计，降低了组件间的依赖，通过用一些小的组件作为构造块来组建大组件，组件的内部结构是一些小的部件，这些部件连接在一起组合成组件。

#### 关系

##### 依赖关系

- 依赖关系又分两种，一种是组件与组件之间的依赖关系，其表示方式与类图中类与类之间的依赖关系表示方式相同，都是使用一个从用户组件指向它所依赖的服务组件的虚线箭头表示，其中 “ ComponentA ”为一个用户组件，“ ComponentB “为它依赖的服务组件。
- 另一种是组件与接口之间的依赖关系，是指一个组件使用了其他元素的接口。依赖关系可以用带箭头的虚线表示，箭头指向接口。

##### 实现关系

- 实现一个接口意味着组件中的实现元素支持接口中的所有操作。

### 部署图

#### 概述

- 部署图（Deployment  Diagram）是用来显示系统中软件和硬件的物理架构，即系统执行处理过程系统资源的部署情况，是一种静态模型。

#### 基本元素

##### 结点（Node）

- 结点是存在于运行时的、代表计算机资源的物理元素，可以是硬件也可以是运行其上的软件系统，如64位计算机、SQL  Server2012数据库服务器、防火墙等。
- 在构造型列表，用户可以根据需要选择不同类型的结点。

##### 设备（Device）

- 设备是指那些本身不具备处理能力的结点。

##### 物件（Artifact）

- 物件是软件开发过程中的产物，包括过程模型（如用例图、设计图）、源代码、可执行程序、设计文档、测试报告、需求原形、用户手册等。

##### 连接（Association）

- 部署图结点间通过通信关联在一起。
