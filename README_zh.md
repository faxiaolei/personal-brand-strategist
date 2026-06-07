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

## 方法参考 / 灵感来源

这个 Skill 不是对某一个作者或某一套框架的直接照搬，而是在通用化和实用化过程中，吸收了几本书里的部分思路：

- `《Obviously Awesome》` - April Dunford：定位、差异化、受众匹配
- `《Building a StoryBrand》` - Donald Miller：表达清晰、信息传达、可理解性
- `《The Brand Gap》` 与 `《Zag》` - Marty Neumeier：品牌结构、战略一致性
- `《Platform》` - Michael Hyatt：平台思维、渠道角色、长期内容资产
- `《Blue Ocean Strategy》` - W. Chan Kim、Renee Mauborgne：价值创新与被忽视市场的切入思路

这些内容只是方法上的启发来源，不代表这个 Skill 是对任何单一本书的官方复刻。它本身是一套面向 Codex 使用场景整理出来的、可复用的个人品牌策略框架。

## 说明

- 这是一个通用 Skill，不绑定某个具体人物或行业
- 它主要解决的是上游品牌策略问题，不只是写文案
- 它尤其适合那些“经历很多，但整体表达还不够清楚”的人
