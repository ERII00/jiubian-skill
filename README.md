# 九边 Skill for Claude Code

> 基于九边《向上生长》《复杂世界的明白人》《西方博弈往事》三本书及公众号"九边""六镇"内容蒸馏而来的 Claude Code Skill 工具箱。

---

## 九边是谁

九边，作家、自媒体人、世界500强企业高管。微信公众号「九边」「六镇」，全网粉丝近千万，2023年印象笔记收藏量排名第一的公号博主。

理工男出身，却把金融、历史、经济写得让普通人一看就懂。他的核心特质：用最简单的语言表达最深刻的道理，不装，不鸡汤，有立场。

---

## 工具箱

| Skill | 触发方式 | 做什么 |
|---|---|---|
| `/jiubian` | `/jiubian`、`九边会怎么说` | 主入口，自动路由到合适的工具 |
| `/jiubian-analyze` | `/九边-分析`、`帮我分析一下` | 问题分析。用九边框架看透本质 |
| `/jiubian-grow` | `/九边-成长`、`我该怎么选择` | 个人成长决策。向上生长方法论 |
| `/jiubian-explain` | `/九边-解释`、`XX是什么意思` | 大白话解释复杂概念 |
| `/jiubian-write` | `/九边-写作`、`帮我用九边风格写` | 模仿九边文风写作 |

---

## 核心框架（蒸馏自三本书）

```
熵增定律（不进则退）
    ↓
内卷化陷阱（原地打转）
    ↓
均值回归（强者终将平凡，除非用道具对抗）
    ↓
资源边界（边界可以扩展）
    ↓
链接即财富（积累形成涌现）
```

---

## 安装方法

```bash
# 推荐：一行安装
npx skills add [你的GitHub用户名]/jiubian-skill
```

或手动安装：

```bash
git clone https://github.com/[你的GitHub用户名]/jiubian-skill.git /tmp/jiubian-skill && cp -r /tmp/jiubian-skill/skills/jiubian* ~/.claude/skills/ && rm -rf /tmp/jiubian-skill
```

---

## 使用方式

在 Claude Code 中：

```
/jiubian 我最近感觉成长很慢，不知道该怎么办
```

```
/jiubian-analyze 为什么我做什么事都坚持不下去
```

```
/jiubian-explain 负利率是什么意思，对我有影响吗
```

```
/jiubian-write 帮我写一篇关于"大多数人没努力过"的文章
```

---

## 原理

每个 SKILL.md 包含：
- 角色定义（九边的世界观、说话方式、禁区）
- 核心框架（从三本书中提炼的方法论）
- 分析/写作流程
- 示例对话

这些框架从九边的《向上生长》《复杂世界的明白人》《西方博弈往事》三本书及公众号内容中提炼，覆盖个人成长、财富认知、历史经济分析、写作风格等方向。

---

## 参考项目

灵感来自 [dontbesilent2025/dbskill](https://github.com/dontbesilent2025/dbskill)

---

## 原作者

[九边](https://mp.weixin.qq.com/) — 微信公众号「九边」「六镇」
