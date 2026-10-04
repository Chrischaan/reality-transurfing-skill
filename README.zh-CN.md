# Reality Transurfing Skill

**让 AI agent 运用 Vadim Zeland 的 Reality Transurfing 框架，与你一起思考真实生活中的问题。**

[English](README.md) · 简体中文

这是一个基于 Markdown 的 agent skill，将《Reality Transurfing: Steps I–V》的特定思维模型用于个人决策、卡住的目标、人际冲突，以及反复出现的行为模式。

它把书中的思想整理成诊断指南、术语表、实践方法和 19 章笔记。Agent 从你的具体处境出发，按需读取相关内容。

## 关于这本书与作者

*Reality Transurfing*（简称 RT，可理解为“现实穿梭”）是 Vadim Zeland 围绕选择、注意力、意图与目标提出的一套体系。*Steps I–V* 汇集了这一系列的五个阶段。书中最有辨识度的概念包括：**摆锤（pendulums）**、**过剩潜能（excess potential）**、**内在与外在意图（inner / outer intention）**、**目标幻灯片（target slides）**，以及**目标与门（goals and doors）**。

在 Zeland 的模型中，过度赋予结果重要性会产生阻力，集体情绪会把人拉离自己的目标，而调整注意力与意图可能带来不同的人生路径。这个 skill 将这些思想用于反思与实际决策。书中的形而上学解释属于作者的推测性模型，不应当被视为已获科学证实的结论。

Vadim Zeland（瓦迪姆·泽兰）是与 Reality Transurfing 体系相关的俄罗斯作家。他在官方网站的自述中提到，自己曾从事量子物理研究和计算机技术工作，也表达了保持私人生活低调的意愿。这些是作者对自身背景的描述，并不构成 Transurfing 理论的科学验证。

进一步了解：[作者官方网站](https://zelands.com/) · [Steps I–V 官方介绍与作者自述](https://zelands.com/reality-transurfing-steps-iv/)。

## 可以用它思考什么

- **一个目标变得“太重要”：** 检查过剩潜能，降低围绕结果的心理压力。
- **一场冲突不断占据注意力：** 识别摆锤，思考如何退出情绪循环。
- **想要一个目标，却只感到义务：** 区分自己的目标与外来目标。
- **目标明确，却一直强迫某条路径：** 探索目标与门、内在与外在意图。
- **想建立具体的可视化练习：** 将目标幻灯片与现实行动结合起来。

## 安装

仓库根目录就是 skill 目录：`SKILL.md` 必须与辅助文件放在一起。这个 skill 本身不需要原书 PDF、脚本或 API key；你需要一个支持 skills 或能够读取这些 Markdown 文件的 AI agent。

在 GitHub 点击 **Code → Download ZIP** 下载仓库，解压后将文件夹重命名为 `reality-transurfing`。

对于从 `~/.agents/skills/` 发现技能的 agent，将完整文件夹放入该目录：

```text
~/.agents/skills/reality-transurfing/
├── SKILL.md
├── cheatsheet.md
├── glossary.md
├── patterns.md
└── chapters/
```

Claude Code 用户可以将同一文件夹放入 `~/.claude/skills/reality-transurfing/`。其他 agent 请使用其文档指定的 skill 目录。安装后如未识别，可重启或刷新 agent。

如果已经有同名 skill，请先比较内容或备份，再决定是否替换。

## 使用示例

直接告诉 agent 使用这个 skill：

```text
请使用 reality-transurfing skill。我一直把这次晋升当成证明自己价值的
唯一机会。请先诊断这里的机制，再帮我选择一个可执行的下一步。
```

也可以这样问：

```text
请用 Reality Transurfing 分析我与同事反复发生的冲突。
我可能在给哪个摆锤提供能量？怎样退出这个循环？
```

```text
帮我区分外来目标和自己的目标。我想创业，但不确定自己想要的是
实际的工作，还是创业者这个身份带来的认可。
```

```text
帮我为完成一个创作项目设计目标幻灯片，再配上一个今天能做的小行动。
```

Skill 会引导 agent 先诊断，再指出相关机制，只读取必要的辅助文件，并把建议与具体章节关联。你可以要求它给出章节依据，以便核对推理。参考资料为英文，但可以要求 agent 用中文或其他语言回答。

## 文件如何配合

| 文件 | 用途 |
| --- | --- |
| [SKILL.md](SKILL.md) | Agent 指令、核心框架、章节与主题索引 |
| [cheatsheet.md](cheatsheet.md) | 症状与机制对照表、决策规则 |
| [glossary.md](glossary.md) | 术语定义与章节指引 |
| [patterns.md](patterns.md) | 按用途整理的分步实践方法 |
| [chapters/](chapters/) | 从 The Alternatives Model 到 The Gatekeeper to Eternity 的 19 章笔记 |

例如，关于“重要性”的问题会引向速查表、相关术语与第四章；关于“目标与门”的问题会引向第十章。每次对话无需加载所有章节。

## 使用范围

把它作为与现实行动配合的反思框架。它不保证结果，也不证明显化、能量场或疗愈方面的主张。不要用它控制或伤害他人，也不要用它替代医疗、心理健康、财务或法律支持。

## 参与改进

欢迎修正术语、章节引用、解释与翻译。请让改动有明确的原书依据，区分 Zeland 的观点与自己的解释，并同步更新中英文 README。请不要加入原书扫描件、完整章节或大段逐字摘录。

## 致谢与许可

框架来源：Vadim Zeland，*Reality Transurfing: Steps I–V*。原书及相关标识的权利归各自权利人所有。本项目为独立社区项目，不声称与作者或出版社有关联，也不声称获得其背书。

README 的组织方式，以及让 agent 按需调用书中框架的思路，参考了 [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill)。此处致谢不代表本 skill 已确认由该项目生成。

[MIT 许可证](LICENSE) 适用于仓库贡献者拥有权利的原创指令、文档与组织内容，不授予原书、第三方引文或商标的任何权利。注明来源本身不等于获得受保护原始材料的再分发许可。
