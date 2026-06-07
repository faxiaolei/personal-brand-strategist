# Personal Brand Strategist

`Personal Brand Strategist` is a reusable Codex Skill for helping someone clarify their personal brand, positioning, target audience, differentiation, content ecosystem, and external messaging system.

It is designed to work across industries and roles. It does not assume any specific profession, platform, or creator type.

## What this skill does

This skill helps turn scattered experiences, strengths, goals, channels, and public-facing assets into a usable brand system.

It is especially useful when someone:

- has done many things but cannot clearly explain who they are
- has multiple channels or identities that feel fragmented
- sounds overpackaged, vague, or inconsistent
- needs a brand framework before writing content, building a site, or designing assets
- wants reusable outputs such as a brand framework, content ecosystem plan, or external expression handbook

## Repository structure

```text
personal-brand-strategist-github/
├── README.md
├── skill-en/
│   ├── SKILL.md
│   ├── agents/
│   │   └── openai.yaml
│   └── references/
│       └── framework.md
└── docs-zh/
    ├── 个人品牌策略师技能说明_中文版_V1.md
    └── 个人品牌策略框架参考_中文版_V1.md
```

## English skill files

The actual reusable Skill lives in:

- `skill-en/SKILL.md`
- `skill-en/agents/openai.yaml`
- `skill-en/references/framework.md`

These are the files that matter if someone wants to install or reuse the Skill in Codex.

## Chinese documentation

The Chinese documents in `docs-zh/` are supporting explanations for human readers. They explain:

- what the skill is
- when to use it
- what kind of outputs it helps produce
- the diagnostic framework behind the skill

They are not required for the Skill to run, but they are useful if you want to share the method with Chinese-speaking users.

## Suggested GitHub publishing approach

If you want to publish this repository:

1. Keep `skill-en/` as the canonical skill implementation
2. Keep `docs-zh/` as the Chinese explanation set
3. Use this `README.md` as the root introduction

If you later want to make the project more polished, you can add:

- screenshots
- usage examples
- a Chinese README
- installation instructions for Codex users

## Notes

- The skill is intentionally generic and not tied to any one person's brand
- It is meant to help clarify strategy before downstream execution
- It distinguishes current truth, current value, and future direction to avoid overclaiming
