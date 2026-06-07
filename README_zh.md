# 个人品牌策略师

`Personal Brand Strategist` 是一个可复用的 Codex Skill，用来先梳理个人品牌策略，再进入后续内容、网站、视觉或对外表达的执行。

它的核心作用，是把一个人零散的经历、能力、目标、渠道和公开形象，整理成一套清晰、可复用的品牌系统。

## 适用场景

当一个人出现下面这些情况时，这个 Skill 会很有用：

- 做过很多事情，但很难清楚表达自己是谁
- 有多个账号、多个身份、多个项目，但整体比较分散
- 对外表达容易显得空泛、失真、包装感过强
- 还没有理清品牌逻辑，就已经开始写内容、做网站、做视觉

## 可以帮助产出的成果

这个 Skill 适合帮助产出例如：

- 个人品牌母框架
- 定位与表达系统
- 内容生态分工框架
- 对外表达手册
- 平台角色地图
- 自我介绍系统

## 核心原则

这个 Skill 主要遵循几条原则：

- 先策略，后执行
- 先证据，后形容词
- 先当前真实，后未来想象
- 先清晰，后包装

它会刻意区分三件事：

- 现在已经真实成立的内容
- 现在能够可信提供的价值
- 未来正在成长的方向

这样做的目的，是避免把一个人写得过度包装，同时也不抹掉他已经真实具备的经历、能力和成绩。

## 仓库结构

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

## 主要文件说明

真正用于 Codex 调用和复用的 Skill 文件是：

- `skill-en/SKILL.md`
- `skill-en/agents/openai.yaml`
- `skill-en/references/framework.md`

`docs-zh/` 目录下的中文文件，主要是给中文读者阅读和理解方法用的辅助说明。

## 使用方式

如果要在 Codex 中调用这个 Skill，主要入口是：

- `skill-en/SKILL.md`

默认调用方式可以写成：

```text
Use $personal-brand-strategist to help me clarify my personal brand, positioning, channels, and messaging system.
```

## 说明

- 这是一个通用 Skill，不绑定某个具体人物或行业
- 它主要解决的是上游品牌策略问题，不只是写文案
- 它尤其适合那些“经历很多，但整体表达还不够清楚”的人
