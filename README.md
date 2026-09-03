# My AI Dev Kit

我在日常开发中反复使用、验证和迭代的 AI 开发资产集合，包括 Skill、插件、Prompt 与工作流。

这里优先沉淀真正改变 Agent 行为、能够复用的内容。项目专属事实、临时排障记录和密钥不会放入本仓库。

## 内容导航

| 目录 | 内容 |
| --- | --- |
| [skills](./skills/) | 可独立使用的 Agent Skill |
| [plugins](./plugins/) | 插件说明、配置与使用经验 |
| [prompts](./prompts/) | 可直接使用或改造的 Prompt |
| [workflows](./workflows/) | 多阶段开发与审查流程 |
| [templates](./templates/) | 新增内容时使用的轻量模板 |

## 收录原则

一个内容适合进入这里，通常需要满足：

- 已在真实开发任务中使用，而不只是概念草稿
- 能说明适用场景、输入、输出和限制
- 不依赖私有环境才能理解
- 不包含账号、密钥、内部地址或其他敏感信息
- 修改时直接更新当前结论，不保留无价值的历史辩解

## 推荐结构

```text
skills/<skill-name>/SKILL.md
plugins/<plugin-name>/README.md
prompts/<prompt-name>.md
workflows/<workflow-name>.md
```

新增内容可从 [templates](./templates/) 复制对应模板。README 中只维护导航和简短说明，完整内容放在各自目录中。

## 状态标记

内容可在文档开头使用以下状态：

- `draft`：仍在试验
- `active`：当前常用
- `stable`：经过多轮验证，变更较少
- `deprecated`：保留用于迁移，不建议继续使用

## 使用说明

仓库内容默认作为个人开发实践参考。复制到其他项目之前，请根据目标 Agent、工具权限、运行环境和代码仓约束进行调整。
