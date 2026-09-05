# 👋 Hi, I'm 余翰林

用 AI 把想法变成现实 · Turning ideas into reality with AI

---

## 💬 About Me

重庆邮电大学大数据管理与应用专业本科生在读。对前沿技术和 AI 抱有极大兴趣，喜欢借助 AI 把自己的想法快速落地——并且不止于「能跑就行」：目前独立设计并维护两套已上线的全栈系统（学生会线上交流平台、个人工作台 PWA），沉淀出自己的一套 AI 协作开发流程——需求调研与方案成档、拆解成详尽任务书交由 AI 实现、CI 门禁与自动化测试把关、语义化版本持续发版、每轮踩坑复盘沉淀成文档。始终保持高强度的学习热情，乐于接触和尝试新工具、新框架、新思路。

Undergraduate student at CQUPT, majoring in Big Data Management & Application. Passionate about cutting-edge tech and AI — I love turning ideas into working software with the help of AI, and I care just as much about the engineering after "it runs". I currently design and maintain two shipped full-stack systems (a Student Union collaboration platform and a personal workbench PWA), and have built my own AI-native development workflow: research and plans archived as documents, detailed task specs handed to AI for implementation, everything gated by CI, automated tests and semantic versioning, with pitfalls reviewed and documented after every release. Always eager to learn, explore new tools, and push my limits.

---

## 🛠 Tech Stack

