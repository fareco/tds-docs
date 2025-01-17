---
id: overview
title: 云引擎服务总览
sidebar_label: 总览 
---



云引擎提供了 Node.js、Python、PHP、Java、.Net、Go 等多种环境来运行服务端程序。你只需要提供服务端的业务逻辑（网站或云函数等），而服务端的多实例负载均衡，不中断服务的平滑升级等都由云引擎提供支持。

下面为你了解云引擎提供一个索引：

* [快速入门](/v2/sdk/engine/guide/quickstart)：快速的了解如何创建一个云引擎项目，本地开发调试，以及如何部署到云端。
* [运行方案](/v2/sdk/engine/guide/plan)：了解云引擎对较大的商业应用如何提供多实例以及运维支持，以及对学习和测试应用的支持。
* [网站托管](/v2/sdk/engine/guide/webhosting)：使用你熟悉的语言开发一个 web 程序，提供静态和动态路由，开发一个 web 站点；或者为移动应用提供一个介绍页；或者开发一个管理员控制台。
* [云函数](/v2/sdk/engine/guide/cloudfunction)：可以将各平台客户端(Andorid、 iOS、浏览器等)的一些公共逻辑独立成一个公共的方法在云引擎中实现，各个 SDK 直接调用该方法，各平台客户端直接调用，并且云引擎更新相比客户端更新更加灵活容易；或者需要一些 Hook 函数，比如用户注册后执行一段业务逻辑；或设置一个定时任务在每天晚上清理数据等。
* [命令行工具 CLI](/v2/sdk/engine/guide/cli)：用来管理和部署云引擎项目的工具。它不仅可以部署、发布和回滚云引擎代码，对同一个云引擎项目做多应用管理，还能查看云引擎日志，批量将文件上传到 LeanCloud 云端。
* [云引擎 REST API 指南](/v2/sdk/engine/guide/rest)：直接通过 REST API 接口调用云函数。
* [LeanCache 指南](/v2/sdk/engine/guide/redis)：云引擎应用可以访问 LeanCache。LeanCache 使用 Redis 来提供高性能、高可用的 Key-Value 内存存储，可以在一些特殊场景（如秒杀、抢红包等）为应用提供很好的性能表现；或者对读写比例很高的数据做缓存，减少对存储服务的压力，提高应用性能表现。
* LeanDB 指南：除了 Redis 外，在云引擎中可以根据需要来配置 [MySQL](/v2/sdk/engine/guide/mysql)、[MongoDB](/v2/sdk/engine/guide/mongo)、[ElasticSearch](/v2/sdk/engine/guide/es) 等不同数据库，相信可以让更多的现有（开源）方案直接跑在云引擎里面，给大家带来更多的便利。
* [云队列（Cloud Queue）指南](/v2/sdk/engine/guide/cloudqueue)：云队列实现了重试、去重、结果查询、延时任务、定时任务等功能，是对云函数功能的一个补充。尚未运行的任务会以一种可靠的方式暂存在云队列，即使你的云引擎因部署、过载、崩溃而重启，任务也不会丢失，云队列会等待你的云引擎实例恢复正常后继续运行它们。
* [云引擎常见问题解答](/v2/sdk/engine/guide/faq)：希望大多数关于云引擎的问题，都能在这里找到答案。
