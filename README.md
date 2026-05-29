<div align="center">

# Hub/Leaf Skills

#### Skill 组织架构工程方法论

[![License](https://img.shields.io/badge/License-MIT-3B82F6?style=for-the-badge)](./LICENSE)
[![Skills](https://img.shields.io/badge/Skills-1-10B981?style=for-the-badge)](#-skills)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-8B5CF6?style=for-the-badge)](https://agentskills.io)

![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-D97706?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-Skill-10B981?style=flat-square&logo=openai&logoColor=white)
![OpenCode](https://img.shields.io/badge/OpenCode-Skill-3B82F6?style=flat-square)

</div>

当你的 Skill 越装越多、触发词开始打架时，你需要的不是"再整理一下"，而是一套**有安全保障的工程方法论**。

这个仓库收录经过实战验证的 Skill 组织架构工具。

---

## Skills

| 名字 | 一句话 |
|---|---|
| [**hub-architect**](./hub-architect/) | 把多个 Skill 组织成 Hub/Leaf 架构，含 7 步安全迁移、5 道回归门禁、证据三角验证 |

---

## 安装

在 Claude Code、Codex、OpenCode 等支持 Skill 的 Agent 里：

```
帮我安装这个 skill：https://github.com/yitaioumiga/hub-leaf-skills/tree/main/hub-architect
```

---

## hub-architect 方法论概览

不是"搭个路由就完事"。覆盖从搭建到验证到回滚的完整工程链路：

| 部分 | 内容 |
|---|---|
| **核心概念** | Hub/Leaf 三层结构、什么适合做 Hub |
| **安全迁移（7 步）** | 基线快照 → 隔离备份 → 替换并删除 → 映射更新 → 证据三角 → 回归门禁 → 清理 |
| **触发回归测试** | 48 条用例、Python 运行器、5 道验收门禁（A/B/C/D/E） |
| **6 条强规则** | 备份先行、加载隔离、回归放行、证据三角、双根复审、触发格式规范 |
| **备案与回滚** | 备案清单、回滚流程、Gate 失败处理 |
| **设计模式** | 按工具/产出物/意图归类 + 大型 Hub 分层策略 |
| **真实案例** | 8 个 Hub（60+ 叶子）实战参考 |

方法论来源：8 个 Hub 迁移实战、48 条回归用例、3 轮回归验证、L0-L4 知识沉淀体系。

---

## 目录结构

```
hub-architect/
├── SKILL.md                        # 主文件（534 行）
└── references/
    ├── hub-leaf-checklist.md       # 搭建清单
    ├── real-world-hubs.md          # 8 个真实 Hub 案例
    ├── strong-rules.md             # 6 条强规则详解
    └── regression-runner.md        # Python 回归运行器
```

---

## 跨平台

Claude Code · Codex · OpenCode · OpenClaw，遵循 [Agent Skills](https://agentskills.io) 开放标准。

---

<div align="center">

[MIT License](./LICENSE) · 自由使用 / 修改 / 再分发

Made by [@yitaioumiga](https://github.com/yitaioumiga)

</div>
