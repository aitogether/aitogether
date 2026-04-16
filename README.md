# 👋 Hi, I'm AITogether

<p align="center">
  <img alt="GitHub stars" src="https://img.shields.io/github/stars/aitogether?style=flat-square&color=gold" />
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/aitogether?style=flat-square&color=brightgreen" />
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/aitogether/aitogether?style=flat-square&color=blue" />
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/aitogether/aitogether?style=flat-square&color=orange" />
</p>


用 AI 和自动化，帮一人公司少写命令、多赚闲钱。
现在主要在做两件事：异地子女的父母周报，和一人公司的多 Agent 内阁系统。

🧓👶 **正在进行中**：在外打拼的子女，很难每天打电话回家——但又总惦记爸妈身体怎样、药有没有忘吃、今天走了多少步、心情好不好。我们正在做一个微信小程序，让子女每周收到一封父母状态简报，爸妈那边只需要「点一下」就能完成反馈。不用天天追着问，也不用时刻焦虑。

## 📸 Screenshots — 父母周报

> 色板 v1.1 · BrandTeal #20A080 · Android 模拟器截图（2026-03-31）

| 首页 | 周报概览 | 步数趋势 | 多周趋势 |
| --- | --- | --- | --- |
| ![](https://raw.githubusercontent.com/aitogether/parents-weekly-briefing/main/ui-prototype/screenshots/01-home.png) | ![](https://raw.githubusercontent.com/aitogether/parents-weekly-briefing/main/ui-prototype/screenshots/02-report.png) | ![](https://raw.githubusercontent.com/aitogether/parents-weekly-briefing/main/ui-prototype/screenshots/03-step-chart.png) | ![](https://raw.githubusercontent.com/aitogether/parents-weekly-briefing/main/ui-prototype/screenshots/04-multi-week-trend.png) |

| 焦虑自查 | 妈妈用药 | 爸爸用药 | 用药计划 |
| --- | --- | --- | --- |
| ![](https://raw.githubusercontent.com/aitogether/parents-weekly-briefing/main/ui-prototype/screenshots/05-anxiety-survey.png) | ![](https://raw.githubusercontent.com/aitogether/parents-weekly-briefing/main/ui-prototype/screenshots/06-medication-mom.png) | ![](https://raw.githubusercontent.com/aitogether/parents-weekly-briefing/main/ui-prototype/screenshots/07-medication-dad.png) | ![](https://raw.githubusercontent.com/aitogether/parents-weekly-briefing/main/ui-prototype/screenshots/08-medication-plan.png) |

> 📱 更多详情：[parents-weekly-briefing](https://github.com/aitogether/parents-weekly-briefing) · [Demo App](https://github.com/aitogether/parents-weekly-briefing-demo-app) · [内阁系统](https://github.com/aitogether/imperial-cabinet-openclaw)

## 👑 最近在搞什么

当前 2026 Q1–Q2 的主线是把 Parents Weekly Briefing 跑进真实家庭，OpenClaw 内阁作为基础设施持续迭代。

- 🧓👶 **Parents Weekly Briefing**（父母周报）
  给异地子女的一周一次父母状态简报：只看步数和用药确认，生成一封「要不要回家看看」的周报，还带一条给爸妈的「回声」小问候。
  > 目标：微信小程序 MVP + Android Demo 已完成，当前进度：接入真实微信登录与后端联调，准备上线内测，跑进首批真实家庭。

  **👉 如果你是异地子女，想参加内测：**
  [→ 查看内测报名说明](https://github.com/aitogether/parents-weekly-briefing/blob/main/README.md#%F0%9F%A7%B9-%E6%AD%A3%E5%9C%A8%E5%8B%9F%E9%9B%86-5-10-%E4%B8%AA%E5%AE%B6%E5%BA%AD%E8%BF%9B%E8%A1%8C%E5%86%85%E6%B5%8B)
- 🏛️ **Imperial Cabinet for OpenClaw**
  用「内阁都察制 · 御前内阁系统」把多 Agent 当成明清官僚体系来治理，专门给一人公司用 OpenClaw 接管日常工作流。
  > 目标：v2 Alpha — 七阶段流水线 + 11 个 Skill 已就绪，正在补齐文档和运维脚本，验证端到端工作流。

  **👉 如果你是一人公司，想用 OpenClaw 接管日常工作：**
  [→ 查看 OpenClaw 上手示例](https://github.com/aitogether/imperial-cabinet-openclaw/blob/main/README.md#10-%E5%88%86%E9%92%9F%E4%B8%8A%E6%89%8B%E7%A4%BA%E4%BE%8B)
- 🧪 小型自动化收入流实验
  用现成开源项目 + 云服务，搭一些「能自己滚动维护、哪怕小但稳定」的收入小流水线。

## 🛠 技术栈 & 兴趣

- AI & Agents：OpenClaw、多模型编排、多 Agent 治理
- Dev：Python / TypeScript / Shell，偏向实用脚本和自动化
- Infra：macOS、本地 LLM + 云端 API 混合，小而美的部署方案
- 话题：一人公司、自动化工作流、怎么用 AI 少加班

## 🏛 代表项目

- [parents-weekly-briefing](https://github.com/aitogether/parents-weekly-briefing)
  > WeChat mini program for adult children to get a weekly briefing on aging parents — step counts, medication adherence, mood check-ins, and a gentle one-tap "echo" feedback for parents.

- [parents-weekly-briefing-demo-app](https://github.com/aitogether/parents-weekly-briefing-demo-app)
  > Android demo app showcasing the Parents Weekly Briefing UI prototype.

- [imperial-cabinet-openclaw](https://github.com/aitogether/imperial-cabinet-openclaw)
  > 内阁都察制 · 一人公司多 Agent 治理框架（基于 OpenClaw）。Multi-agent orchestration framework for solo founders.

👉 **想看实际长什么样？** 戳 screenshots & demo：
- 🧓👶 父母周报：[parents-weekly-briefing README 顶部](https://github.com/aitogether/parents-weekly-briefing#-screenshots)
- 📱 Android Demo App：[parents-weekly-briefing-demo-app README 顶部](https://github.com/aitogether/parents-weekly-briefing-demo-app#-screenshots)

（后续会把其他实用脚本/工具也逐步开源出来）

## 📫 怎么找到我

- 最稳妥的方式：在对应仓库提 Issue / 开 Discussion
- 如果你在用 OpenClaw / 多 Agent，也欢迎直接提「真实工作流」需求，一起打磨一人公司的御前内阁系统

---

### 🌍 About This Profile (English)

_This profile is mostly in Chinese because my projects are primarily aimed at Chinese-speaking solo founders and families._

**Parents Weekly Briefing** is a WeChat mini program built for **adult children who live far from their aging parents**. Many of us can't call home every day, but we constantly worry — are they eating well? Did they take their medication? How many steps did they walk today? This project sends a simple weekly report to the child, while the parent only needs to tap once to give feedback. No complicated setup, no guilt — just a quiet, reliable connection across the distance.

If you're building something for the "sandwich generation" — people juggling careers and aging parents — I'd love to connect. Open an issue or start a discussion in any repo.
