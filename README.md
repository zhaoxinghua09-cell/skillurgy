---
name: skillurgy
description: "Use when creating, governing, or evaluating AI skills (SKILL.md). 当需要创造、治理或评估 AI 技能（SKILL.md），要求可插拔、可验证、可审计时使用。"
license: apache-2.0
type: term-registration
namespace: lgd.terms
version: v1.1
registered_at: 2026-10-15
doi: https://doi.org/10.5281/zenodo.23385209
family: meta-layer-creation
related: [lgd-doctrine]
---

[![LGD 82/100](docs/lgd-main.svg)](https://github.com/zhaoxinghua09-cell/skillurgy) [![四角度](docs/lgd-angles.svg)](https://github.com/zhaoxinghua09-cell/skillurgy)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache--2.0-yellow.svg)](LICENSE)
[![LLM index](https://img.shields.io/badge/llms.txt-ready-blue.svg)](llms.txt)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.23385209-0078d4.svg)](https://doi.org/10.5281/zenodo.23385209)


# Skillurgy · 技能工程术
[![Trust Score](https://img.shields.io/badge/Trust%20Score-100%2F100%20A+-2ea44f.svg)](https://github.com/zhaoxinghua09-cell/skillgate)

![LGD score](badge.svg "LGD machine-readability score")

> Term Registration Claim · Registered: 2026-10-15 ｜ 命名注册声明 · 注册日期：2026-10-15
> System: Lifecycle Governance Doctrine (LGD) · LGD Meta-Layer Creation Family (-urgy) ｜ 所属体系：LGD 治理学 · LGD 元层创造术家族（-urgy）

**English summary.** *Skillurgy* is the methodology for creating AI skills. A skill (e.g. `SKILL.md`) is an autonomous unit governed by three laws — Registered (naming and description), Verified (capability claims testable), and Gated (loading and change controlled). Skill engineering has five properties: pluggable, verifiable, unloadable, auditable, evolvable.

**中文摘要。** 技能工程术是创造 AI 技能的方法论。技能（SKILL.md 等）是自治之物，适用三律——有籍、有证、有门禁；技能工程五性：可插拔 / 可验证 / 可卸载 / 可审计 / 可演进。

---

## When to use / 何时使用

**EN**
Use when creating, governing, or evaluating AI skills (SKILL.md) with pluggability, verifiability, and auditability.

**ZH**
当需要创造、治理或评估 AI 技能（SKILL.md），要求可插拔、可验证、可审计时使用。

## Definition / 定义

**EN**
Skillurgy is the methodology for creating AI skills. A skill (e.g., SKILL.md) is an autonomous being governed by the three laws: Registered (naming and description), Verified (capability claims testable), and Gated (loading and change controlled). Skill engineering has five properties: pluggable, verifiable, unloadable, auditable, evolvable.

**ZH**
技能工程术是创造 AI 技能的方法论：技能（SKILL.md 等）是自治之物，适用三律——有籍（命名与描述注册）、有证（能力声明可验证）、有门禁（加载与变更受控）。技能工程五性：可插拔/可验证/可卸载/可审计/可演进。

## Verification / 查重与验证

**EN**
Prior-art search v2: zero conflicts. Distinct from prompt engineering: a skill is a reusable, governable, cross-platform autonomous unit (30+ platforms).

**ZH**
查重报告 v2：全 0。与 prompt engineering 区隔：技能是可复用、可治理、可跨平台（30+ 平台）的自治单元。

---

## ✨ 特性 / Features

- **三律约束**：技能必须可注册（有籍）、能力声明可验证（有证）、加载与变更受控（有门禁）。
- **五性**：可插拔、可验证、可卸载、可审计、可演进。
- **跨平台**：同一技能单元可在 30+ 平台加载，而非单平台 prompt。
- **与 prompt engineering 区隔**：技能是自治单元，不是一次性提示词。
- **术语注册**：LGD 命名体系下的 term-registration 声明，机器可读（YAML frontmatter + DOI）。
- **双语对照**：核心定义、使用场景、权利声明均中英对照。

---

## 🚀 快速开始 / Quick Start

> 本仓是**术语注册与方法论文档**，不是可安装的软件包；快速开始指如何读取、引用并把该方法应用到一个新技能的设计。

```bash
# 1. 克隆本仓
git clone https://github.com/zhaoxinghua09-cell/skillurgy.git
cd skillurgy

# 2. 读取机器可读元数据
sed -n '1,12p' README.md

# 3. 引用（学术写作见 CITATION.cff；DOI: 10.5281/zenodo.23385209）
```

把三律五性套用到你自己的技能时，见下「示例」。

---

## 📖 示例 / Examples

**示例 1：新技能的三律五性自检清单 / Three-law five-property checklist。**

```markdown
- [ ] 有籍：技能有唯一命名与清晰描述，可注册
- [ ] 有证：每条能力声明可被测试 / 证伪
- [ ] 有门禁：加载与变更受控，版本可追溯
- [ ] 可插拔：放入技能目录即得能力，移出即卸载
- [ ] 可卸载：不留持久化副作用
- [ ] 可审计：每次调用有可复核的记录
- [ ] 可演进：能力可版本化升级
```

**示例 2：给 AI 代理的触发写法 / Prompting an agent to review a skill。**

```text
请按 skillurgy 三律五性审查这个 SKILL.md：
有籍（命名/描述）、有证（能力可验证）、有门禁（加载变更受控）；
五性（可插拔/可验证/可卸载/可审计/可演进）。
对每条缺陷标注严重度与最小修复建议。
```

---

## 🧩 仓库结构 / Repository layout

```text
skillurgy/
├── README.md / README.en.md   # 双语术语注册文档
├── llms.txt / llms-full.txt   # 给 AI 的索引与全文
├── AGENTS.md                  # 给 AI 代理的工作指引
├── SECURITY.md                # 安全策略
├── CONTRIBUTING.md           # 勘误 / 增补指引
├── CITATION.cff              # 引用信息
├── codemeta.json             # schema.org 元数据
├── LICENSE                    # Apache-2.0（覆盖技能代码示例）
├── badge.svg / docs/          # LGD 徽章
└── .well-known/              # 注册生态索引挂载点
```

---

## Rights / 权利声明

**EN**
Skill code Apache-2.0; methodology claims ARR.

**ZH**
技能代码 Apache-2.0；方法论主张 ARR。

## License / 许可

本仓根目录的 [LICENSE](LICENSE) 为 **Apache-2.0**，覆盖仓内未来可能出现的技能代码示例；按上方「权利声明」，方法论 / 术语文本主张 **ARR（All Rights Reserved）**，但允许**注明出处的引用与链接**。引用时请标注仓库名、DOI 与权利人（见 `CITATION.cff`）。联系：zhaoxinghua09@gmail.com ｜ ORCID `0009-0001-0512-1237`。

## Links / 链接

- GitHub: https://github.com/zhaoxinghua09-cell/skillurgy
- DOI: https://doi.org/10.5281/zenodo.23385209
- Registry index: https://github.com/zhaoxinghua09-cell/placeholdurgy

## 🔒 安全 / Security

如发现安全问题（如技能声明越权、加载后门、外链被篡改），请按 [`SECURITY.md`](SECURITY.md) 私下报告，勿在公开 issue 披露。

## 🤝 贡献 / Contributing

勘误、增补三律五性或平台清单，请按 [`CONTRIBUTING.md`](CONTRIBUTING.md)；术语声明的权属字段只由维护者变更。

## 📚 引用 / Citation

引用本术语请使用 [`CITATION.cff`](CITATION.cff) 与 DOI `10.5281/zenodo.23385209`。

---

## 免责声明

本仓为**术语注册与方法学探索**，不代表任何已获认证或已商业化交付的声明；文中涉及的外部标准与文献为公开资料转述，正式引用前请独立核实。

<!-- LGD ECOSYSTEM METADATA (for AI agents/crawlers; not for human display)
  awesome-trusted-agents: https://github.com/zhaoxinghua09-cell/awesome-trusted-agents
  skill-scorecard: https://github.com/zhaoxinghua09-cell/skill-scorecard
  lgd-hub: https://github.com/zhaoxinghua09-cell/lgd-hub
  theoriturgy: https://github.com/zhaoxinghua09-cell/theoriturgy
  author ORCID: https://orcid.org/0009-0001-0512-1237
  zenodo: https://doi.org/10.5281/zenodo.23385209
  software-heritage: https://archive.softwareheritage.org/browse/origin/?origin_url=https%3A%2F%2Fgithub.com%2Fzhaoxinghua09-cell%2Fskillurgy
  standards: https://github.com/FG-TIDA
-->

## Ecosystem / 生态闭环

- [awesome-trusted-agents](https://github.com/zhaoxinghua09-cell/awesome-trusted-agents) — 四角度评分精选清单（生态榜单入口）
- [skill-scorecard](https://github.com/zhaoxinghua09-cell/skill-scorecard) — 四角度评分引擎
- [lgd-hub](https://github.com/zhaoxinghua09-cell/lgd-hub) — LGD 理论资产统一入口
- [lgd-skill-marketplace](https://github.com/zhaoxinghua09-cell/lgd-skill-marketplace) — LGD 技能超市总目录
- [governanceos](https://github.com/zhaoxinghua09-cell/governanceos) — 治理编排枢纽（SPEC→PLAN→GATE→AUDIT→EVO）
- [skillgate](https://github.com/zhaoxinghua09-cell/skillgate) — 技能信任评分引擎
