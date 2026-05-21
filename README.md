# deep-thinking skill

一个用于 Codex 的深度思考与决策引导技能。

它不是为了更快给出答案，而是像一个思考陪练一样，通过真问题诊断、事实拆解、结构分析、主要矛盾、动态变化、策略与行动，帮助用户把复杂问题想清楚。

## 适合什么场景

- 职业选择，例如「我该不该跳槽」
- 团队管理，例如「团队是不是该换人」
- 产品方向，例如「这个项目还要不要继续」
- 人际关系、亲密关系、创业决策等越想越乱的问题
- 任何用户明确希望「深入思考」「分析本质」「用第一性原理想想」的场景

## 不适合什么场景

- 明确、低成本、可以直接回答的问题
- 普通技术问答
- 用户只想快速得到一个现成答案的场景

## 安装方法

在 Codex 中，可以让内置的 `skill-installer` 帮你安装：

```text
使用 skill-installer 帮我从 GitHub 安装 KY2026AI/deep-thinking-skill 仓库里的 skills/deep-thinking 技能。
```

也可以在本机命令行中运行：

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo KY2026AI/deep-thinking-skill \
  --path skills/deep-thinking
```

安装完成后，重启 Codex，让新技能生效。

## 使用方法

安装后，在 Codex 中直接提出需要深入思考的问题即可，例如：

```text
帮我用 deep-thinking 深入分析一下，我到底该不该换工作。
```

或者：

```text
我最近团队管理有点卡住了，用第一性原理帮我想想这个问题。
```

## 技能文件

技能主体位于：

```text
skills/deep-thinking/SKILL.md
```
