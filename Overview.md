# 软件项目管理 - 综述

## 介绍
本文主要描述以下几个方面：
- [产出物](#产出物)
- [角色和他们的职责](#角色和他们的职责)
- [项目管理流程](#项目管理流程)

## 产出物
一个项目的会产出什么？

### 发布的内容
- 用户手册
  负责人: `Information Developer`
- Installers
  负责人: `DevOps Developer`

### 规范文档
规范文档应该有公司一个技术委员会来负责。

- 项目流程定义
  负责人: `Project Manager`
- 文档规范
- 代码规范

### 内部
- 需求文档
  负责人: `Product Manager`
- 设计文档
  负责人: 任何人
- 测试用例
  负责人: `Tester`
- 源代码
  负责人: `Developer`, `Tester`, `DevOps Developer`
- 项目开发计划
  负责人: `Developer`
- 项目测试计划
  负责人: `Tester`
- 项目开发运营计划
  负责人: `DevOps Developer`
- 项目文档计划
  负责人: `Information Developer`
- 项目架构设计文档
  负责人: `Architect`

### 项目执行结果
- 项目计划执行结果
  负责人: `Project Manager`
- 测试结果
  负责人: `Tester`

### 资产
- 团队人员列表
  负责人: `Project Manager`
- 服务器
  负责人: `DevOps Developer`

## 角色和他们的职责
这里，我们使用一个逻辑的角色模型，来描述一个团队的组成和成员的职责。
在真实世界里，一个人可以扮演多个角色，当然，一个角色也可以被多个人共同承担。

- Project Manager
  负责项目流程的运作。
- Product Manager
  负责产品的需求定义。
- Architect
  负责产品的技术架构。
- Developer
  负责开发产品
- Tester
  负责测试产品
- DevOps Developer
  负责开发中的运维工作。
- Information Developer
  负责产品的文档编辑

### 项目经理的职责
- 负责建立与外界的沟通渠道
- 负责收集项目进度信息
- 负责收集项目的指数信息
  
### 架构师的职责
- [建立软件的框架](Architecture.md)
- 负责编辑代码规范
- 负责开发环境配置流程
- 负责代码版本控制流程
- 管理软件每个版本的依赖环境信息
- 管理软件每个版本的第三方组件版本信息

## 项目管理流程

1. [流程：项目流程](Process%20Project.md)
2. [流程：项目的估算](Process%20Estimation.md)
3. [流程：Feature管理](Process%20Feature%20Management.md)
4. [流程：Defect管理](Process%20Defect%20Management.md)
5. [流程：产品版本管理](./Process%20Product%20Versions.md)