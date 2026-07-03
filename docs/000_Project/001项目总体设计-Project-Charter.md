# 第001章：项目总体设计（Project Charter）

# 印染智能工厂平台（YDSmart）

Version：V1.0

Last Update：2026-07-03

## 1. 项目简介

### 项目名称

YDSmart（YinDye Smart Factory）

### 项目定位

YDSmart 是一套面向印染行业的 ERP + APS + MES + EMS + BI + AI
一体化平台，实现订单、计划、生产、质量、仓储、能源、经营分析及 AI
辅助决策统一管理。

## 2. 建设目标

-   智能排产
-   自动派工
-   实时数据采集
-   AI分析与预测
-   能源优化
-   成本优化
-   设备联网
-   数据驾驶舱

## 3. 技术架构

-   前端：Vue3 + TypeScript
-   后端：ASP.NET Core Web API
-   数据库：SQL Server
-   缓存：Redis
-   消息队列：RabbitMQ
-   AI：OpenAI（RAG / MCP）

## 4. 系统模块

1.  系统管理
2.  ERP
3.  APS
4.  MES
5.  WMS
6.  EMS
7.  QMS
8.  BI
9.  AI助手
10. 移动端

## 5. 开发规范

-   DDD
-   SOLID
-   Clean Architecture
-   Repository Pattern
-   Unit Of Work
-   RESTful API
-   Swagger
-   Serilog
-   XML 注释
-   禁止 SQL 拼接
-   禁止重复代码
