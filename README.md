# 医院管理系统简介 java281

## 项目概述

医院管理系统是基于SpringBoot开发的，采用前后端分离的架构模式。系统主要包括管理员、医生和患者三种角色，涵盖了医生信息管理、患者信息管理、挂号信息管理、药物信息管理、检查项目管理、病床信息管理、排班信息管理等功能模块。

## 技术栈

- 后端：SpringBoot、Mybatis-Plus、MySQL、Redis
- 前端：Vue、AntV/G2Plot
- 工具：EasyPoi、Itextpdf

## 功能模块

### 系统角色

#### 管理员（Admin）

- 医生信息管理：添加、编辑医生信息
- 患者信息管理
- 挂号信息管理：查看挂号缴费状态、挂号状态
- 药物信息管理：添加、编辑药物，填写药物信息（编号、名称、单位、单价、出版商）
- 病床信息管理：增加床位，填写床号
- 排班信息管理：选择值班日期、科室、医生，进行排班
- 数据统计分析：挂号科室人数统计、患者性别比例统计、患者年龄分布统计

#### 医生（Doctor）

- 查看今日挂号列表、历史挂号列表
- 查看缴费状态、挂号状态
- 追诊
- 为患者申请住院，选择床位号
- 个人信息查询

#### 患者（Patient）

- 预约挂号：选择科室、医生进行挂号
- 查看我的挂号信息、查看报告单
- 查看住院信息、个人信息

## 运行环境

- 操作系统：Win10/11
- 开发工具：ideaIU-2022.3.3.win
- 开发语言：Java (jdk-8u371)、Vue(node.js 13.14)
- 项目管理工具：apache-maven-3.9.4
- 数据库：MySQL 8.0、Redis 7.0.10

## 部署步骤

1. 执行目录中的sql文件，Mysql用户名密码为：root / root
2. 启动Redis
3. 解压项目压缩包
4. 使用IDEA导入项目
5. 等待Maven下载Jar包，下载完成之后点击启动项目
6. 使用npm run dev启动前端工程

## 目录结构

```
- backend
  - src
    - main
      - java
      - resources
      - webapp
- frontend
  - src
    - assets
    - components
    - views
```

## 核心亮点

- 基于SpringBoot，具有高效率、易维护的优点
- 使用Mybatis-Plus简化数据库开发
- 前后端分离，易于扩展和维护
- 引入Redis，提高系统性能
- 使用AntV/G2Plot进行数据可视化，便于数据分析
- 遵循规范的开发流程，确保项目质量
- 灵活的角色权限控制，满足不同用户需求
- 详尽的功能模块，覆盖医院管理方方面面

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img12.360buyimg.com/ddimg/jfs/t1/324581/15/23816/13140/68d3eb1eF69552f2b/e3381441ee42b4d2.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/322816/1/13264/42189/68d3eb1eFf42d8fb2/465ce6ec56d64bf9.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/338516/3/13449/32181/68d3eb1fF00ef1f5f/90883f4eead52e3b.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/338982/9/13220/16508/68d3eb1fF8264cce3/b975b905a19fa6d6.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/332171/11/16737/23686/68d3eb20F2d5152f1/3ffc71c2f87eec59.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/337719/38/10997/17321/68d3eb20F14649f92/4b91ebcb2f17b5e2.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/159415/10/33831/32765/68d3eb20F940f8066/bf4fc3d9dcd3f601.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/344243/14/7043/23947/68d3eb20F3bf674da/b547c58082e1e7dd.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/339818/32/14231/27121/68d3eb21F3cefde28/eb8122dd7de2d5f1.jpg)

