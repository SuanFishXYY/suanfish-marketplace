# 🐟 Suanfish Marketplace

> *算鱼工作室 · Claude Code / Codex / Copilot CLI 的 plugin marketplace*

哲学驱动的多智能体设计语言体系。99% 的 AI 永远回答 Yes，这里的 AI 有 18 条硬规则可以拒单。

[![marketplace](https://img.shields.io/badge/Claude%20Code-marketplace-blueviolet)](https://docs.claude.com/en/docs/claude-code/plugin-marketplaces)
[![plugins](https://img.shields.io/badge/plugins-1-green)](.claude-plugin/marketplace.json)
[![license](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## 📦 当前收录

| Plugin | 版本 | 简介 |
| --- | :---: | --- |
| [`suanfish-design-system`](https://github.com/SuanFishXYY/suanfish-design-system) | **v3.0.0** | 36 位 agent · 8 tier · 7 path · R1-R18 REJECT · 三层哲学（价值 + 辩证 + 发展规律）+ 8 时代历史定位 |

---

## 🚀 安装方式

### Claude Code

```bash
# 添加本 marketplace
/plugin marketplace add SuanFishXYY/suanfish-marketplace

# 安装算鱼设计系统
/plugin install suanfish-design-system@suanfish-marketplace
```

### 手动 clone（任何 CLI）

```bash
git clone https://github.com/SuanFishXYY/suanfish-design-system.git ~/.claude/skills/suanfish-design-system
```

---

## 🌗 v3.0 三层哲学体系（What's New）

| Layer | 文件 | 回答的问题 |
| --- | --- | --- |
| **Layer 1 · 价值** | `references/17-philosophy.md` | 该选哪边？ |
| **Layer 2 · 辩证** ✨ | `references/24-philosophy-dialectics.md` | 为什么有两边？ |
| **Layer 3 · 发展规律** ✨ | `references/25-philosophy-laws.md` | 矛盾如何随时间漂移？ |
| **Layer 0.5 · 历史定位** ✨ | `references/26-historical-positioning.md` | 我来自哪个时代？要去哪个时代？ |

**任何 BRIEF 入场顺序**：
```
BRIEF → 🪙 dialectician → 📜 historian → 🔭 futurist → 🧭 moment-strategist → A-G 路径
```

---

## 🛑 R1-R18 REJECT 规则

| 规则区段 | 触发者 | 哲学根因 |
| --- | --- | --- |
| **R1-R6** | moment-strategist | 价值层 · 6 条硬触发 |
| **R7-R12** | tier-2 主理 agent | 路径专属规则 |
| **R13** ✨v3.0 | futurist | L1 复杂度螺旋律 |
| **R14** ✨v3.0 | historian | L2 抽象交替律 |
| **R15** ✨v3.0 | futurist | L3 控制权下移律 |
| **R16** ✨v3.0 | futurist | L4 反馈循环缩短律 |
| **R17** ✨v3.0 | futurist | L5 模态融合律 |
| **R18** ✨v3.0 | dialectician | 矛盾两端都站（D 任意一对没选倾向） |

---

## 🎯 适用场景

- 🎬 仪式感模式（首次登录 / 版本更新 / 新功能发布）
- 🏛 稳态模式（日常工作 / 多步流程 / 表格 / 图谱）
- 💬 聊天模式（AI 对话 / prompt 编辑器）
- 🔔 通知模式（toast / banner / push）
- 📱 移动模式（H5 / 小程序 / App）
- 🧩 嵌入模式（卡片 / widget / iframe）
- 🤖 AI-native 模式（流式 / 工具调用 / 思维链 / 引用 / artifact）

---

## 📮 贡献 / 提交新 plugin

发 PR 到本仓的 `.claude-plugin/marketplace.json`，按 [Claude Code plugin marketplace schema](https://docs.claude.com/en/docs/claude-code/plugin-marketplaces) 填写。

---

## 📜 License

MIT · 算鱼工作室 © 2026

---

> *"工具是把柄，哲学是骨头。没有骨头的工具，迟早被流派、被趋势、被甲方意志拆得稀碎。"* — v3.0 立项语
