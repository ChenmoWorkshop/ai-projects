# AI 编程项目库 · ai-projects

与 AI 结对编程完成的项目合集。每个项目独立成仓库，本页做总览导航。

> 人类提出需求与审美判断，AI 负责实现——这个库记录这种协作方式的产出。

---

## 项目列表

### 创作工坊 · Chenmo Studio

**单文件个人创作工作台：待办 / 灵感 / 内容 / 复盘，带完整账号体系与云同步。**

整个前端就是一个 `index.html`——没有框架、没有 npm、没有打包。后端是一个云函数加三个数据集合，每个人有自己独立的账号和一份数据。

- **在线体验**：<https://chenmo-studio.app.workbuddy.host/>
- **源码**：[ChenmoWorkshop/chenmo-studio](https://github.com/ChenmoWorkshop/chenmo-studio)（MIT，已开源）
- **技术栈**：原生 HTML / CSS / JavaScript · 腾讯云 CloudBase 云函数 · 文档型数据库

**核心特性**

| | |
|---|---|
| 四大模块 | 待办（优先级）、灵感（随手记）、内容（创作管理）、复盘（定期回顾） |
| 账号体系 | 注册 / 登录 / 90 天 token 会话 / 数据按账号隔离 / 游客体验模式 |
| 每日名言 | 162 条中外哲学家词库，每天 10 条中西方各半交替，点击切换 |
| 自定义 | 工作台名称、副标题、头像（本地压缩后上传） |
| 工程特点 | 零构建 · 单文件 · PWA 可加到主屏幕 · 浏览器本地不落业务数据 |

**为什么值得看**

- 演示了「静态页无法直连 CloudBase SDK」这一常见限制下，用**云函数代理**打通全链路的完整做法
- 自研账号体系（`scrypt` 加随机盐 + 恒定时间比对 + token 会话），绕开了短信收费 / SMTP 配置 / 小程序限制的现成方案
- 附带两个可复用的 **WorkBuddy 技能包**：数据上云迁移、账号体系搭建
- 免费额度实测用量占比 1–2%，个人使用零成本

---

## 关于这个库

这个库里的项目有两个共同点：

1. **需求来自人，实现来自 AI。** 没有预先写好的技术方案，是从「我想要一个这样的东西」开始的。
2. **优先考虑能不能被读懂、被复用。** 所以每个项目都会把踩过的坑写进 README——那些真正花掉时间的部分，比功能列表更值得留档。

## 约定

- 新项目按 `项目名/` 目录收纳，或独立建仓库后在本页登记
- 每个项目要求附带：可运行的 README、明确的部署步骤、License
- 可见性：涉及个人隐私数据（如私人笔记内容、账号凭据）的部分不入库；项目代码本身默认公开，方便别人拿去改

## 关键词

<details>
<summary>搜索索引 / Search keywords（点击展开）</summary>

AI 编程 · AI 结对编程 · 个人工作台 · 待办清单 · 任务管理 · 灵感记录 · 内容管理 · 复盘 · 单文件应用 · 零构建 · 原生 JavaScript · 云同步 · 账号体系 · 数据隔离 · 腾讯云开发 · 云函数 · Serverless · PWA · 免费部署 · 自部署 · 开源项目

AI coding · AI pair programming · vibe coding · personal workbench · productivity app · task manager · todo app · notes app · content planner · single-file app · zero build · vanilla JavaScript · cloud sync · user authentication · serverless · Tencent CloudBase · cloud function · PWA · self-hosted · open source projects

</details>
