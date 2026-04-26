# 🍜 SkyTakeOut - 苍穹外卖系统

<div align="center">

![Java](https://img.shields.io/badge/Java-1.8+-orange.svg)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.3-brightgreen.svg)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue.svg)
![Redis](https://img.shields.io/badge/Redis-6.x-red.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

**一个完整的外卖点餐系统 | 前后端分离架构 | 企业级实战项目**

[功能特性](#-功能特性) • [技术栈](#-技术栈) • [快速开始](#-快速开始) • [项目展示](#-项目展示) • [系统架构](#-系统架构)

</div>

---

## 📖 项目简介

**SkyTakeOut（苍穹外卖）** 是一个基于 Spring Boot + 微信小程序的完整外卖点餐系统。项目采用前后端分离架构，包含用户端小程序和管理端 Web 后台，涵盖了从用户浏览菜品、下单支付到商家接单管理的完整业务流程。

### ✨ 项目亮点

- 🎯 **完整业务流程**: 覆盖外卖平台核心功能，从点餐到配送全流程
- 🏗️ **企业级架构**: 分层设计、AOP 切面、缓存优化、WebSocket 实时通信
- 🔐 **安全可靠**: JWT 认证、权限控制、数据加密、拦截器校验
- ⚡ **高性能**: Redis 缓存、数据库索引优化、连接池、负载均衡
- 📱 **多端适配**: 微信小程序 + Web 管理后台，支持多场景使用
- 🚀 **易于部署**: Docker 支持、详细文档、一键启动脚本

---

## 🚀 功能特性

### 👥 用户端（微信小程序）

| 功能模块 | 功能描述 |
|---------|---------|
| 🏠 首页浏览 | 菜品/套餐分类展示、搜索筛选、轮播图推荐 |
| 🛒 购物车 | 添加商品、修改数量、批量结算、实时计价 |
| 📋 订单管理 | 下单支付、订单跟踪、历史查询、评价晒单 |
| 📍 地址管理 | 收货地址 CRUD、默认地址设置、智能定位 |
| 💬 备注功能 | 口味偏好、特殊需求、个性化定制 |
| 👤 个人中心 | 用户信息、消费统计、优惠券管理 |

### 👨‍💼 管理端（Web 后台）

| 功能模块 | 功能描述 |
|---------|---------|
| 📊 数据统计 | 营业额分析、订单量趋势、用户增长、热销排行 |
| 👨‍💼 员工管理 | 账号管理、角色分配、权限控制、操作日志 |
| 🍽️ 菜品管理 | 菜品 CRUD、分类管理、口味配置、上下架控制 |
| 📦 套餐管理 | 套餐组合、定价策略、图片上传、状态管理 |
| 📋 订单处理 | 接单/拒单、配送管理、异常处理、订单导出 |
| 🏪 店铺管理 | 营业状态、公告设置、配送范围、营业时间 |
| 💼 工作台 | 今日数据概览、待处理事项、实时订单提醒 |

---

## 🛠️ 技术栈

### 后端技术

**核心框架**
- Spring Boot 2.7.3 - 快速开发框架
- MyBatis - ORM 持久层框架
- Spring Data Redis - Redis 缓存集成
- Druid - 阿里巴巴数据库连接池

**安全认证**
- JWT (jjwt 0.9.1) - Token 身份认证
- AspectJ - AOP 切面编程
- 自定义拦截器 - 登录校验、权限控制

**工具组件**
- Lombok - 简化 Java 代码
- FastJSON - JSON 数据处理
- PageHelper - MyBatis 分页插件
- Knife4j - Swagger API 文档增强
- Apache POI - Excel 报表导出
- 阿里云 OSS - 对象存储服务

**实时通信**
- WebSocket - 订单实时推送、语音提醒
- Spring Task - 定时任务调度

**其他**
- 微信支付 SDK - 在线支付集成
- HttpClient - HTTP 客户端

### 前端技术

**微信小程序**
- uni-app - 跨平台开发框架
- Vue.js - 渐进式 JavaScript 框架
- Uni UI - uni-app 组件库

**管理后台**
- Vue.js - 前端框架
- Element UI - Vue 组件库
- ECharts - 数据可视化图表
- Axios - HTTP 请求库

**服务器**
- Nginx 1.20.2 - 反向代理、负载均衡、静态资源托管

### 开发工具

- IDE: IntelliJ IDEA / VS Code
- 数据库: MySQL 8.0+
- 缓存: Redis 6.x+
- 接口测试: Postman / Knife4j
- 版本控制: Git / GitHub

---

## 📁 项目结构


---

## 🙏 致谢

感谢以下开源项目：

- [Spring Boot](https://spring.io/projects/spring-boot)
- [MyBatis](https://mybatis.org/mybatis-3/)
- [Redis](https://redis.io/)
- [uni-app](https://uniapp.dcloud.net.cn/)
- [Element UI](https://element.eleme.io/)

---

<div align="center">

**如果这个项目对你有帮助，请给一个 ⭐ Star 支持一下！**

[⬆ 回到顶部](#-skytakeout---苍穹外卖系统)

</div>


