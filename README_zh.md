<p align="center">
<a href="https://ctradeex.io/"><img src="docs/images/ctradeex-icon.jpg" alt="banner" width="200px"></a>
</p>

<p align="center">
<b> CtradeExchange <i>digital currency, foreign exchange, stock trading , spot matching</i></b>
</p>

<p align=center>

<a href="https://twitter.com/intent/follow?screen_name=KubeSphere">
  <img src="https://img.shields.io/twitter/follow/KubeSphere?style=social" alt="follow on Twitter">
</a>
<a href="https://join.slack.com/t/kubesphere/shared_invite/enQtNTE3MDIxNzUxNzQ0LTZkNTdkYWNiYTVkMTM5ZThhODY1MjAyZmVlYWEwZmQ3ODQ1NmM1MGVkNWEzZTRhNzk0MzM5MmY4NDc3ZWVhMjE">
  <img src="https://img.shields.io/badge/Slack-600%2B-blueviolet?logo=slack&amp;logoColor=white">
</a>

<a href="https://www.youtube.com/channel/UCyTdUQUYjf7XLjxECx63Hpw">
  <img src="https://img.shields.io/youtube/channel/subscribers/UCyTdUQUYjf7XLjxECx63Hpw?style=social">
</a>

</p>


----

# 交易系统后台
> [English](README.md) | 中文

开源数字货币、外汇、股票交易系统，支持多种交易方式，现货撮合、合约全仓、合约隔离仓、杠杆现货、股票、外汇等。

# 功能清单：

- 1、支持多种交易策略：合约、杠杆、现货、以及风险对冲（射单交易模式）
- 2、丰富的开放接口，方便快速接入主流的支付系统和快速开发业务推广活动
- 3、多种客户端支持（H5、PC、APP），丰富的行情图标，多种指标
- 4、强大的后台管理，支持主白标模式，实现多种业务模式同时开展
- 5、灵活的参数配置能力，各种交易参数配置实时生效
- 6、稳定的行情架构，支持多源（coinapi、binance、ib、ig、longbridge等）互备


# 功能介绍：
- 1、客户端
- 2、管理后台

# 主要技术：

## 后端：
- 开发框架：Spring Boot 2.7
- 微服务框架：Spring Cloud 2021
- 安全框架：Spring Security + Spring OAuth 2.0
- 任务调度：Quartz 、 Saturn
- 数据库支持: MySQL、PostgreSQL、 MongoDB、 TiDB 、influxDB
- 持久层框架：MyBatis && MyBatis Plus
- 数据库连接池：Druid
- 服务注册与发现: Nacos
- 客户端负载均衡：Spring Cloud Loadbalancer
- 熔断组件：Sentinel
- 网关组件：Spring Cloud Gateway
- 日志管理：Logback
- 运行容器：Undertow
- 分布式事务：LCN、Seata
- 工作流: Activiti 5.22
- 数据同步：Canal
- 消息中间件：Kafka、RocketMQ
- 内存型数据库：Ignite
- 撮合引擎：Exchange-core
- 无锁队列：LMAX Disruptor
- 风控规则引擎：Drools
- 交易通讯协议 Netty + Dubbo
- 行情通讯协议 TCP + PB

## 前端：
- JS 框架：Vue、、Avue、nodejs
- CSS 框架：sass
- 组件库：ElementUI
- 打包构建工具：Webpack
- 客户端 Uniapp


# 服务定义：
服务说明



# 整体架构：
贴架构图



# 核心流程：
流程图，补充英文版本




