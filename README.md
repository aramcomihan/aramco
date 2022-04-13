# Aram Co.

**若需部署 aramco，请转到 [aramco](https://github.com/aramcomihan/aramco/tree/vless) 分支。**

## 概述

本专案用于在 Heroku 上部署 Aram Co WebSocket，在合理使用的程度下，本镜像不会因为大量占用资源而导致封号。

部署完成后，每次启动应用时，运行的 AramCo 将始终为最新版本

## 部署

> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/aramcomihan/aramco)

 4. 回到专案首页，点击上面的链接以部署 AramCo

### 变量

## 接入 CloudFlare

以下两种方式均可以将应用接入 CloudFlare，从而在一定程度上提升速度。

 1. 为应用绑定域名，并将该域名接入 CloudFlare
 2. 通过 CloudFlare Workers 反向代理

## 注意

 1. **请勿滥用本专案，类似 Heroku 的免费服务少之又少，且用且珍惜**
 2. 若使用域名接入 CloudFlare，请考虑启用 TLS 1.3
 3. AWS 绝大部分 IPv4 地址已被 Twitter 屏蔽