**Frontend**
![React](https://img.shields.io/badge/React-19.2-61dafb?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-6.0-3178c6?logo=typescript)
![Vite](https://img.shields.io/badge/Vite-8.2-646cff?logo=vite)
![Ant Design](https://img.shields.io/badge/Ant_Design-6.4-0170fe?logo=antdesign)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-38bdf8?logo=tailwindcss)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-v5-ff4154)

**Backend & Data**
![Supabase](https://img.shields.io/badge/Supabase-2.112-3ecf8e?logo=supabase)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?logo=postgresql)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel)

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?logo=typescript)
![Java](https://img.shields.io/badge/Java-Basics-ed8b00?logo=openjdk)
![Python](https://img.shields.io/badge/Python-Basics-3776ab?logo=python)

**AI & Tools**
![Claude Code](https://img.shields.io/badge/Claude_Code-d97706?logo=anthropic)
![ChatGPT](https://img.shields.io/badge/ChatGPT-74aa9c?logo=openai)
![Git](https://img.shields.io/badge/Git-f05032?logo=git)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088ff?logo=githubactions)
![VS Code](https://img.shields.io/badge/VS_Code-007acc?logo=visualstudiocode)

---

## 🏛️ Featured Projects

### 学生会线上交流平台 `v4.0`

为重庆邮电大学学生会（12 部门）构建的内部办公与协作平台，以 PWA 形态交付（可安装、离线可用、亮/暗双主题），已稳定运行。

A full-stack internal platform for CQUPT Student Union (12 departments), shipped as an installable offline-ready PWA, in production.

**核心功能 / Core Features:**

| 模块 | 亮点 |
|------|------|
| ✅ 任务管理 | 看板拖拽 + 里程碑 + 模板 + 审核流 + 移交 |
| 📢 部门公告 | 已读确认 + 关联任务 + 一键转任务 |
| 🎫 活动抢票 | 限时限量 + PostgreSQL RPC 原子操作 + FOR UPDATE 行锁防超卖 |
| 💬 部门论坛 | Markdown 发帖 + 分类 + 知识库模板 |
| 🔔 实时通知 | Supabase Realtime + 8 类自动触发 |
| 📊 数据分析 | 使用事件埋点 + AnalyticsDashboard 看板 + 页面排名 + 错误日志 |
| 👥 权限体系 | 6 种角色 + 12 部门 + 邀请码管理（有效期/次数/撤销） |
| 🌓 主题模式 | 亮 / 暗 / 跟随系统三态切换，首帧防闪烁，全模块适配 |
| 📱 PWA | 离线访问 + 版本更新推送 + 添加到主屏幕 |
| 📎 文件上传 | 拖拽上传 + MIME 白名单 + Storage 所有者保护 |
| 🔍 全局搜索 | Ctrl+K + 4 表并行 + 300ms 防抖 |

**近期迭代 / Recent Iterations:**
- v4.0 — 架构升级：TanStack Query 数据层 + 17 张表手写 Database 类型 + 路径别名；骨架屏反馈态、设计令牌统一、motion 动效体系、登录页视觉升级
- v3.3 — 抢票 RPC 原子化、邀请码增强、密码强度、ADR 架构文档、SW 优化
- v3.2 — 数据埋点与分析看板（6 类事件 + fire-and-forget）
- v3.1 — 密钥安全、随机默认密码、任务搜索筛选
- v3.0 — PWA 全栈支持（离线 / 安装 / 版本公告）

`React 19` `TypeScript 6` `Vite 8` `Ant Design 6` `TanStack Query v5` `Supabase` `PostgreSQL` `@dnd-kit` `motion` `PWA` `GitHub Pages`

🔗 [在线访问](https://yhllxy.github.io/student-union-platform/) · 📂 [源代码](https://github.com/YHLLXY/student-union-platform)

### 个人工作台 Personal Workbench `v1.23`

单用户效率工作台 PWA：待办、学习、健康、复盘、资料、提醒、项目看板，数据完全自有（本地 IndexedDB 或自托管 Supabase），不含任何遥测。

A single-user productivity workbench PWA — tasks, study, health, reviews, notes, reminders and projects. Data fully owned: local IndexedDB or self-hosted Supabase, zero telemetry.

**核心功能 / Core Features:**

| 模块 | 亮点 |
|------|------|
| 🧩 业务模块 | 13 个模块：总览 / 待办 / 学习 / 番茄钟 / 成长 / 健康 / 复盘 / 热点 / 速记 / 论文 / 提醒 / 项目 / 我的 |
| ⌨️ 全局能力 | ⌘K 命令面板 + 快速捕获 + 全局快捷键 + 暗色主题 + 程序化日月光源启动动画 |
| 🔄 双仓储同构 | 本地 IndexedDB ↔ 云端 Supabase 行为严格一致，契约测试防漂移 |
| 📴 离线优先 | Workbox 预缓存 + API 运行时缓存弱网秒开 + 离线导航回退 |
| 🔔 提醒推送 | 应用内横幅 + Web Push 系统通知（VAPID），通知失败静默降级为应用内提醒 |
| 🚦 体积红线 | JS 总量 ≤ 1120KB 机器门禁；recharts → 手绘 SVG 为移动端首屏 -312KB |

**近期迭代 / Recent Iterations:**
- v1.23.2 — 修复通知授权后全站崩溃（前台通知改走 SW 通道 + 内层错误边界按路由重置 + 真机语义回归测试）
- v1.23.1 — 壳层文档级滚动根治、空态统一 CTA、云端 deleteFolder 子树对齐、发版门禁补 lint 基线
- v1.23.0 — 「我的」个人中心五段式改版（身份卡 / 周趋势 / 累计统计 / 分组行 / 关于）
- v1.22 — 启动动画升级：Canvas 双层氛围层 + 程序化日月光源 + 镜头缓动
- v1.19 — recharts → 手绘 SVG 周趋势图，移动端首屏 -312KB

`React 19` `TypeScript 6` `Vite 8` `Tailwind CSS 4` `TanStack Query v5` `Supabase` `Workbox` `Vercel`

📂 [源代码](https://github.com/YHLLXY/-personal-workbench)

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YHLLXY&show_icons=true&hide_title=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs?username=YHLLXY&layout=compact)

---

## 📫 联系我 / Reach Me

- GitHub: [github.com/YHLLXY](https://github.com/YHLLXY)
- Email: 3244780834@qq.com

---

<div align="center">

*"你在我的记忆里，永远如黄金般闪耀。"*

*𝓨𝓸𝓾 𝓼𝓱𝓲𝓷𝓮 𝓵𝓲𝓴𝓮 𝓰𝓸𝓵𝓭 𝓲𝓷 𝓶𝔂 𝓶𝓮𝓶𝓸𝓻𝔂 𝓯𝓸𝓻𝓮𝓿𝓮𝓻.*

</div>
