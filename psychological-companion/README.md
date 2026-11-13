# 心理支持与有效努力陪伴团

[English](README.en.md)

只需召唤一次。你可以直接说正在经历什么、想完成什么，或指出刚才的回应让你不舒服。同一位团长负责倾听、调度、修复和续接。团队有 15 位可点名的心理视角成员，以及方向与取舍、卡点判断、共同执行、反馈与调整和情绪陪伴员。

## 同一会话里的例子

| 你说 | 团队怎么接 |
| --- | --- |
| 今天只想讲一件事 | 团长先听，围绕这件事回应 |
| 请依恋和心智化各看一次 | 实际调用两位成员，对照各自看到的细节 |
| 有点沮丧，但我还想把这段读完 | 接住沮丧，然后一起读眼前这一段 |
| 我说了要一起做，你怎么又给我列计划 | 团长承认错在重复规划。按需请情绪陪伴员，落实用户希望的陪法 |
| 先聊聊为什么这件事这么牵动我。等会儿再做 | 在同一会话暂停任务并探索，用户说继续时从原位置接上 |
| 这段只跟团长说。然后直接帮我做第一步 | 团长自己回应，按要求进入第一步 |

## 使用与验证

本团已按 WorkBuddy 专家开发规范 v2.0 转化并安装到本机专家目录 `plugins/psychological-companion`，已通过 `validate_expert.py` 静态校验并注册到 `marketplace.json`，可在「专家中心 → 我的专家」中看到。成员展示名改为三字花名，原视角/职能名保留在上表与团长成员表中，用户点名任一名称都能路由到同一 Agent ID。头像沿用原包统一的青绿色图标风格，可手动替换为 512×512 PNG/JPG（≤500KB）。成员实际调用效果与上述对话用例仍建议在客户端逐条验证。

```text
.codebuddy-plugin/plugin.json
settings.json
agents/
avatars/
README.md
README.en.md
```

