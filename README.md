# universal-traffic-aggregator

[English](./README-en.md) | 简体中文

# 重要提示

1.本项目从起步到开发到部署均有文档和详细视频教程

2.本项目需要您有一定的golang和vue基础

3.您完全可以通过我们的教程和文档完成一切操作，因此我们不再提供免费的技术服务，如需服务请进行[付费支持]()

4.如果您将此项目用于商业用途，请遵守Apache2.0协议并保留作者技术支持声明。您需保留如下版权声明信息，以及日志和代码中所包含的版权声明信息。所需保留信息均为文案性质，不会影响任何业务内容，如决定商用【产生收益的商业行为均在商用行列】或者必须剔除请[购买授权]()

## 1. 基本介绍

### 1.1 项目介绍

> universal-traffic-aggregator(UTA)是一个基于 [vue](https://vuejs.org) 和 [gin](https://gin-gonic.com) 开发的全栈前后端分离的《市场推广-商业转化一体化平台》，集成了文章发布、发帖、资料、知识付费课程、待办Todo、会员体系设置、支付接入，项目会持续更新（电商版块、PDF版块、教培版块即将上线），让您把更多时间专注在业务拓展上。

[在线预览](https://www.yhyk.fun/yhyk/): https://www.yhyk.fun/yhyk/

测试用户名：19102060001

测试密码：19102060001Aa

### 1.2 贡献指南

Hi! 首先感谢你关注universal-traffic-aggregator。

universal-traffic-aggregator 是一套为快速承接公域流量准备的一整套前后端分离架构式的市场推广-商业转化一体化平台，旨在快速承接公域流量，提供专业文章、发帖、资料、知识付费产品等通用社交功能。

universal-traffic-aggregator 的成长离不开大家的支持，如果你愿意为 universal-traffic-aggregator 提供建议，请阅读以下内容。

#### 1.2.1 Issue 规范
- issue 仅用于提交 Bug 或 Feature 以及设计相关的内容，其它内容可能会被直接关闭。
									      
- 在提交 issue 之前，请搜索相关内容是否已被提出。

#### 1.2.2 Pull Request 规范
- 请先 fork 一份到自己的项目下，不要直接在仓库下建分支。

- commit 信息要以`[文件名]: 描述信息` 的形式填写，例如 `README.md: fix xxx bug`。

- 如果是修复 bug，请在 PR 中给出描述信息。

- 合并代码需要两名维护人员参与：一人进行 review 后 approve，另一人再次 review，通过后即可合并。

## 2. 使用说明

### 2.1 server项目

使用 `Goland` 等编辑工具，打开server目录，不可以打开 gin-vue-admin 根目录

```bash

# 克隆项目
git clone https://github.com/EasifyCoder/universal-traffic-aggregator.git
# 进入server文件夹
cd server

# 使用 go mod 并安装go依赖包
go generate

# 运行
go run . 

```

### 2.2 web项目

```bash
# 进入web文件夹
cd web

# 安装依赖
npm install

# 启动web项目
npm run serve
```

### 2.3 swagger自动化API文档

#### 2.3.1 安装 swagger

``` shell
go install github.com/swaggo/swag/cmd/swag@latest
```

#### 2.3.2 生成API文档

```` shell
cd server
swag init
````

## 3. 技术选型

- 前端：用基于 [Vue](https://vuejs.org) 的 [Element](https://github.com/ElemeFE/element) 构建基础页面。
- 后端：用 [Gin](https://gin-gonic.com/) 快速搭建基础restful风格API，[Gin](https://gin-gonic.com/) 是一个go语言编写的Web框架。
- 数据库：采用`MySql` > (5.7) 版本 数据库引擎 InnoDB，使用 [gorm](http://gorm.cn) 实现对数据库的基本操作。
- API文档：使用`Swagger`构建自动化文档。
- 配置文件：使用 [viper](https://github.com/spf13/viper) 实现`yaml`格式的配置文件。
- 日志：使用 [zap](https://github.com/uber-go/zap) 实现日志记录。

## 4. 项目架构

### 4.1 系统架构图

### 4.2 目录结构

## 5. 主要功能

UTA项目包含完整的前端、后端与运营后台。主要功能介绍以前端页面展示的功能为主，所有功能均可在运营后台进行设置。

- 文章阅读：后台可设置文章类别，基于类别进行文章的编写和发布。用户可对文章进行点赞、收藏、评论等操作。
- 发帖：用户登录后可自由发帖，每个帖子包含文本与图片，用户可选择发布在对应的帖子类别下。
- 会员：完善的会员体系与积分体系，增强用户粘性。
- 资料：资料可设置为免费资料与付费资料。支持设置会员价、会员免费、会员专属等高阶功能。
- 图文课程：可设置为免费课程与付费课程。支持设置会员价、会员免费、会员专属等高阶功能。承接知识付费体验课、训练营、陪跑营的完美载体。
- 工具导航：提供常用工具和网站的快速导航，包括开发工具、设计工具、学习资源等分类整理，方便用户快速找到所需工具。
- 待办：个人任务管理系统，支持创建、编辑、删除待办事项，设置优先级和截止日期，帮助用户高效管理日常任务。
- 每日快讯：聚合每日重要新闻和行业动态，提供简洁的新闻摘要和深度分析，让用户快速了解最新资讯和趋势。

## 6. 联系方式

| 微信 |
|  :---:  | 
| <img width="150" src="./assets/宇皓AI.png"> 


## 7. 捐赠

如果你觉得这个项目对你有帮助，你可以请作者喝饮料 :tropical_drink:

## 8. 注意事项

请严格遵守Apache 2.0协议并保留作品声明，去除版权信息请务必获取授权，未授权去除版权信息将依法追究法律责任