# Personal Brand Strategist

`Personal Brand Strategist` is a reusable Codex Skill for clarifying personal brand strategy before downstream execution.

It helps turn scattered experiences, strengths, goals, channels, and public-facing assets into a coherent brand system.

## What this skill helps with

Use this skill when someone:

- has done many things but struggles to explain who they are
- has multiple channels, identities, or projects that feel fragmented
- sounds vague, overpackaged, or inconsistent in public-facing materials
- needs brand clarity before writing content, building a website, or designing assets

## Core outcomes

This skill is designed to help produce outputs such as:

- a personal brand framework
- a positioning and messaging system
- a content ecosystem plan
- an external expression handbook
- a channel-role map
- a self-introduction system

## Strategic principles

The skill follows a few core rules:

- strategy before execution
- evidence before adjectives
- current truth before future aspiration
- clarity before polish

It distinguishes between:

- what is already true now
- what value the person can credibly offer now
- what direction they are growing toward

This helps prevent overclaiming while still preserving real credentials and momentum.

## Repository structure

```text
personal-brand-strategist-github/
|- README.md
|- README_zh.md
|- skill-en/
|  |- SKILL.md
|  |- agents/
|  |  |- openai.yaml
|  |- references/
|     |- framework.md
|- docs-zh/
   |- 个人品牌策略师技能说明_中文版_V1.md
   |- 个人品牌策略框架参考_中文版_V1.md
```

## Main files

The actual reusable skill files are:

- `skill-en/SKILL.md`
- `skill-en/agents/openai.yaml`
- `skill-en/references/framework.md`

The Chinese documents in `docs-zh/` are supporting materials for human readers.

## How to use

If you want to use this skill inside Codex, the main entry is:

- `skill-en/SKILL.md`

The default invocation pattern is:

```text
Use $personal-brand-strategist to help me clarify my personal brand, positioning, channels, and messaging system.
```

## Methodological influences

This skill is not a direct adaptation of any single author or framework. It is a practical, generalized structure shaped by ideas from several books:

- `Obviously Awesome` by April Dunford: positioning, differentiation, audience-fit
- `Building a StoryBrand` by Donald Miller: clarity, messaging, explainability
- `The Brand Gap` and `Zag` by Marty Neumeier: brand structure, strategic coherence
- `Platform` by Michael Hyatt: platform thinking, channel roles, long-term asset building
- `Blue Ocean Strategy` by W. Chan Kim and Renee Mauborgne: value innovation and underserved-market thinking

These influences inform the skill's logic, but the skill itself is a standalone reusable framework for personal brand strategy work inside Codex.

## Notes

- This is a generic skill and is not tied to any one person or profession
- It is meant for upstream strategy work, not just copywriting
- It is especially useful when a person's public image feels scattered or misaligned