[WorkBuddy 专家团规范](https://open.workbuddy.cn/docs/expert-team) · [专家创建入口](https://open.workbuddy.cn/docs/expert)

## 成员

| 花名 | 视角 / 职能 | English | Agent ID |
| --- | --- | --- | --- |
| 沈溯源 | 心理动力学 | Psychodynamic | `psychological-support-psychodynamic` |
| 穆依安 | 依恋取向 | Attachment-Informed | `psychological-support-attachment` |
| 闵知微 | 心智化（MBT） | Mentalization (MBT) | `psychological-support-mentalization` |
| 陈习之 | 图式疗法 | Schema Therapy | `psychological-support-schema` |
| 戚抒怀 | 个体情绪聚焦（EFT） | Individual Emotion-Focused (EFT) | `psychological-support-emotion-focused` |
| 方在兹 | 格式塔 | Gestalt-Informed | `psychological-support-gestalt` |
| 舒自宽 | 慈悲聚焦（CFT） | Compassion-Focused (CFT) | `psychological-support-compassion-focused` |
| 柯念衡 | 认知行为（CBT） | Cognitive Behavioral (CBT) | `psychological-support-cognitive-behavioral` |
| 任纳川 | 接纳与承诺（ACT） | Acceptance and Commitment (ACT) | `psychological-support-acceptance-commitment` |
| 钟持平 | 辩证行为技能（DBT） | Dialectical Behavior Skills (DBT) | `psychological-support-dialectical-skills` |
| 柳际和 | 人际心理治疗（IPT）视角 | Interpersonal (IPT) Perspective | `psychological-support-interpersonal` |
| 周环生 | 系统式家庭与关系视角 | Systemic Family and Relationship | `psychological-support-systemic` |
| 纪重书 | 叙事疗法 | Narrative | `psychological-support-narrative` |
| 易寸进 | 焦点解决短期疗法（SFBT） | Solution-Focused Brief (SFBT) | `psychological-support-solution-focused` |
| 俞自择 | 存在主义取向 | Existential | `psychological-support-existential` |
| 简取先 | 方向与取舍 | Prioritization | `effective-effort-prioritization` |
| 关未通 | 卡点判断 | Bottleneck Finder | `effective-effort-bottleneck` |
| 陆同行 | 共同执行 | Co-Execution | `effective-effort-co-execution` |
| 顾再调 | 反馈与调整 | Feedback and Adjustment | `effective-effort-feedback` |
| 宁听言 | 情绪陪伴员 | Emotional Companion | `effective-effort-emotion-companion` |

## 参考资料

- [APA · Approaches to psychotherapy](https://www.apa.org/topics/psychotherapy/approaches)
- [APA PsycTherapy · Featured approaches](https://www.apa.org/pubs/databases/psyctherapy/approaches.aspx)
- [Anna Freud · Mentalization-Based Treatment](https://www.annafreud.org/training/health-and-social-care/mentalization-based-treatments-mbt/mentalization-based-treatment-adults/about-mbt/)
- [International Society for Emotion Focused Therapy](https://www.iseft.org/about-us)
- [Gilbert · Introducing compassion-focused therapy](https://doi.org/10.1192/apt.bp.107.005264)
- [Dulwich Centre · Externalising the problem](https://dulwichcentre.com.au/courses/aboriginal-narrative-practice-course/lessons/03-externalising/)
- [Solution-Focused Therapy Institute · What is SFBT?](https://solutionfocused.net/what-is-solution-focused-therapy/)
- [NIMH · Five action steps for supporting someone in crisis](https://www.nimh.nih.gov/health/publications/5-action-steps-to-help-someone-having-thoughts-of-suicide)
- [Motivational Interviewing Network of Trainers · Understanding Motivational Interviewing](https://motivationalinterviewing.org/understanding-motivational-interviewing)
- [NICE · Depression in adults, including behavioral activation](https://www.nice.org.uk/guidance/ng222/chapter/recommendations)
## 成员职业定位（按疗法 / 职能区分）

每位成员的 `profession` 已按各自流派的独特切入点单独定义，不再统一写「AI 心理支持视角」。

| 花名 | 职业定位 zh | Profession EN | Agent ID |
| --- | --- | --- | --- |
| 安续之 | 同会话陪伴与调度总监 | Continuous Companion & Orchestration Director | `psychological-companion-team-lead` |
| 沈溯源 | 心理动力学 · 重复模式探索 | Psychodynamic · Recurring Pattern Exploration | `psychological-support-psychodynamic` |
| 穆依安 | 依恋取向 · 联结需要澄清 | Attachment-Informed · Connection Needs | `psychological-support-attachment` |
| 闵知微 | 心智化 MBT · 心理状态辨识 | Mentalization (MBT) · Mental State Clarification | `psychological-support-mentalization` |
| 陈习之 | 图式疗法 · 核心信念辨识 | Schema Therapy · Core Belief Patterns | `psychological-support-schema` |
| 戚抒怀 | 情绪聚焦 EFT · 当下感受命名 | Emotion-Focused (EFT) · Naming Present Feelings | `psychological-support-emotion-focused` |
| 方在兹 | 格式塔 · 此时此地觉察 | Gestalt · Here-and-Now Awareness | `psychological-support-gestalt` |
| 舒自宽 | 慈悲聚焦 CFT · 自责缓和 | Compassion-Focused (CFT) · Easing Self-Criticism | `psychological-support-compassion-focused` |
| 柯念衡 | 认知行为 CBT · 想法检验 | CBT · Appraisal Checking | `psychological-support-cognitive-behavioral` |
| 任纳川 | 接纳承诺 ACT · 价值小步 | ACT · Values & Small Steps | `psychological-support-acceptance-commitment` |
| 钟持平 | 辩证行为 DBT · 应对技能 | DBT Skills · Brief Coping Options | `psychological-support-dialectical-skills` |
| 柳际和 | 人际 IPT · 关系事件梳理 | IPT · Interpersonal Events | `psychological-support-interpersonal` |
| 周环生 | 系统式 · 互动循环观察 | Systemic · Interaction Cycles | `psychological-support-systemic` |
| 纪重书 | 叙事疗法 · 例外经历挖掘 | Narrative · Unique Outcomes | `psychological-support-narrative` |
| 易寸进 | 焦点解决 SFBT · 例外小步 | SFBT · Exceptions & Small Steps | `psychological-support-solution-focused` |
| 俞自择 | 存在主义 · 取舍与意义澄清 | Existential · Tradeoffs & Meaning | `psychological-support-existential` |
| 简取先 | 任务优先级判断 | Task Prioritization | `effective-effort-prioritization` |
| 关未通 | 执行卡点诊断 | Execution Bottleneck Diagnosis | `effective-effort-bottleneck` |
| 陆同行 | 协同执行搭档 | Co-Execution Partner | `effective-effort-co-execution` |
| 顾再调 | 产出复盘与调整 | Output Review & Adjustment | `effective-effort-feedback` |
| 宁听言 | 任务情绪与对话修复 | Task Emotions & Conversation Repair | `effective-effort-emotion-companion` |
