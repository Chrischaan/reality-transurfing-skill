# Reality Transurfing Skill

**Bring Vadim Zeland’s Reality Transurfing frameworks into conversations with your AI agent.**

English · [简体中文](README.zh-CN.md)

A Markdown-based agent skill for thinking through personal decisions, stuck goals, interpersonal conflict, and recurring patterns using the specific mental models of *Reality Transurfing: Steps I–V*.

It organizes the book’s ideas into a diagnostic guide, a glossary, practical techniques, and 19 chapter notes. The agent starts with your situation and loads the relevant material on demand.

## About the book and author

*Reality Transurfing* (RT) is Vadim Zeland’s system for thinking about choice, attention, intention, and the pursuit of goals. *Steps I–V* brings together the five steps of the series. Its distinctive vocabulary includes **pendulums**, **excess potential**, **inner and outer intention**, **target slides**, and **goals and doors**.

In Zeland’s model, excessive importance creates resistance, collective emotional dynamics pull people away from their own goals, and a change in attention and intention can open different paths through life. This skill uses those ideas as prompts for reflection and practical decisions. The book’s metaphysical explanations are the author’s speculative model, not established scientific findings.

Vadim Zeland is the Russian author associated with Reality Transurfing. In the autobiographical account on his official website, he describes earlier work in quantum physics research and computer technology, and explains his preference for keeping his personal life private. That account is his own description of his background, not a scientific validation of Transurfing.

Read more: [author’s official website](https://zelands.com/) · [official Steps I–V overview and author introduction](https://zelands.com/reality-transurfing-steps-iv/).

## What you can use it for

- **A goal feels too important:** examine excess potential and reduce the pressure around the outcome.
- **A conflict keeps consuming your attention:** identify the pendulum and consider how to disengage.
- **You want something but feel only obligation:** distinguish an innermost goal from a foreign goal.
- **You know the goal but keep forcing the path:** explore goals and doors, inner and outer intention.
- **You want a concrete visualization practice:** work with a target slide alongside real-world action.

## Install

The repository root is the skill folder: `SKILL.md` and its supporting files must stay together. No book PDF, scripts, or API keys are required by this skill; you need an AI agent that supports skills or can read these Markdown files.

Download this repository from GitHub using **Code → Download ZIP**, extract it, and rename the extracted folder to `reality-transurfing`.

For agents that discover skills in `~/.agents/skills/`, place the complete folder there:

```text
~/.agents/skills/reality-transurfing/
├── SKILL.md
├── cheatsheet.md
├── glossary.md
├── patterns.md
└── chapters/
```

For Claude Code, place the same folder in `~/.claude/skills/reality-transurfing/`. If your agent uses another skill directory, use that host’s documented location. Restart or refresh the agent if needed.

If you already have a skill with this name, compare or back it up before replacing it.

## Usage

Explicitly ask your agent to use the skill:

```text
Use the reality-transurfing skill. I keep treating this promotion as my
only chance to prove my worth. Help me diagnose the mechanism and choose
one practical next step.
```

Other examples:

```text
Apply Reality Transurfing to this recurring conflict with my colleague.
Which pendulum might I be feeding, and how could I disengage?
```

```text
Help me distinguish a foreign goal from my own goal. I want to start a
business, but I am unsure whether I want the work or the status.
```

```text
Help me create a target slide for finishing my creative project,
then pair it with a small action I can take today.
```

The skill instructs the agent to diagnose first, name the relevant mechanism, consult only the necessary supporting files, and connect suggestions to chapter references. You can ask for those references to check the reasoning. The reference material is in English; you can request an answer in Chinese or another language.

## How the files fit together

| File | Purpose |
| --- | --- |
| [SKILL.md](SKILL.md) | Agent instructions, core frameworks, chapter and topic indexes |
| [cheatsheet.md](cheatsheet.md) | Symptom-to-mechanism table and decision rules |
| [glossary.md](glossary.md) | Term definitions with chapter pointers |
| [patterns.md](patterns.md) | Step-by-step techniques grouped by purpose |
| [chapters/](chapters/) | 19 chapter notes, from The Alternatives Model to The Gatekeeper to Eternity |

For example, a question about importance leads to the cheatsheet, the relevant terms, and Chapter IV; a question about goals and doors leads to Chapter X. There is no need to load every chapter for each conversation.

## Scope

Use this as a reflective framework alongside ordinary action. It does not guarantee outcomes or establish claims about manifestation, energy fields, or healing. It should not be used to control or harm other people, or replace medical, mental-health, financial, or legal support.

## Contributing

Corrections to terminology, chapter references, explanations, and translations are welcome. Keep changes grounded in the named source, distinguish Zeland’s claims from your interpretation, and keep both READMEs in sync. Please do not add book scans, full chapters, or long verbatim passages.

## Credits and license

Source of the frameworks: Vadim Zeland, *Reality Transurfing: Steps I–V*. The original book and associated marks remain with their respective rights holders. This is an independent community project, with no claimed affiliation with or endorsement by the author or publisher.

The README layout and the idea of making book frameworks available on demand were inspired by [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill). That acknowledgment does not imply this skill was generated by that project.

[MIT](LICENSE) applies to the repository contributors’ original instructions, documentation, and organization, to the extent they own those rights. It grants no rights to the source book, third-party quotations, or trademarks. Attribution does not itself grant permission to redistribute protected source material.
