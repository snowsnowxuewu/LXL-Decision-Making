# LXL Decision Making Skill

A Claude Code skill for structured decision-making, based on Li Xiaolai's book *The Truth About Thinking*（思考的真相）.

## What it does

When you're facing a tough decision — whether it's a career move, a big purchase, or any Yes/No or A-vs-B choice — this skill guides you through a rigorous 5-step framework instead of jumping straight to comparison.

The core insight: most bad decisions happen because people skip straight to comparing options without first clearly defining what they actually want.

## How to trigger it

Say **"run LXL decision skill"** in Claude Code and it will start the analysis. You can also trigger it with phrases like "help me decide", "should I…", or "我该不该…".

## The framework

**Phase 1 — Information Intake**
Claude collects everything it needs in one round: your real goal, the options you're considering, where the idea came from, your concerns, constraints, evaluation criteria, and gut feeling.

**Phase 2 — Full Analysis (5 steps)**

1. **Definition** — Clarify the real goal behind the decision. Most people describe an action ("should I quit?") when they should be defining a goal ("I want meaningful work with financial security").
2. **Classification** — Map all relevant factors across 6 categories: the person, the path to the goal, resources, external risks, opportunity costs, and time horizon.
3. **Causality** — Verify whether the option actually leads to the desired outcome. Is the assumed cause-effect relationship real, or just correlation?
4. **Weighted Comparison** — Score each option against your own criteria (including gut instinct as a weighted factor) to produce an objective comparison.
5. **Time Dimension** — Check whether the conclusion holds across short, medium, and long term. Set trigger conditions for when to revisit the decision.

## Files

| File | Description |
|------|-------------|
| `decision-framework/SKILL.md` | The skill instructions loaded by Claude Code |
| `decision-framework/李笑来决策模板.md` | The full decision template with examples (Chinese) |
| `decision-framework.skill` | Packaged skill file — double-click to install in Claude Code |

## Installation

Download `decision-framework.skill` and double-click it. Claude Code will prompt you to install it.

## Language

The skill adapts to your language — respond in Chinese or English and it will match.

---

# LXL 决策思考技能

一个基于李笑来《思考的真相》的 Claude Code 结构化决策技能。

## 这个技能做什么

当你面临一个艰难的决定——换工作、大额消费，或任何"要不要做"、"选A还是选B"的问题——这个技能会引导你用一套严谨的五步框架来思考，而不是直接跳到比较选项。

核心洞察：大多数糟糕的决定，是因为人们还没想清楚自己真正想要什么，就急着开始比较选项了。

## 如何触发

在 Claude Code 里说 **"run LXL decision skill"**，技能就会启动分析流程。也可以用"帮我做个决定"、"我该不该…"、"help me decide"等方式触发。

## 分析框架

**第一阶段 — 信息收集**
Claude 一次性收集所有需要的信息：你的真实目标、备选方案、想法的来源、顾虑、限制条件、评判标准，以及你的直觉倾向。

**第二阶段 — 完整分析（五步）**

1. **定义** — 澄清决定背后的真实目标。大多数人描述的是一个动作（"我要不要辞职？"），而真正需要定义的是目标（"我希望做有意义的事，同时保持财务安全"）。
2. **分类** — 将所有相关因素映射到六个类别：当事人本身、目标达成路径、资源条件、外部风险、机会成本、时间维度。
3. **因果** — 验证这个选项是否真的能带来想要的结果。假设中的因果关系是真实的，还是只是相关性？
4. **加权比较** — 用你自己的标准（包括直觉作为一项加权因素）给每个选项打分，得出客观的比较结论。
5. **时间维度** — 检验结论在短期、中期、长期是否一致，并设定重新评估的触发条件。

## 文件说明

| 文件 | 说明 |
|------|------|
| `decision-framework/SKILL.md` | Claude Code 加载的技能指令文件 |
| `decision-framework/李笑来决策模板.md` | 完整决策模板及示例（中文） |
| `decision-framework.skill` | 打包好的技能文件，双击即可安装到 Claude Code |

## 安装方法

下载 `decision-framework.skill`，双击打开，Claude Code 会提示你安装。

## 语言支持

技能会自动匹配你的语言——用中文回答就用中文分析，用英文就切换成英文。
