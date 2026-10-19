## Hi there 👋 大家好 👋

我是 **FutureWL**，做企业级数字化平台与 AI Agent 工具链。

我的开源重心只有一个：**猎手云 LieShouCloud** —— 把「一套代码库装配出任何行业、任何形态的企业数字化平台」做成可复用的工程体系。

## 🏗️ 猎手云开源地图

> 产品（行业方案）= **core 底座** + **能力域组合**（crm / erp / mes / iot / legal / edu…）
> 交付形态 = 单体 / 微服务（配置驱动，零重写演进）
> 数据库 = MySQL / PostgreSQL（代码只写 JPA，纯配置切换）
> 部署位置 = 云端 / 客户机房私有化（私有化自动挂载 License / 离线升级）

| 层 | 仓库 | 技术栈 |
| --- | --- | --- |
| **总入口** | [LieShouCloud](https://github.com/FutureWL/LieShouCloud) | Java 21 · Spring Boot 3.5 |
| **后端底座** | [lieshou-framework](https://github.com/HUNTERCAT-DIGITAL/lieshou-framework) | Java · Spring Cloud |
| **装配形态** | [lieshou-standalone](https://github.com/HUNTERCAT-DIGITAL/lieshou-standalone)（单体） · [lieshou-cloud](https://github.com/HUNTERCAT-DIGITAL/lieshou-cloud)（微服务） | Java |
| **微服务模块** | [auth](https://github.com/HUNTERCAT-DIGITAL/lieshou-cloud-auth-services) · [user](https://github.com/HUNTERCAT-DIGITAL/lieshou-cloud-user-services) · [admin](https://github.com/HUNTERCAT-DIGITAL/lieshou-cloud-admin-services) · [approval](https://github.com/HUNTERCAT-DIGITAL/lieshou-cloud-approval-services) · [gateway](https://github.com/HUNTERCAT-DIGITAL/lieshou-cloud-gateway-services) | Java · Spring Cloud |
| **契约层** | [contract-types](https://github.com/HUNTERCAT-DIGITAL/lieshou-contract-types) · [contract-api](https://github.com/HUNTERCAT-DIGITAL/lieshou-contract-api) · [contract-config](https://github.com/HUNTERCAT-DIGITAL/lieshou-contract-config) · [ark-contract-types](https://github.com/HUNTERCAT-DIGITAL/lieshou-ark-contract-types) | TypeScript · OpenAPI |
| **前端核心层** | [lieshou-core-web](https://github.com/HUNTERCAT-DIGITAL/lieshou-core-web) | TypeScript · React |
| **组件库** | [lieshou-ui](https://github.com/HUNTERCAT-DIGITAL/lieshou-ui) | TypeScript |
| **多端** | [admin-web](https://github.com/HUNTERCAT-DIGITAL/lieshou-app-admin-web) · [mobile](https://github.com/HUNTERCAT-DIGITAL/lieshou-app-mobile) · [desktop](https://github.com/HUNTERCAT-DIGITAL/lieshou-app-desktop) · [mini-program](https://github.com/HUNTERCAT-DIGITAL/lieshou-app-mini-program) · [harmony](https://github.com/HUNTERCAT-DIGITAL/lieshou-app-harmony) | React · Electron · 微信小程序 · ArkTS |

**核心亮点**：一码多产 · 模块化单体 ↔ 微服务一键切换 · 多数据库可移植 · 私有化交付体系 · 多前端入口

📖 架构总纲：[LieShouCloud/docs/ARCHITECTURE.md](https://github.com/FutureWL/LieShouCloud/blob/main/docs/ARCHITECTURE.md)

> 开源范围说明：上游工程底座与契约层开源（**Apache-2.0**）；客户交付件、行业能力域与私有化配置不开源。
> 早期学习/教程类仓库已归档，不在开源主线内。

## 🔭 正在做的事

- **猎手云 LieShouCloud** —— 一套代码库装配任意行业 / 任意形态的企业数字化平台；多端交付已落地 legalmind、huntercat、zhiye、linkesecurity 等客户仓
- **AI Agent 工程** —— 多智能体 · 多会话并行协作的编排与治理、Agent 工具链、浏览器/桌面本地自动化闭环
- 业余：3D 打印、无人机（UAV）

## 📫 联系

- 🌐 [猎手云](https://huntercat.cn) ｜ 📝 [博客](https://FutureWL.github.io) ｜ 🐦 [X / Twitter](https://x.com/Future0929)
- 📣 公众号「**AI进化论**」（魏来AI进化论）— 写 AI 落地与工程实践，[最近一篇](https://mp.weixin.qq.com/s/h1Q8cr7IXbTlB-7_RtT2pQ)
