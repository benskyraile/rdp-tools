# Multilogin 6 浏览器自动化功能使用指南

本文将详细介绍如何快速上手 Multilogin 6 的浏览器自动化功能，帮助您高效管理多账号操作。

## 一、软件下载与账号创建

要使用 Multilogin 6 的自动化功能，首先需要完成以下准备工作：

1. 下载最新版 Multilogin 6 软件
2. 创建用户账号
3. 选择合适的订阅方案

👉 [【点击查看】2025年最新 Multilogin 优惠码及特价套餐活动方案汇总](https://bit.ly/multIlogin)

## 二、安装与配置流程

### 1. 软件下载与安装
访问 Multilogin 官网下载页面获取最新安装包。安装完成后，打开软件并点击"创建新账户"按钮完成注册。

### 2. 订阅方案选择
Multilogin 提供两种主要方案：
- Scale 方案：适合中小规模自动化需求
- 定制方案：满足企业级大规模自动化需求

两种方案均支持 REST API 和 Local API 功能，可根据实际需求选择。

## 三、端口配置指南

为确保软件稳定运行，建议预先设置监听端口：

1. 启动 Multilogin 软件
2. 进入"我的账户"页面
3. 点击"打开日志文件目录"按钮
4. 返回上级目录 `/.multiloginapp.com`
5. 打开 `app.properties` 文件
6. 添加配置语句：`multiloginapp.port=35000`

### Mac 用户特别提示
在 macOS 系统中：
1. 打开 Finder 并按下 `Cmd + Shift + H` 进入用户文件夹
2. 按下 `Cmd + Shift + .` 显示隐藏文件夹
3. 找到 `/.multiloginapp.com/data` 目录

## 四、API 功能启用

完成基础配置后，您就可以：
- 通过 REST API 实现远程控制
- 使用 Local API 进行本地自动化操作
- 开发自定义脚本实现批量操作

如需了解更多高级功能，建议参考官方文档或联系技术支持团队。