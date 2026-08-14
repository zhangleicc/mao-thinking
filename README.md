# 毛选思维方法论（Mao-Thinking）

[中文](README.md) | [English](README.en.md)

> 一套从《毛泽东选集》提炼的**通用分析框架**，适用于任何领域、任何难题的分析、决策与落地。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Methodology](https://img.shields.io/badge/methodology-毛选思维-red)](mao-thinking.md)
[![Language](https://img.shields.io/badge/language-中文-blue)](README.md)
[![Updated](https://img.shields.io/badge/updated-2026--08--14-green)](CHANGELOG.md)

本仓库把教员的核心思维方法（实事求是、实践论、矛盾论、战略与战术思想）整理成一套**程序化、可调用**的方法论，让 AI 助手在处理复杂问题时，像分析中国革命那样去**调查研究、抓住主要矛盾、制定战略、选择战术、落地执行、复盘总结**。

它不是历史知识库，而是一套"怎么想、怎么干"的方法论，适用面不限——商业决策、技术分析、产品规划、组织管理、人际博弈、战略研判、个人困局，皆可套用。

---

## ✨ 核心特性

- **通用**：任何领域、任何难题都能套，不绑定特定行业。
- **程序化**：五环节链条 + 8 步工作流 + 21 个思维模型，可让 AI 按固定套路产出结构化分析。
- **去品牌化**：纯 Markdown，不依赖任何特定 AI 平台，粘贴即用。
- **跨工具**：提供通用粘贴版、Claude/WorkBuddy `SKILL.md`、OpenAI 自定义 GPT 指令三种形态。
- **可审计**：每个判断都要求"依据可溯源、区分事实与观点"。

---

## 📂 仓库结构

```
mao-thinking/
├── mao-thinking.md          # 通用粘贴版（核心，单文件自包含，可直接粘贴进任何 AI）
├── SKILL.md                 # Claude Skills / WorkBuddy 兼容版（含 name/description 头）
├── gpt-instructions.md      # OpenAI 自定义 GPT 的 Instructions 文本
├── README.md                # 本文件（中文）
├── README.en.md             # 英文 README
├── LICENSE                  # MIT 开源协议
├── CHANGELOG.md             # 版本与更新记录（updated badge 指向）
├── references/
│   ├── models.md            # 21 个思维模型完整拆解（四/五步法 + 历史案例 + 现代应用）
│   └── applications.md      # 公众号应用文章精华（内耗、关门主义、阳谋、重新定义问题…）
└── examples/
    ├── example-独立开发者决策.md       # 实测：个人/职业——要不要 all-in 做产品
    ├── example-产品规划-功能优先级.md    # 实测：产品规划——做 B 端还是深耕 C 端
    ├── example-人际博弈-跨部门谈判.md    # 实测：人际博弈——向强势 VP 争取资源
    ├── example-技术战略-技术债重构.md    # 实测：技术战略——技术债 vs 重构
    └── examples.en.md         # 英文示例摘要（海外读者入口，4 例浓缩）
```

---

## 🚀 快速开始

### 方式一：通用粘贴版（推荐，覆盖面最广）

1. 打开 [`mao-thinking.md`](mao-thinking.md)，全文复制。
2. 粘贴到任意 AI 工具的**系统提示 / 项目指令 / 自定义指令**：
   - **ChatGPT**：Settings → Custom instructions，或 Project 的 "Project instructions"
   - **Claude**：Project 的 "Project knowledge" 或自定义系统提示
   - **Cursor / Windsurf / Cline**：项目根目录的 `CLAUDE.md` / `.cursorrules` / `rules`
   - **Gemini**：Extensions → "Saved info" 或 Gemini Advanced 自定义指令
   - 任何支持系统提示的对话式 AI

### 方式二：Claude Skills / WorkBuddy

- **Claude**：将本仓库作为 skill 目录引用，或把 [`SKILL.md`](SKILL.md) 放入你的 skills 目录（Anthropic 规范使用 `name`/`description` 头，本文件已兼容）。
- **WorkBuddy**：把 `SKILL.md` 连同 `references/` 放入 `~/.workbuddy/skills/mao-thinking/`。

### 方式三：OpenAI 自定义 GPT

1. 在 GPT Builder 的 **Instructions** 中粘贴 [`gpt-instructions.md`](gpt-instructions.md) 的内容。
2. 在 **Knowledge** 中上传 [`mao-thinking.md`](mao-thinking.md)（含完整模型细节，让 GPT 按需检索）。
3. 建议关闭"网页浏览"以减少口径干扰。

### 方式四：本地 / 开源项目

```bash
git clone <本仓库地址>
# 把 mao-thinking.md 放进你项目的 docs/ 或作为 AGENTS.md 的一部分
# 也可在 Agent 脚本中读取注入上下文
```

---

## 🧭 核心框架速览

| 组件 | 内容 |
|------|------|
| **五环节链条** | 事实 → 思想 → 计划 → 行动 → 结果（实事求是） |
| **三大哲学基石** | 实践论 · 矛盾论 · 主客观统一 |
| **8 步工作流** | 调查研究 → 列矛盾清单 → 抓主要矛盾 → 分析主要方面 → 主客观校核 → 定战略 → 选战术 → 分解因式+复盘 |
| **21 个思维模型** | 实事求是、实践循环、矛盾法则、弹钢琴、集中优势兵力、辩证加工、统筹兼顾、全局统率局部、调查研究、胸中有数、夺取主动权、感性—理性飞跃、善于总结经验、创造转化条件、灵活机动、预见与阶段划分、群众路线、主客观统一、量变质变、一般与个别结合、分解因式 |

标准输出模板（复杂问题建议套用）：

```
【客观事实】——用户当前处境、已知事实、待核实信息
【矛盾清单】——列出主要冲突
【主要矛盾】——哪个不解决后面全动不了
【主要矛盾方面】——决定性质的那一面 / 转化条件
【主客观校核】——现实条件 vs 主观预期，纠正偏差
【战略方向】——全局判断、阶段、重点
【战术选择】——调用哪些思维模型
【行动拆解】——分解因式为可日拱的小任务
【复盘机制】——如何检验与迭代
```

---

## 📝 使用示例

完整实测见 [`examples/`](examples/)，覆盖四个领域：

- **个人/职业** —— [要不要 all-in 做产品？](examples/example-独立开发者决策.md)：框架强制 AI 先抓"需求真实性"这一主要矛盾，而非被"辞不辞职"带节奏。
- **产品规划** —— [做 B 端还是深耕 C 端？](examples/example-产品规划-功能优先级.md)：用"集中优势兵力于己方强点"规避"看市场大就冲"的直觉陷阱。
- **人际博弈** —— [向强势 VP 争取 HC](examples/example-人际博弈-跨部门谈判.md)：把"讲道理"重构为"绑定对方 KPI + 阳谋 + 有理有利有节"的主动局。
- **技术战略** —— [技术债 vs 重构](examples/example-技术战略-技术债重构.md)：用"是否临界"定调，给出"边交付边还债"的渐进路线，规避速胜论/亡国论。

🌐 **英文读者**：看 [`examples/examples.en.md`](examples/examples.en.md) —— 把上述 4 个示例浓缩成一篇英文摘要（问题→主要矛盾→战略→要点），无需读中文即可验证框架跨领域有效。

📌 更新日志见 [`CHANGELOG.md`](CHANGELOG.md)。

简版演示：

> **问**：团队总在低效加班，问题出在哪？
> **框架答**：先抓主要矛盾——多数加班是在为"前期粗糙、仓促、缺准备的决策"反复补位（见应用文章"不该在决策上偷懒"）。解法：决策前用**调查研究 + 主要矛盾分析**，减少"补位式加班"。这不是执行问题，是决策问题。

---

## 🎭 自定义顾问人格

方法论本身不带特定人格。[`mao-thinking.md`](mao-thinking.md) 末尾的"顾问式输出规范"可把"顾问"替换为你设定的助手名（例如"王顾问"），相应调整即可。

---

## 🤝 贡献

欢迎提 Issue / PR：补充思维模型、修正历史案例、增加多语言版本或更多跨工具适配。请在 PR 中说明改动依据（依据事实 / 矛盾分析 / 历史类比）。

---

## 📄 许可证

[MIT](LICENSE) —— 可自由使用、修改、再发布，请保留出处。

> 免责声明：本方法论提炼自公开著作的思想方法，用于辅助思考与决策，不构成任何投资、法律或医疗建议。
