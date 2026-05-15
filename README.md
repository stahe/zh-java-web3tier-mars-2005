# 基于Struts、Spring和Java的三层Web架构与MVC模式

🔗 **相关文档：**
[基于Struts、Spring和Java的三层架构与MVC模式](https://stahe.github.io/zh-java-web3tier-mars-2005/)

---

## 📘 简介

本代码库收录了 2005 年 3 月至 7 月期间发表在 Developpez.com 上的两篇文章的内容。
这些文章采用循序渐进的教学方法，探讨了 Java Web 架构：

1. **Spring IoC**
   通过 Spring 框架介绍 **控制反转（IoC）**，也称为 **依赖注入（DI）**。

2. **三种三层 Web 架构示例**
   介绍一个用于管理在线购物的简化Web应用程序，该应用采用**MVC（模型-视图-控制器）**架构实现，并展示了三种技术变体。

---

## 🏗️ 涉及的架构

示例应用程序采用**三层**架构：

* **展示层**
* **业务逻辑层**
* **数据访问层**

**MVC** 模型通过三种不同方式实现：

### 1️⃣ Servlet + JSP

* 一个 **Servlet 控制器**
* 用于视图的 **JSP 页面**
* 手动 MVC 架构

### 2️⃣ Struts

* 基于 **Struts** 框架的 MVC 实现
* 通过 `ActionServlet` 进行集中控制
* 声明式操作映射

### 3️⃣ Spring MVC

* 使用 **Spring MVC** 框架
* 与 Spring 的 IoC 容器集成
* 面向依赖注入的配置

---

## 🎯 学习目标

* 理解 **三层架构** 的原理
* 掌握 **Java Web 环境中的 MVC 模式**
* 了解 **控制反转 (IoC)** 和依赖注入
* 比较不同的 MVC 实现方法
* 理解框架相对于手动实现的优势

---

## 🧩 使用的技术
* Java
* Servlet
* JSP
* Struts
* Spring Framework
* Spring MVC
---
## 📚 目标受众
本材料适用于：

* 希望了解传统 Web 架构的 Java 开发人员
* 希望对比“手动”MVC 与基于框架的 MVC 的任何人

---

## 🏷️ 历史背景

这些文章可追溯至 2005 年，反映了当时 Java Web 开发实践的现状。

