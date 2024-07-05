# WebChat

一个基于 Web 的简易聊天室。

## 目录

- [WebChat](#webchat)
  - [目录](#目录)
  - [简介](#简介)
  - [功能](#功能)
  - [安装](#安装)
  - [使用方法](#使用方法)
  - [环境变量](#环境变量)

## 简介

WebChat 是一个基于 Web 的简易聊天室，支持用户管理、公共聊天室、好友私聊等功能。此项目基于 Express 搭建 Web 应用，使用 Socket.IO 实现聊天功能，使用 MySQL 实现数据持久化，使用 Redis 实现会话管理和多服务器协同，使用 Nginx 实现反向代理。

## 功能

- 用户管理
- 实时消息通信
- 会话管理
- 数据持久化
- 多服务器协同
- 反向代理

## 安装

等待后续更新

## 使用方法

等待后续更新

## 环境变量

- `DB_HOST`: MySQL host
- `DB_USER`: MySQL 用户名
- `DB_PASSWORD`: MySQL 密码
- `DB_DATABASE`: MySQL 数据表
- `RD_HOST`: Redis host
- `RD_PORT`: Redis 端口
- `PORT`: 本地服务器监听端口

```
# .env 示例
DB_HOST=mysql
DB_USER=root
DB_PASSWORD=123456
DB_DATABASE=login
RD_HOST=redis
RD_PORT=6379
PORT=3000
```
