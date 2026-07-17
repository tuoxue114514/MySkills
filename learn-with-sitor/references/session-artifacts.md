# Session Artifact Templates

Use these templates only when the learner requests the corresponding artifact or when the course is ending. Populate every claim with evidence from the conversation; write “尚无证据” instead of guessing.

## Route map

```markdown
# 学习路线：<topic>

目标能力：<observable outcome>

| 节点 | 作用 | 前置依赖 | 掌握证据 | 难度 | 状态 |
|---|---|---|---|---|---|
| ... | ... | ... | ... | ... | locked / learning / review / mastered |

当前节点：<node>
下一解锁条件：<evidence required>
```

Show dependency arrows or a Mermaid graph only when the relationships are not clear in the table.

## Learner profile

```markdown
# 当前学习画像

- 学习目标与场景：
- 已稳定掌握：
- 当前已掌握、待延迟复测：
- 薄弱知识：
- 常见错误与易混概念：
- 推理与表达习惯：
- 有效的讲解方式：
- 无效或低效的讲解方式：
- 当前节点及四维评分：
- 评分证据：
- 下一步训练重点：
```

## Portable learning archive

```markdown
# Sitor 学习档案

## 课程上下文
- 主题：
- 目标：
- 使用场景：
- 目标水平：
- 时间约束：
- 指定资料或范围：
- 学习偏好：

## 路线与进度
- 已完成节点：
- 当前节点：
- 待学习节点：
- 节点依赖：

## 掌握证据
| 节点 | 准确性 | 深度 | 迁移 | 辨别 | 综合 | 关键证据 |
|---|---:|---:|---:|---:|---:|---|
| ... | ... | ... | ... | ... | ... | ... |

## 薄弱点与错误模型
- ...

## 教学适配
- 有效方式：
- 避免方式：
- 合适难度与节奏：

## 待复测项目
- <item, due time, retrieval task>

## 下次继续指令
请先读取本档案，从“<current node>”开始，用一个无提示回忆问题验证保留情况；根据表现恢复教学或更新路线。
```

## Spaced-review plan

Default checkpoints after initial mastery:

- 10 minutes
- 1 day
- 3 days
- 7 days
- 14 days
- 30 days

At each checkpoint, prioritize active retrieval over rereading. Choose one or more of: no-prompt explanation, rapid judgment with reasons, error correction, variant problem, cross-context application, or retest of a previous misconception.

Adjust the next interval from performance:

- effortless and accurate: lengthen it;
- correct but effortful: retain it;
- wrong or incomplete: shorten it and reteach the specific gap.

Use absolute dates when the current date is available. Distinguish a suggested schedule from an actually created reminder or automation.

