<div align="center">

<img src="https://raw.githubusercontent.com/onebook-living/.github/main/profile/assets/logo-mark.png" alt="一本 OneBook" width="48" height="48" />

# 一本OneBook

**业务说「Redis 慢」，十之七八要先证明：慢是不是真的发生在 Redis 里。**

*程序员面试知识操作系统 · 一个领域一本书 · 面试问题驱动 · 活书*

[![21 篇已上线](https://img.shields.io/badge/已上线-21_篇-1E3A5F?style=for-the-badge)](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=books)
[![7 篇试读](https://img.shields.io/badge/免费试读-7_篇-2F6B4F?style=for-the-badge)](https://github.com/onebook-living#精选试读)
[![Question Driven](https://img.shields.io/badge/Question-Driven-B8860B?style=for-the-badge)](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=books)

### 👉 [先看这篇 · Redis 变慢了，你怎么系统排查？](https://onebook.example.com/books/1001/articles/1001012?utm_source=github&utm_medium=readme&utm_content=trial&utm_campaign=redis-变慢排查)

*约 20 分钟 · FREE 试读 · 一篇看深度，不是背八股*

[官网](https://onebook.example.com/?utm_source=github&utm_medium=readme&utm_content=home) · [书架](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=books) · [会员](#membership)

</div>

> **30 秒回答**：业务说「Redis 慢」，十之七八要先证明：慢是不是真的发生在 Redis 里。很多是连接池排队、跨机房网络在拖 —— Redis 监控反而很干净。确认是 Redis 内慢以后，再用慢日志和命令统计找「哪辆卡车堵了单车道」：凶命令 / 大 key / 热 key，还是后台 fork 尖刺。别一慢就扩容或重启。

---

## 你可能正遇到这些

| 痛点 | 典型场景 |
|------|----------|
| **资料太多、互相打架** | 博客、课程、AI 各说各话，收藏夹满却更焦虑 |
| **背了词，追问就露馅** | 30 秒能背，一追问机制就接不住 |
| **不知道下一题读啥** | 收藏夹很多，没有路径和完成度 |
| **买完就静止** | 课程目录很长，版本变了没人更 |

---

## 一本是什么

**一本OneBook = 程序员面试知识操作系统** — 每个领域 **一本活书**，按 **面试问题 + 热度** 组织，不是按章节编号刷课。

| 理念 | 对你意味着什么 |
|------|----------------|
| **一个领域一本书** | Redis / MySQL / Agent … 各一本，不拆成十门小课 |
| **Question Driven** | 按面试现场问法组织，不是「第几章」 |
| **Living Book** | 有 Version、有更新日志，活书在长 |
| **一篇讲透** | 30 秒 → 原理 → 生产，追问写进同一篇厚文 |

> **我们不是什么**：课程平台 · 静态文档 · 博客合集 · 「又一个 Redis 教程」

---

## 面试文章很多，为什么要点进来？

GitHub / 知乎 / 掘金上 **Redis 为什么快** 的文章已经够多了。点进一本，不是因为标题新鲜，而是因为：

1. **先试再信** — 每书 3 篇 FREE 标杆试读，深度与会员篇同标准
2. **不是摘要，是讲透** — 心理追问 → 机制链 → 生产实践，追问接得住
3. **有地图，不盲读** — 公开目录 + Version，一眼看见还缺哪些题
4. **敢纠偏** — 例如：快 **并不** 只是因为单线程

**你买的不是多一篇博客，是「这个领域按面试问法已经整理好的那一本」+ 后续更新。**

---

## 精选试读

- ⭐ **[Redis 变慢了，你怎么系统排查？](https://onebook.example.com/books/1001/articles/1001012?utm_source=github&utm_medium=readme&utm_content=trial&utm_campaign=redis-变慢排查)** · 约 20 分钟 — 先证明慢在不在 Redis 内；再用慢日志找凶命令 / 大 key / 热 key / fork 尖刺
- **[如何用 Redis 做分布式锁？Redlock 还要不要？](https://onebook.example.com/books/1001/articles/1001011?utm_source=github&utm_medium=readme&utm_content=trial&utm_campaign=redis-分布式锁)** · 约 24 分钟 — SET NX PX + token + Lua 解锁 + 看门狗；临界区尽量短
- **[Redis 为什么快？](https://onebook.example.com/books/1001/articles/1001001?utm_source=github&utm_medium=readme&utm_content=trial&utm_campaign=redis-为什么快)** · 约 8 分钟 — 纯内存 · IO 多路复用 · 数据结构 · 非「单线程所以快」
- **[MySQL 变慢了，你怎么系统排查？](https://onebook.example.com/books/1003/articles/1003004?utm_source=github&utm_medium=readme&utm_content=trial&utm_campaign=mysql-变慢排查)** · 约 20 分钟 — 连接池 / 网络 / 从库 lag / InnoDB 内慢，分段证明再下钻
- **[事务隔离与 MVCC 是怎么实现的？](https://onebook.example.com/books/1003/articles/1003002?utm_source=github&utm_medium=readme&utm_content=trial&utm_campaign=mysql-事务隔离与mvcc)** · 约 20 分钟 — RR 默认 · Read View · undo 链 · 快照读 vs 当前读
- **[索引为什么快？B+ 树与最左前缀](https://onebook.example.com/books/1003/articles/1003001?utm_source=github&utm_medium=readme&utm_content=trial&utm_campaign=mysql-索引为什么快)** · 约 18 分钟 — 聚簇 / 二级索引 · 少读磁盘页才是本质
- **[大模型、RAG、Tool、Agent、MCP 各解决什么？](https://onebook.example.com/books/1005/articles/1005001?utm_source=github&utm_medium=readme&utm_content=trial&utm_campaign=agent-概念地图)** · 约 12 分钟 — 五件事分清楚，Agent 面试不混概念

---

## 书架

[![已上线 3 本](https://img.shields.io/badge/已上线-3_本-1E3A5F?style=flat-square)](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=shelf-stats)
[![已发布 21 篇](https://img.shields.io/badge/已发布-21_篇-57606A?style=flat-square)](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=shelf-stats)
[![标杆试读 7 篇](https://img.shields.io/badge/标杆试读-7_篇-2F6B4F?style=flat-square)](https://github.com/onebook-living#精选试读)
[![筹备中 6 本](https://img.shields.io/badge/筹备中-6_本-B8860B?style=flat-square)](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=shelf-stats)

### [一本 Redis](https://onebook.example.com/books/1001?utm_source=github&utm_medium=readme&utm_content=book-redis) · v2.8 · ★98 · 6 篇已上线

程序员 Redis 面试活书 · 规划 72+ 题 · 3 篇 FREE 试读（为什么快 / 变慢排查 / 分布式锁）

<details>
<summary><strong>8 个模块 · 目录 23 题</strong></summary>

| 模块 | 题数 |
|------|-----:|
| 基础原理 | 5 |
| 持久化 | 1 |
| 高可用 | 2 |
| 集群 | 1 |
| 缓存设计 | 1 |
| 并发与分布式 | 3 |
| 性能排障与场景 | 1 |

</details>

[在官网查看目录与试读 →](https://onebook.example.com/books/1001?utm_source=github&utm_medium=readme&utm_content=book-redis)

---

### [一本 MySQL](https://onebook.example.com/books/1003?utm_source=github&utm_medium=readme&utm_content=book-mysql) · v0.5 · ★95 · 5 篇已上线

程序员 MySQL 面试活书 · 规划 68+ 考点 · FREE 试读：索引 / MVCC / 变慢排查

<details>
<summary><strong>8 个模块 · 目录 33 题</strong></summary>

| 模块 | 题数 |
|------|-----:|
| 索引 | 1 |
| 事务与锁 | 2 |
| SQL 与性能 | 1 |
| 排障与场景 | 1 |

</details>

[在官网查看目录与试读 →](https://onebook.example.com/books/1003?utm_source=github&utm_medium=readme&utm_content=book-mysql)

---

### [一本 AI Agent](https://onebook.example.com/books/1005?utm_source=github&utm_medium=readme&utm_content=book-agent) · v0.2 · ★95 · 10 篇已上线

规划 82 考点 · 入门路径 13 篇 FREE · 概念地图 → 扫盲 → 面试锚点

<details>
<summary><strong>9 个模块 · 目录 39 题</strong></summary>

| 模块 | 题数 |
|------|-----:|
| 零基础扫盲 | 6 |
| 基础与架构 | 4 |
| 推理与规划 | 4 |
| 更多模块 | 见官网目录 |

</details>

[在官网查看目录与试读 →](https://onebook.example.com/books/1005?utm_source=github&utm_medium=readme&utm_content=book-agent)

---

**筹备中**：Java · Kafka · Dubbo · RocketMQ · Spring Cloud · Web3 交易所

👉 **[打开官网书架 · 查看全部知识书](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=books)**

---

## 怎么读

```text
GitHub / 搜索 → 精选试读 1 篇（30 秒 + 原理 + 生产）
  → 觉得讲得透 → 知识星球会员 → 官网绑定 → 全书 + 后续 Version
```

---

## 最近更新

- **2026-08-25** · 一本 Redis v2.8 · Phase A 新篇 8 题登记（筹备中）
- **2026-08-25** · 一本 AI Agent v0.2 · 目录 39 题 · 入门路径 13 FREE
- **2026-08-24** · 一本 MySQL v0.5 · 目录同步 33 篇锚点
- **2026-08-20** · 一本 MySQL · FREE《MySQL 变慢了，你怎么系统排查？》

完整 Version → [官网书架](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=books)

---

## 开发者 · 入口

| 资源 | 说明 |
|------|------|
| [官网 · 书架](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=books) | 活书目录 · 试读 · 阅读 |
| [活书 Version](https://onebook.example.com/books?utm_source=github&utm_medium=readme&utm_content=books) | 各书 changelog · 篇目进度 |

*GitHub 仅承载 Org 品牌 README；正文经官网与会员站分发。*

---

<a id="membership"></a>

## 会员

创始会员 **¥299/年**（正式价以官网为准）· 试读满意再决定 · 续费创始价保留

会员解锁全书 + 后续新书与 Version 更新

[知识星球 · 加入会员](#membership) · [已购 · 绑定指引](https://onebook.example.com/guide/bind-planet?utm_source=github&utm_medium=readme&utm_content=bind)

---

<div align="center">

*一本OneBook · 一个领域一本书 · 面试问题驱动 · 活书*

*Profile README · ops-format-v1.2 · 2026-08-28*

</div>
