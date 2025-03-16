# proj0-contest-and-lab-for-os-course
### 标题
面向操作系统课程的操作系统竞赛和实验

### 项目描述
各高校的计算机专业普遍都开设OS课，由于培养目标的差异，不同高校OS课程的要求是不同的；即使是同一所大学的学生，对OS课程&实验的需求也会有所不同，甚至有些学生还会通过参加操作系统比赛来学习掌握操作系统。

为此，每个高校的老师和同学都相应的需求，结合自己的实际情况，选择或设计实现适合自己OS实验，以及参加操作系统比赛。老师和同学设计的实验也可能会适合情况相近的高校OS课程，学生写的参赛项目指导书会帮助更多的学生参加比赛，提升系统能力。

本项目的目的鼓励各个高校的师生设计适合自己的OS实验教程和竞赛指导等，帮助并共享给大家。 这个项目的特点是：从不同的维度（使用OS、分析OS、实现OS、扩展OS、硬件特征、应用需求....）设计操作系统相关的实验内容和比赛项目指导教程等，使得学生可以从不同维度来更好地理解和掌握OS。

### 所属赛道

2025全国大学生操作系统比赛的“OS功能挑战”赛道

### 参赛要求
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

**各高校上OS课的老师都可以是项目导师**

向勇
- github https://github.com/xyongcn
- email xyong@tsinghua.edu.cn

陈渝
- github https://github.com/chyyuu
- email yuchen@tsinghua.edu.cn

### 难度

初等~中等~高等

### 特征

- 从不同的维度（使用OS、扩展OS、实现OS、分析OS、硬件特征、应用需求....）设计操作系统相关的实验内容和比赛项目指导教程
- 文档、代码、问题、答疑交互过程都开放和开源的
- 支持各种硬件
  - 基于RISC-V、LoongArch、ARM处理器等的虚拟开发板（可基于QEMU等硬件模拟环境）
  - 基于目前量产的RISC-V、LoongArch、ARM处理器等的物理开发板
    
### License
- 某种开源协议

推荐GPL和CC开源协议


### 预期目标

注意：**下面的内容是建议内容，不要求必须全部完成。**选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标**


#### 题目一：2025年内核实现赛道的step by step 指导教程
- 重新step by step地完成内核实现赛道的初赛和决赛要求
- 写出step by step的各个步骤的文档
- 对类似github issues的提问给出回答和帮助

##### 注意事项：
- 可参考已有的技术帮助文档和去年的比赛作品（各个获奖队的代码和文档的repos都已开源）。
- 重点要求是要完成一步一步完成的开发/fix bug等的过程描述和基于git的阶段性代码，便于其他参赛同学学习。
- 完成的代码和文档开源，但自己完成部分的版权属于自己。
- 可以基于某种量产处理器和开发板完成项目


##### 已有参考
- [2025OS比赛内核实现赛道相关的一些OS实例/教程的参考信息](https://github.com/oscomp/os-competition-info/blob/main/ref-info.md)
- [2021年OS比赛的一等奖的代码和文档](https://github.com/oscomp/2021oscomp-best-kernel-design-impl)
   - branch 2021-ultraos：哈尔滨工业大学（深圳）内核实现
   - branch 2021-xv6：华中科技大学 内核实现
   - branch 2021-404：中国科学院大学 内核实现
- [2021年OS比赛的技术支持文档和代码](https://github.com/oscomp/os-competition-info/blob/main/ref-info.md)
- [南开大学的uCore Tutorial实验指导书（大致等价于初赛的部分内容）](https://nankai.gitbook.io/ucore-os-on-risc-v64/)
- [北京工商大学的rCore_Tutorial_Detail（面向对OS实验的小白同学）](http://hm1229.top/book/index.html)
- [清华大学的rCore-Tutorial-Book 第三版（大致等价于初赛的部分内容）](https://rcore-os.github.io/rCore-Tutorial-Book-v3/)


#### 题目二：适合本校特点的实验指导教程（文档/代码框架/测例/参考实现）

在各自高校现有OS课程实验的基础上，进一步完成如下目标：
- 改进实验指导文档
- 实验代码框架
- 实验用的测试用例
- 实验的参考实现


##### 注意事项：
- 可基于本校课程中已有的实验内容。
- 能够与操作系统的原理、概念对应起来。
- 重点要求是要完成一步一步完成的开发/fix bug等的阶段性描述和基于git的阶段性代码，便于其他学校的老师和同学一步一步地学习。
- 完成的代码和文档开源，但自己完成部分的版权属于自己。
- 不是以难度作为最终评价目标，而是以适合各自高校实验作为最终评价目标
 
#### 已有参考

- [基于RISC-V代理内核的操作系统课程实验与课程设计](https://gitee.com/hustos/pke-doc)
- [rCore Tutorial 2025 spring OS课实验指导](https://github.com/LearningOS/rCore-Tutorial-Guide-2025S)
- [uCore Tutorial 2025 spring OS课实验指导](https://github.com/LearningOS/uCore-Tutorial-Guide-2025S)
